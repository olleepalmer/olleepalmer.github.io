---
layout: post
title:  "The best way I’ve found to manage A/B testing programs"
hero-header: "The best way I’ve found to manage A/B testing programs"
subhead: "You could use a messy spreadsheet or buy a custom built tool, but a simple kanban board in (gasp!) Jira is the most deliciously simple and effective method that I’ve found."
excerpt: "You could use a messy spreadsheet or buy a custom built tool, but a simple kanban board in (gasp!) Jira is the most deliciously simple and effective method that I’ve found."
categories: [blog]
permalink: "/kanban-AB-testing-program-organisation"
slug: "2019-09-23-kanban-AB-testing-program-organisation"
---
There are a lot of moving parts in an A/B testing program.

You need to manage idea submissions, prioritise a backlog, manage design and development. Not to mention, keep all your stakeholders informed along the way.


## The problem with spreadsheets

Not long ago the defacto standard was to use a spreadsheet as an organisational tracker, Optimizely still host a template on their site that you can download.

I used one for years.

The thing is: they completely suck.

With all the different data points and extended blocks of text, the whole thing gets cluttered and messy almost immediately. It doesn’t take long before you’re spending more time fiddling about with formatting than doing actual useful work.

{% include image.html name="optimizely-spreadsheet-example.png" caption="This is how we organised tests until, well, not that long ago" %}


Pasting visuals into tiny cells is cumbersome and there’s no simple way to link and attach test plan and reporting documentation. It technically works but it’s really just just a pretty shitty way of doing things.


A few years ago I saw one of the guys who runs Atlassian’s testing program present a deliciously simple alternative: a Kanban board.


{% include image-large.html name="kanban-columns.svg" caption="The magical columns of Kanban power" %}


They use five columns which show the progress of an idea from, well, an idea, to a finished test.

<ul class="list">
<li>Idea</li>
<li>Prioritised Backlog</li>
<li>Working/Building</li>
<li>Live</li>
<li>Results</li>
</ul>

I quickly ditched the spreadsheet and, so far, I’ve found this method vastly superior to anything else that I’ve tried.

## Why I like using a KanBan board

### Anyone can easily see what’s happening

With enterprise scale testing, there’s a long list of people who need to know what you’re doing to the website and where.

The ‘Live’ column shows anyone in the business an at-a-glance view of what’s live (this is important for the tech team) what’s in the pipeline and critically, it’s a place where results live.

Not only can the proverbial offshore QA team or the dev on pager duty trying to debug a site issue see exactly what tests you’re running and what you’re doing, it can be useful to organise your own workflow as well.

### It’s easy to manage your workflow

At any one time you have a single at-a-glance view of your whole testing pipeline.

You know that you need to work on fixing the flickering on the purple widget test.

You know that you need to write up the results on the bright orange button test.


### Results have somewhere to live

In too many businesses, A/B test results become apocryphal.

The report shared around by email six months ago becomes at best forgotten or at worst or at worst alive in the collective memory yet distorted beyond recognition.

So many times, I’ve seen the mythical idea of a particular test be invoked as an arbiter of truth  to advance dubious or ill considered agendas, without anyone actually referring to the research in question.

By keeping an active test repository of results, you can ensure that the data is always close to hand.

## You don’t have to use Jira (but it sometimes helps)
I hated Jira for a long time. It bears many of the hallmarks of software designed by developers for developers with scant regard for usability.

But it’s getting better.

Depending on your business, getting a Jira board set-up can take you anywhere from between a couple of hours and a couple of weeks.

You’ll need to track down the resident admin and convince them to set things up for you. In my experience, they’re often a BA or a dev or a sysadmin who you’ve never met who probably doesn’t much want to help.

They’ll ask you to write a maddening flow document (give me a shout if you need help with this and I can send you the one that I normally use).

You can set up a board like this in about 3 minutes on Trello and it does almost the EXACT same thing.

## So why bother using Jira?

When working with a business that already uses Jira, I make sure to use Jira.

The main reason for this is... it’s one less barrier to getting stakeholders involved in the testing program. If everyone’s already got a Jira login, it’s easy and straightforward for them to view the testing board as part of their natural ecosystem.

The aim of a winning experimentation program is to bring optimisation to the heart of everyday processes and decision making.

For almost all of my clients, Jira and Confluence are the system of record where decisions are logged, documentation and requirements kept. Simply, it’s where the work happens.

Everyone already has a Jira account. That makes logging a test idea as simple and natural as writing an email.

Trello is vastly more intuitive and easier to set-up. Some businesses are run entirely on Trello (mine is). In that case, please use Trello.


But I’d be wary of introducing a Trello board to a business that uses Jira or something else

## What about custom built tools?

After ignoring it for years, I’ve recently started using Optimizely’s Program Management too with one client.

We’ve only been up and running for a few weeks, but I’ll post some thoughts about that once I’ve got a clearer idea on its strengths and weaknesses.

How do you organise your testing program?
