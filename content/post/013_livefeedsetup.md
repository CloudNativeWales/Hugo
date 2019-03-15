---
author: Lewis Denham-Parry
date: 2019-03-13T12:00:00Z
description: "The one when we tried to figure out how to live stream our meetup"
draft: false
featured_image: /images/posts/livefeedsetup/setup.jpg
slug: 013_livefeedsetup
title: 013_LivefeedSetup.md
---

# Streaming to Wales

Since creating Cloud Native Wales, we've wanted to make sure we can share as much of the content with people throughout Wales.
The reason we setup the meetup was that not everyone could make the meetups and conferences hosted outside of Wales, so we brought it to Cardiff.
But not everyone can make it to Cardiff, so how do we fix that?

## Lessons from Football

I once heard a story about Football being streamed live at 3pm within the UK, outside of the UK people can watch Saturday 3pm kickoffs live but we can't do that with TV services in the UK.
This was due to the fear that no one would turn up to the games, and that ticket sales would drop.
We want to make sure we bring people together and start conversations, not just with speakers but with attendees.
But we also want to make sure that if you can't make the meetup (whether that's from not being able to get to Cardiff, can't arrange child care etc) that you can still learn from the talks.

## Solution

From our first meetup we share swag that we've picked up from conferences.  If you have stickers, people will come.
Since then, we've been able to raffle off conference tickets which encourages people to turn up for a chance of winning.

## Livestream setup

We're going to be using YouTube to stream the event.   Here's a list of software/hardware that we'll be using to get it all to work:

* [OBS](https://obsproject.com)
* MacBook Pro (2017 model)
* [Razor Kiyo webcam](https://www.razer.com/gb-en/gaming-broadcaster/razer-kiyo)
* [Blue Yeti microphone](https://www.bluedesigns.com/products/yeti/)

I've practised this 4 times at home with a private stream and all worked ok, now it's time to try it out live.

## First attempt

So this was our setup:

![Our Setup](/images/posts/livefeedsetup/setup.jpg)

All was going well until I received warnings about the encoding.
There was nothing I could do during the first talk as I'd have to stop the stream to change the settings.
Might need to look at running tests at the venue to confirm connection speeds in the future.
The second talk I reduced the quality but had a better consistency.

## Flying Blind

When the feed was on, I planned to connect to the stream on my phone to confirm audio quality levels.
Due to the encoding issue, the live stream was stuttering to begin with.
When I was attempting to connect to the stream, I just had a spinning logo.
Also, there's about a 20-30 second delay, which is obvious now but was a surprise to me the first time it happened.
By the second talk, it was working fine and the audio levels were great.

## The Video

So here it is, I've set it to the second talk.
Any feedback is welcome, if I remember any other notes from the video I'll update the post accordingly.

<iframe width="560" height="315" src="https://www.youtube.com/embed/5c8gB1U3YPA?start=2638" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>