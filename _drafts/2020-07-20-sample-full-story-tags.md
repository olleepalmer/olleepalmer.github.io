---
layout: post
title:  "How to sample your Full Story sessions with GTM"
hero-header: "How to sample your Full Story sessions with Google Tag Manager"
subhead: "Get a representative capture of Full Story sessions distributed evenly across each month with this Google Tag Manager trick"
excerpt: "Get a representative capture of Full Story sessions distributed evenly across each month with this Google Tag Manager trick"
categories: [blog]
permalink: "/blog/sample-full-story-tags"
slug: "2020-07-20--sample-full-story-tags"
---

Out of the box, Full Story does not offer any sampling: if you buy a license for 3m visitors and your site gets 50m visitors/month, then you’ll exhaust your impressions within the first week.

Which is a problem.

No one needs to capture a definitive example of session related of every single session.

You want to capture enough to give you a representative sample of what your site visitors are doing.

These instructions are for GTM and Full Story, but you could take this same general approach with any tag manager and any tag that you want to fire for a proportion of site visitors.

## How it works

This method relies on a handful of triggers and a Cookie to bucket visitors into the Full Story group and keep them there.

1. New session
2. Do they have cookie?
3. Yes - show FS tag
4. No - does random number end in defined digits?
5. Yes - generate cookie
6. Then - FS tag fire

### Random number generator

We use the power of random numbers and probability to let people into the tag group.

In this example, we want to fire the tag for 5% of all traffic. We need to set the cookie for 5% of traffic and not set it for the remainder.

This technique uses the probability of a random number ending in predefined digits.

There are 10 single digits between  0 and 9, which means that there is a 10% probability of a random number ending in one of those digits.

### Cookie

If a user visits the site for the first time and the random number ends in between 00 and 007, we will drop the ‘full-story-enabled’ cookie for that user.

### The gate

The ‘gate’ is what we call the tag which looks for the presence of the cookie.

If a user has the ‘fs_enabled’ cookie, they’re let through the gate and the tag fires. If they do not have the cookie, they are not allowed through the gate and the Full Story tag does not fire. Simples!

### Reverse blocking

To make doubly certain that we aren’t allowing any users through who haven’t been allocated an ‘fs_enabled’ cookie we add another, reverse blocking trigger.

In addition to the gate, which fires the tag based on the presence of the Cookie we have a reverse blocking that which specified that the tag should not be fired if the ‘fs_enabled’ tag is undefined.

This is the GTM equivalent of shooting someone that’s already dead but it’s a small amount of extra effort to ensure that the tags are 100% watertight.



<script>
(function(){
  var randomNumber = {{RANDOM_NUMBER}} || undefined;
 // 8% sampling - Numbers ending in 00 to 007
 var regexp = /0[0-7]$/;
 var isFullStoryEnabled = regexp.test(randomNumber);
  document.cookie = "full_story_enabled="+isFullStoryEnabled+"; SameSite=Lax";
})();

</script>




_Thanks to [Simo Ahava](https://www.simoahava.com/) for generously clarifying aspects of this approach for me and correcting my flawed Regex._
