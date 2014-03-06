---
title: Team Management with Hubot
layout: post
author: adam
published: true
---

When Clay and I first started working together, we quickly realized that we are both total nerds when it comes to team productivity. In just a few weeks, we had built the [first version](https://github.com/cjoh/morning-checkin) of [MorningCheckin](http://www.morningcheckin.com), a lightweight app that lets each team member "check in" every morning and let others know what they "got done" the previous day and what they intend to "get done" today. Our team started using MorningCheckin fastidiously, but after a few months the habit just wasn't sticking. When we arrived at our office in the morning, the first thing we wanted to do was open a new browser tab, wait for MorningCheckin to load, and craft a new checkin using its special syntax.

<!-- more -->

So today, I'm happy to have open-sourced our new experiment in team management: [hubot-github-todos](https://github.com/adamjacobbecker/hubot-github-todos). It's built on top of two things we love: [Hubot](hubot.github.com), an open-source chat robot, and GitHub Issues, a platform that we were already using for bug and feature tracking.

So how does it work? Take a look:

![hubot github todos](http://cl.ly/image/2C3g3B0x311L/Screen%20Shot%202014-01-28%20at%2010.45.52%20AM.png)

In case you didn't catch it: we're taking this whole task management thing and simply putting inside of our team chat. There's no interruption from your current workflow, no website to login to, no database to maintain -- just a few quick commands to learn and you're good to go.

Oh, and there's a bonus. We also needed a way to unobtrusively ask a coworker to do something for us without interrupting what they're doing:

![ask adam](http://cl.ly/image/0o1p2R200X0y/Screen%20Shot%202014-01-28%20at%2010.46.02%20AM.png)

With this small script, we hope to never again ask each other:

- What are you working on today?
- Can you do X for me real quick?
- What's your plan for the week?

If you want to try it for yourself, you can grab the source at [https://github.com/adamjacobbecker/hubot-github-todos](https://github.com/adamjacobbecker/hubot-github-todos) or simply install the package in your existing Hubot with npm. Have fun!
