---
layout: blog
title:  "Kanban A/B testing program organisation"
hero-p: "Like everyone, I used to organise A/B tests in a big spreadsheet. It doesn’t take very long before you run into issues with that method, though."
hero-img: 
hero-img-caption: 
categories: [blog]
permalink: "/a-b-testing-program-organisation"
excerpt_separator: <!--more-->
---
Like everyone, I used to organise A/B tests in a big spreadsheet. It doesn’t take very long before you run into issues with that method, though. 

BIG OL’ UGLY SPREADSHEET

Pasting visuals into tiny cells is cumbersome and there’s no simple way to link and attach test plan and reporting documentation.

A few years ago I saw the guys who run Atlassian’s testing program [present their deliciously simple approach: a Kanban board](https://www.atlassian.com/company/events/summit-us/watch-sessions/2014/archives/collaboration-teams/ab-testing-how-to-break-things-and-fail-fast-without-breaking-things).

ATLASSIAN SCREENSHOT

You have five columns which show the progress of an idea from, well, an idea, to a finished test. 

* Idea
* Backlog
* Working/Building
* Live
* Finished

The purpose of this is primarily to give anyone in the business at at-a-glance view of what’s live (this is important for the tech team) what’s in the pipeline and critically, it’s a place where results live.

In too many businesses, A/B test results become apocraphyl. A report might be shared around by email, forgotten and then the collective memory twists and distorts the results beyond recognisitob. They enter the collective memory and become a way of advancing an agenda without actually referring to the research in question.

Too many times have I heard something like: “Oh yeah, that’s a bad idea, I’m pretty sure we tested that a couple of years back and it bombed” when, in fact, the actual test results either say something completely different or are so outdated or irrelevant that they hold no bearing on the current situation.

By keeping an active test reporistory of results, you can ensure that the data is always close to hand.

You can set these on Trello really easily or (with a bit of finagling) Jira works too. When working with a business that already uses Jira, I make sure to use Jira. The main reason for this is... it’s one less barrier to getting stakeholders involved in the testing program. If everyone’s already got a Jira login, it’s easy and straightforward for them to view the testing board as part of their natural ecosystem.

After ignoring it for years, I’ve recently started using Optimizely’s Program Management too with one client. We’ve only been up and running for a few weeks, but I’ll post some thoughts about that once I’ve got a clearer idea on its strengths and weaknesses.

How do you organise your testing program?