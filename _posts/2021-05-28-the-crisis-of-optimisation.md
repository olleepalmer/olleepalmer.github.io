---
layout: post
title: "The Crisis of Optimisation"
hero-header: "The Crisis of Optimisation"
subhead: "If academic research science is having a crisis of integrity, then what can we expect from the world closed door corporate A/B testing?"
excerpt: "If academic research science is having a crisis of integrity, then what can we expect from the world closed door corporate A/B testing?"
description: "If academic research science is having a crisis of integrity, then what can we expect from the world closed door corporate A/B testing?"
categories: [blog]
image: "/img/crisis-of-optimisation-illustration.png"
permalink: "/blog/the-crisis-of-optimisation"
slug: "2021-05-31-the-crisis-of-optimisation.md"
---

{% include image-large.html name="crisis-of-optimisation-illustration.png" caption="Illustration by @popiumworks" alt="Illustration of website optimisation" %}

Scientific truth is meant to be beyond reproach.

The idea that an experiment will produce the same results every time is a cornerstone of the scientific method.

But science is in turmoil.

Over the last fifteen years, successive waves of scandal has plunged science into disarray. Cases of dubious research methods, ‘data dredging’ and [even outright fraud](https://en.wikipedia.org/wiki/List_of_scientific_misconduct_incidents) have emerged with alarming regularity. Foundational studies [have been retracted](https://www.vox.com/2018/6/13/17449118/stanford-prison-experiment-fraud-psychology-replication) in droves and entire disciplines decimated. Even [Nobel Prize winners have been implicated](https://www.nature.com/articles/d41586-019-03755-2).

If the transparent, peer reviewed world of academia is fraught with this crisis of integrity, then what can we expect from the vastly less scrutinised corporate ‘science’ of A/B testing? It’s not possible to tell exactly how bad it is, but the evidence suggests that overstated, sensationalised and misleading A/B test results are far more common than we’d like to admit.

In this article, I’ll discuss the underlying causes, explore the implications for your testing program and offer advice about how you can guard against threats to the integrity of experimentation within your own business.

## Science in crisis 

In 2005, John Ioannidis, a professor at the Stanford School of Medicine, published an essay called _[Why Most Published Research Findings Are False](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)_. It reported the findings of a statistical model which examined the research methods of thousands of published academic studies.

The results were alarming. In most cases, Ioannidis discovered, the claims made by the research were more likely false than actually true. He confirmed what many had long thought: bogus science was being practised on a grand scale. Scientists were selectively reporting and manipulating data to advance their careers. “At every step in the process,” he said, “there is room to distort results, a way to make a stronger claim or to select what is going to be concluded”. Ioannidis expected a backlash. Instead, there was silence. Even a sense of relief.

In what has since become known as the replication crisis, successive waves of scrutiny and damning evidence has cast doubt upon swathes of academic research. [One survey of 1,500 scientists found that more than 80% had failed to reproduce another scientist's experiments](https://www.nature.com/news/1500-scientists-lift-the-lid-on-reproducibility-1.19970). More than half had failed to reproduce their _own_ experiments.

One open sourced, collaborative effort among psychologists known as [The Reproducibility Project](https://en.wikipedia.org/wiki/Reproducibility_Project) aimed to replicate 100 studies published in psychology journals. Even when working in collaboration with the original authors, they successfully managed to replicate just 36%. Science is not the haven of empirical purity that we formerly imagined. [Even pharmaceutical drug trials have been heavily implicated](https://www.fww.ovgu.de/fww_media/femm/femm_2017/2017_19-p-8998.pdf).

{% include image-columns.html name="wp_ji_photo.png" caption="Ioanaddis hasn't had a great run of late. He's still got a cracking moustache, though." alt="Illustration of website optimisation" %}

The problem brought to light by the replication crisis is not just that experiments cannot be replicated. Irreproducibility is only a symptom. It’s a polite and euphemistic proxy for the practice of bad science itself. The underlying causes are almost invariably the same: poor analysis, selectively reporting results, small sample sizes and low statistical power. But what causes scientists to violate the most fundamental obligations of their role as explorers of empirical truth?

In the wake of Ioanaddis’s paper, the discipline of Metascience has gained prominence. In basic terms, it is the science of science and it seeks to make sense of the problem of replication. Most of the research into the underlying causes identifies two significant factors. Scientists are incentivised for publishing new and novel research and they can reasonably expect to get away with distorting the truth to get there.

### Incentives

Published research is essential for career success in the scientific world. There is a direct link between published research and job opportunities, money and prestige. Publish or perish, as they say.

### Ease of getting away with it

In many fields, raw data is difficult to reproduce. This means that even if a researcher does falsify data, they’re unlikely to be caught. At the very least, they can plausibly claim innocence if contradictory findings do emerge.

## Optimisation has the same issues (plus a confluence of compounding curveballs all of our own)

While the ‘pressure to publish’ is unique to academia, the corporate world is grappling with the same underlying problem. Results or else. Flat or negative outcomes rarely create excitement of any kind, no matter how much potential they hold. My old colleague [Harry Brignull wrote about this](https://90percentofeverything.com/2016/07/12/the-thing-that-makes-user-research-unique/index.html) many years ago in reference to user research:

> The thing about user research is that it delivers bad news every time. It depicts reality – the fact that you don’t control how your customers think, that they see things differently and that changes are needed if you’re ever going to please them. It doesn’t make you look good. That’s the whole point.

While experimentation doesn’t always deliver bad news it is a method for iteratively uncovering and understanding user preferences. It’s not a lottery ticket, but rather an opportunity to observe and measure reality. Most clients don’t want reality, though. They want wins. And if agencies don’t deliver rivers of gold (or claim to have done so), they can expect to lose that client to the next contender who promises that they will. Internal teams that don’t claim significant uplifts are at risk of losing funding, credibility, prestige, and even their jobs.

### Expectations set during the sales process

The stage is set for this conflict well before the team is hired or the agency appointed. Almost invariably, it’s the result of sky high expectations set during an enthusiastic sales process.

Running an experimentation program at scale comes with a high cost. In most organisations, it is a new and unproven endeavour that runs contrary to the established ways of working. Getting the business case over the line normally takes some evangelising: exuberant presentations stuffed with charts that go up and to the right. Dollar signs flash in executive eyes. Expectations have been set.

As an industry, we don’t do ourselves any favours.

Vendors sell tools based on stories of famous tests that generated tens of millions of dollars in revenue. Agencies join in with case studies that parrot the implausible results of miraculous experiments that created outsized impact.

Clients are hungry for results and sales teams at both agency and vendor are hungry to hit their targets. And they’ll promise the moon to get there, reality be damned.

{% include image-large.html name="crisis-of-optimisation-illustration-case-studies.png" caption="Typical case study page. Big numbers but who gives a shit about most of these metrics?" %}

All the while, we hear very little spoken about the routine drudgery of optimisation. The embarrassingly frequent tests with flat or even negative results. Yet the vast majority of business experiments fail to generate a 'winning' result. It's not unusual for a program to deliver many interesting learnings, but no actual incremental revenue for months at a time. The burden of expectation mounts.

### Inexperience

This pressure is compounded by a lack of experience on all sides. Practitioner, client _and_ agency. Business experimentation is only a new discipline. The business world is still gaining basic literacy in the processes and methodology of running experiments at scale.

Unlike scientists, most people working in the field have not been trained in experiment design and statistical analysis. There is no formally recognised training program or certification from a university or academic institution where you can learn how to run a good optimisation program.

As a result, when businesses hire to scale up their optimisation efforts, they are confronted by a dearth of skilled applicants. This means that they frequently wind up hiring enthusiastic practitioners from related disciplines with the right keywords in their Linkedin profile. I should know, as this is precisely how I came to build the in-house optimisation program at Britain’s largest mobile telco back in 2013.

The result of this kind of staffing is that many practitioners are learning on the job. Probably by making lots of mistakes (I know I did). Along the way, they will fall afoul of the bad practices that will undermine the quality of their experiments: stopping tests too soon, getting attached to concepts based on their opinions and beliefs, badly formed hypotheses and altogether worse. Bad experiments and unreliable results follow. In most cases, it’s not malicious. They just don’t know any better.

The wider inexperience and statistical illiteracy within the business world means that such practises frequently go undetected. Clients and executives have swallowed the hype, but they rarely understand the stats or have the skills to make sense of the underlying analysis.

### Unrealistic expectations + inexperience = trouble

When inexperience and imposter syndrome meet high expectations and industry hype (’low hanging fruit’, ‘quick wins’ and million dollar button tests) things can go seriously awry. It’s this confluence of forces which result in test reports written by data science PhD’s that make bold recommendations from correlated but causally unrelated factors and blatantly ignore statistical best practice of any kind. I’ve seen this. I suspect it happens more than you might think.

The slide toward overstated results, overlooking statistical significance and generally fudging the numbers in favour of a good story is slow and insidious.

To protect the integrity and credibility of optimisation in your business, you need to sidestep the dopamine hit of miracle results in favour of the longer, more arduous but ultimately vastly more rewarding and remunerative trudge toward the peak of objective truth.

We have no way of knowing the extent to which bogus optimisation is at large within the corporate world. Unlike academic research, there is no corpus for us to scrutinise of experiment plans outlining process, methodology and results.

When I have had the opportunity to audit optimisation programs, my anecdotal experience suggests that the situation is not great. When I discussed this article with the principle of a CRO agency recently, he suggested it should open with the lines, “Worried about the legitimacy of experiments run within your business? _You should be_.”

## Protect your program through training, scrutiny and realistic expectations 

Fortunately, there are a few small steps that you can take to protect the integrity and legitimacy of your own program.

### Ask pointed questions about statistical significance

To ensure the validity of A/B test results, you need a basic familiarity with the concept of statistical significance. People are unreasonably scared of statistics. But it doesn’t need to be reams of Einsteinesque scribbly equations.

The basic principles of statistical significance can be learned in a few minutes and will vastly improve your ability to identify dubious test results at 50 paces.

No result should be presented without a P value or significance calculation. Anyone who makes decisions based on the results of experiments should be versed in the basics of statistical significance and be prepared to question the results.

### Don’t be afraid to re-run tests

Even at 95% significance, there is a 5% possibility that your brilliant discovery was mere chance alone. Before you make investment decisions on the back of that result, make sure it is real. The simplest way to remove any lingering doubt is to re-run the experiment.

Some practitioners will argue that replication is impractical due to the variable population of a large scale website experiment. This is hokum. If you cannot achieve a similar result in a follow-up experiment, you cannot expect to see that result when you build the change into your site.

What if you don’t have enough traffic? If you don’t have enough traffic to re-run a winning experiment, you don’t have enough traffic to have a serious optimisation program.

At a fundamental level, so much of this problem exists due to the huge expectations placed upon optimisation teams. If you believe the miracle black box
sales pitch, you will be disappointed. [Experimentation is not for everyone](https://oliverpalmer.com/blog/you-probably-dont-need-ab-testing).

You probably won’t miraculously happen upon a small change that generates gazillions of dollars of incremental revenue.
You will stop yourself from doing plenty of dumb things.

You’ll almost certainly undoubtedly unearth fascinating and highly profitable insights into customer behaviour. But the journey is long and taxing and littered with failed attempts, false starts and dead ends. To paraphrase John Ioannidis, optimisation is a noble endeavour but it’s also a low-yield endeavour. And we should be very comfortable with that fact.

_Thanks to [David Mannheim](https://www.davidmannheim.com/), [Craig Sullivan](https://twitter.com/OptimiseOrDie), [Angelo Belardi](https://abelardi.com/), [Tom Critchlow](https://tomcritchlow.com/), [Ali Qasim Naqvi](https://aliqasnaqvi.medium.com/), [Michael Shafer](https://mscp.wordpress.com/) and [Stefan Thomke](https://www.hbs.edu/faculty/Pages/profile.aspx?facId=6566) for reviewing an earlier version of this article. They didn't all agree with my contentions but their feedback was invaluable for refining my thinking._
