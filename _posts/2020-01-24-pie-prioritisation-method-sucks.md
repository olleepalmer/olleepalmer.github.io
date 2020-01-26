---
layout: post
title:  "The PIE method sucks (but it’s the best we've got)"
hero-header: "The best way I’ve found to manage A/B testing programs"
subhead: "Behind its flimsy facade, this three-letter approach to prioritising a backlog of A/B tests hides an elegant and effective framework for communication, collaboration and consensus-building."
excerpt: "Take a handful of guesstimates and then get the average. Surely there's a better way to prioritise your A/B testing program? I used to think so too."
categories: [blog]
permalink: "/blog/pie-prioritisation-method-sucks"
slug: "2020-01-24-pie-prioritisation-method-sucks"
description: "Some thoughts about the PIE method for A/B test prioritisation"
---

{% include image-large.html name="pie-score.svg" caption="PIE score: Ostensibly the average of three guesstimates" %}

If you’re running more than one or two A/B tests a month, you need a prioritisation method. If you’re working with a team that’s bigger than just you, you need a prioritisation method.

Actually, even if it’s just you, you need a prioritisation method.

## Why you need a prioritisation method

Formal prioritisation helps you to avoid waste time and energy on low impact, high effort tests.

It makes sure that you focus on where you can get the best results for the least effort.

The process of prioritisation with a group has the added benefit of building buy-in and investment in the direction of your testing program.

## How PIE  works

First [proposed by Chris Goward at Wider Funnel back in 2011](https://www.widerfunnel.com/how-to-prioritize-conversion-rate-optimization-tests-using-pie/), PIE has since become the defacto standard for A/B test prioritisation.

Optimizely&#39;s Program Management tool uses it natively as too, I understand, does VWO&#39;s equivalent.

PIE scoring works like this:

You assign each test candidate a score out of ten according to the following criteria:

<ul class="list">
<li><strong>Potential</strong>- How much improvement can be made?</li>
<li><strong>Importance</strong> - How valuable is the traffic to the pages?</li>
<li><strong>Ease</strong> - How complicated will the test be to implement?</li>
</ul>

After you’ve scored, you then take the average of the 3.

The number that’s left over?

That’s your PIE score.

Is it scientific? It is not.

Is it useful? It certainly is.

## Why PIE sucks

If you scroll down to the comments section at the bottom of [the blog post which introduced PIE to the world](https://www.widerfunnel.com/how-to-prioritize-conversion-rate-optimization-tests-using-pie/), you’ll see a comment from one “OCP” (that’s me, Oliver Charles Palmer in anonymous troll mode) basically calling bullshit on the whole endeavour.

> _Isn’t the PIE score just an aggregation of a few guesstimates turned into a number out of ten?_


{% include image-large.html name="ocp-pie-troll.jpg" caption="Me anonymously trolling on the original PIE score blog post" %}

To which Chris thoughtfully responds:

>  As with many good strategic frameworks, it’s a mix of objective and subjective measures ... If it was all just data that could be pulled from an analytics report, we wouldn’t need talented strategists to do it. We could just write an algorithm! But, it’s not this simple.

He is right.

Anonymous troll me is also right, incidentally, but more on that in an a moment.

## Surely there's something better?

Now and then, new prioritisation methods crop up.

Here's a handful of the more widely adopted ones:

### ICE

Developed by the team at Growth Hackers, [ICE](https://blog.growthhackers.com/the-practical-advantage-of-the-ice-score-as-a-test-prioritization-framework-cdd5f0808d64) is a fairly popular PIE alternative:

<ul class="list">
<li><strong> Impact </strong>- What will the impact be if this works?
</li>
<li><strong> Confidence </strong> - How confident am I that this will work? </li>
<li><strong>Ease</strong> - What is the ease of implementation?
</li>
</ul>

To my mind, ICE is a slightly improved take on PIE.

I've singled out PIE in this post because it is the method that I use (and the first that I came across, for that matter).

That being said, everything here could equally be applied to ICE or probably any other future 3-letter permutations and variations (including my own take on PIE, below).

**Modified PIE**

In my own work, I actually use a slightly modified version of PIE.

<ul class="list">
<li><strong>Priority</strong>- How much does this align with our business focus?</li>
<li><strong>Impact</strong> - What will the impact be if this works?</li>
<li><strong>Ease</strong> - How complicated will the test be to implement _and_ analyse?
</li>
</ul>

I wasn't aware of ICE when I made these tweaks, but it has the similarity of replacing 'Importance' with 'Impact'.

I began using this version of PIE with my clients because I found myself regularly struggling to explain the difference between &#39;Potential&#39; and &#39;Importance&#39;.

Without thinking about it too much, this version emerged.

I feel like it offers a subtle improvement over the original, even if it uses the same three letters! :-)

### PXL

CXL have developed PXL ([introduced in a blog post which cites my comment above](https://cxl.com/blog/better-way-prioritize-ab-tests/), no less) which adds umpteen different data points (“Above the fold?” and “Noticeable within 5 seconds?”, etc.) in a spreadsheet and then applies a score to your inputs.

I have never investigated PXL in detail, but my feeling is that this is a vain attempt at making prioritisation ‘more scientific’ and giving the result some sort of objective legitimacy.

I think this is utterly too complicated and maddening and silly and I feel sorry for anyone who&#39;s tried to do this on a large backlog in a group environment.

## Why PIE rules

### Simplicity as a feature

PIE (like ICE) offers three simple data points.

It&#39;s not a framework for objective prioritisation.

PIE doesn&#39;t bestow any quasi-scientific legitimacy on the prioritisation choices that we make. Instead, in its beautiful simplicity, PIE puts the onus on us to ask the right questions and use the answers to make sensible, informed decisions.

### Provides a framework for debate

PIE provides a simple and accessible framework for discussion and debate.

This method comes into its own is where you’re running an optimisation program with a range of  stakeholders with competing interests.

If you get everyone involved in the program info a  room once a month and sit down and debate the PIE scores for each test, all parties will typically, in my experience, leave comfortable that you&#39;ve decided on the right tests, for the right reasons.

### Zero embedded values

[As with others like it](https://blog.optimizely.com/2015/05/05/how-to-prioritize-ab-testing-ideas/), the PXL method is riddled with value judgements.

For example, some of the inputs required to score each test are:

<ul class="list">
<li>Is it above the fold?</li>
<li>Adding or removing content?</li>
<li>Noticeable within five seconds?</li>
</ul>

There&#39;s a contextual value judgement in each of these which I think needs to be unravelled in each case.

Also: are we still talking about the fold?

### It's fast

Because you're inputting just three inputs, prioritisation with PIE doesn't have to be a long and complicated process.

If you ever finish PXLing your backlog, give me a shout and we'll compare notes.

## PIE is as good as it gets

As Chris indicates in his comment all those years ago, he was aware that creating a scientific arbiter of impact and effort would be a quixotic struggle.

Instead, PIE gives you a way to focus your intellect and reasoning and facilitate and guide discussion with your stakeholders sensibly and productively.

So yeah, if you’re looking for a magic number-crunching test prioritisation machine, PIE sucks.

For the rest of us, however, it’s an invaluable tool.

Thanks for sharing it, Chris and sorry for trolling you 😉
