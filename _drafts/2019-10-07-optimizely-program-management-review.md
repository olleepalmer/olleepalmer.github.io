---
layout: post
title:  "My two month experiment with Optimizely Program Management"
hero-header: "The best way I’ve found to manage A/B testing programs"
subhead: "After ignoring it for years, I recently spent two months using Optimizely’s experimentation program organisational tool. Instead of helping, it actually made things more difficult."
excerpt: "After ignoring it for years, I recently spent two months using Program Management, Optimizely’s experimentation program organisational tool. Instead of helping, it actually made things more difficult."
categories: [blog]
permalink: "optimizely-program-management-review"
---

{% include image-large.html name="program-management.jpg" caption="The dream as it appears from my desk" %}


Let’s get this out of the way: I love Optimizely. I’ve been using it daily since 2013 and it’s hands down the best experimentation platform out there. 

A couple of years ago, they bought a company called Experiment Engine and rebranded it as Program Management. It’s a product thats designed to help businesses organise and scale up their experimentation programs.

Without having laid hands on it, I was always a bit skeptic about Program Management, though. I’ve been using a simple Jira Kanban board for years and it works really, really well. 

The major reservations I had were:

1. What could Program Management do better than my Jira board?
2. Is vendor lock-in a great idea? What if we stopped using Opfimizely? We’d have to migrate everything out of there into a third party, independent tool. That would be a major pain. 

A few months ago, one my clients switched to a new type of Optimizely plan and got Program Management thrown in as an added bonus.

Now, I know, if it ain’t broke, etc. but the tool has the explicit remit of helping people to speed up their experimentation programs. That’s exactly what I like doing, so I figured that if we weren’t actually paying for it, it’d be worth seeing how it compares.

So, let’s start with the good things

## What I like

### The reporting 

One of the key reasons we made the switch was because of Experiment Engine’s reporting. At least in principal, it’s great to be able to churn out reports which tell us how many tests we’ve run over each period and where.

The downside is that you have to manually code each test to enable this reporting. 

The reports also propose to be able to tell you your win rate and help to generate a figure which tells you the ROI of your testing program. While this does have a bit of nuance (you can set a positive result for a negative score, for instance), I can see this working in simplistic cases.

### Built in scoring 

Program Management has a built in scoring tool which uses the PIE methodology.

This is a great plus, even if it butchers PIE a bit (more on this later in the post).

When our CSM demo’d Program Management, he mentioned that in his experience people really love the ‘reveal’ moment when the average PIE score is revealed. 

And he’s right! They do. It’s actually pretty fun.

{% include image-large.html name="program-management-scoring.png" %}

### Pre-defined fields

Rather than just an empty block of text as in Jira, each idea submission has a range of predefined fields (‘Hypothesis’, ‘Goal’, ‘Primary metric’, etc.).

This is useful to help stakeholders define their ideas before submitting a test concept. If there’s a field called Hypothesis and Goal, then that encourages them to think about these elements of the test when submitting a concept.


## What I don’t like

### The inflexible scoring method

The PIE Score is not a perfect method of test prioritisation, but it’s the best one we have. I use it with all my clients.

Program Management has built-in PIE scoring, which is great. They also let you customise the labels, which I really appreciate. I use ‘Priority’, ‘Impact’ and ‘Ease’. Program Management let me adjust the labels to these fields. This is a massive plus.

Instead of using a 1-10 score (like pretty much everyone out there, ever), PM uses 1-5 which gives you a lot less nuance.

Most of my clients only run a handful of tests a month. A PIE score 9.1 means that something will be worked on almost immediately, where an 7.2 will probably languish in the queue. Maybe forever.

Using PM’s 1-5 system felt a lot less nuanced. Everything seemed to be a 3.8 or a 4.3 and there didn’t seem be much difference between them.

### ‘Love scores’ are infuriating.

In addition to the standard PIE scores, PM has a mandatory ‘Love’ field that cannot be disabled.

This seems to be designed to allow pushy senior stakeholders to crank up their pet test concept. You may put up with this kind of carry-on in your testing program, but I keep mine in check.


### Adding users is slow and buggy

The login process is complicated and buggy. It’s fairly difficult to work out how to add new users (for the record, there’s a tiny + button that you need to click for someone without an Optimizely account). 

I had to engage support a couple of times to help me add users whose invitations had expired.

### It’s inexorably linked to Optimizely

This is one my biggest gripes.

The interface assumes that anyone you’re adding already has an Optimizely Account. Believe it or not, I actually don’t want all of my stakeholders to have Optimizely logins.

Program Management is inexorably linked to Optimizely, so there’s no way around it.

I need to create logins for users and then I have to explain to them how to get to Program Management  from Optimizely (‘click on the absolutely tiny little triangle in the left corner’). There’s no way for them to go straight to Program Management.

One of benefits of using Jira is that most businesses already use Jira, and most stakeholders already have a Jira login. It’s not something new or foreign or additional, it’s one of the fundamental business tools.

### You can’t @ mention people

Not being able to tag someone in a ticket and create an email notification means that it’s hard to let people know what’s happening.

Even when users ‘watch’ a test, they don’t get notifications when changes are made.

Rather than a vibrant collaborative workspace, Program Management is a lonely island.

### It’s hard to see what’s happening at a glance

This is the big one.

Using a Kanban board, it is always clear to me where I needed to focus my efforts. I could see: here are the new tests that need to be prioritised, here’s what’s running currently, here’s what needs analysis.

In the Program Management interface, it’s just a sea of green circles.

Tests are either ‘Active’ or ‘Archived’.

But we don’t really think in that way; those ‘Archived’ tests contain years of results! And they should be easy to see and to access.

Within each test, you have the option of marking by stage, e.g. ‘Requirements’, Development’, ‘Design’, etc. but you cannot view tests by stage in aggregate.

### No serial number for tests

Jira creates a number for each ticket. 

My first test might be called ABT-1 and my one hundredth test ABT-100. Having a sequential number automatically assigned to each test makes it easy to search and find what you’re looking for. 

Searching for ‘Purple Homepage Widget’ becomes cumbersome and ineffective surprisingly quickly.

If Program Management assigned a short, sequential number to each ‘Idea’ that would be very useful.

It’s not a great place for results

One of the main things I want from a tool such as this is a place where test results can live and be easily referred back to.

Program Management has two states:

‘Live’ and ‘Archived’

If a test has been archived, it literally disappears from view. Past test needs to be present, visible and easily found.

### No ability to filter by stage

Program Management has a great timeline in each ticket where you can mark the stage it’s at, e.g. Idea, Requirements, Development, etc.

The problem is, there’s no way to filter your master list by stage. This meant that I became dreadfully lost. 

Where my Kanban board gives me an at a glance view of what I need to be working on at any minute, Program Management gave me a homogenous list of every test at every stage. 




