---
title: "Getting Started with Loggly Part 2: The Cool Stuff!"
author: Johnathan Lyman
layout: post
permalink: /2015/03/14/loggly-part-2/
category:
    - Blog
---

This is a continuation of part 1: [Getting Started with Loggly](http://johnathanlyman.com/p/loggly-start).

Note: Apparently waiting hours for account generation isn’t a thing according to the fine folks on twitter @loggly.

> [@theeJL](https://twitter.com/theeJL) Creation takes a few sec so likely something happened during form validation. Perhaps try again or DM us the subdomain you typed in— Loggly, Inc. (@loggly) [March 15, 2015](https://twitter.com/loggly/status/576938047004024832)

<script src="//platform.twitter.com/widgets.js" async="" charset="utf-8"></script>

Now that we’re signed up, let’s get down to the good stuff!

The first thing I want to do is start tracking Linux. The [core of my site](http://johnathanlyman.com/p/stack) is Ubuntu (among other things). Loggly makes this easy. All I need to do is click the Linux icon on my account’s main page.

![](https://i0.wp.com/johnathanlyman.com/wp-content/uploads/2015/03/Screenshot2015-03-1419.52.30.png?w=882)

![](https://i1.wp.com/johnathanlyman.com/wp-content/uploads/2015/03/Screenshot2015-03-1420.01.19.png?resize=693%2C433)

It really is as simple as copying the two lines of code and running them with superuser access. Within a few seconds, Loggly grabbed a hold and started showing me cool stuff!

![](https://i2.wp.com/johnathanlyman.com/wp-content/uploads/2015/03/Screenshot2015-03-1420.05.00.png?w=882)

It’s pretty empty now, because I literally just started tracking and I’m only tracking Linux. With time this will become more populated and more interesting to parse through.

Moving on to other applications, now. I want to start tracking nginx. Nginx is just one of the apps Loggly can track. The list is massive.

![](https://i0.wp.com/johnathanlyman.com/wp-content/uploads/2015/03/Screenshot2015-03-1420.06.39.png?w=882)

Getting Nginx set up was just as easy as Linux, although Loggly believed my Nginx logs weren’t of a proper format. No matter, they’re coming in great.

Getting MySQL set up isn’t a one-click process like the others. This requires MySQL to do some extra work and get a bit re-configured. No worries, it’s nothing extravagant.

Setting up PHP was a breeze, and I like a good breeze.

Once everything was added like I wanted, I started poking through my logs to see if I could really find good data without hassle. Turns out, I can.

What’s better than watching someone from China try to hack into your system via SSH by trying to log in as the root user?

![](https://i2.wp.com/johnathanlyman.com/wp-content/uploads/2015/03/Screenshot2015-03-1420.25.24.png?w=882)

Nothing ![:)](https://johnathanlyman.com/wp-includes/images/smilies/simple-smile.png)

I’d recommend Loggly to anyone who wants to consolidate and be able to parse and search through their log data. You might not need the heavy plans, I know I don’t. It’s still good to be able to look at events as they happen in real time with an interface that doesn’t suck and from anywhere in the world without having to log into your system.

Go check out [Loggly](http://loggly.com), right now. You’ll enjoy it, for sure!

