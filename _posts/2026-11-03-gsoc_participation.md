---
title: Future GSoC Participation
date: 2026-11-03
author: Tim Leonhard
layout: post
---

Matteo and I had the opportunity to attend the Google Summer of Code Mentor Summit in Munich. It was a pleasure meeting each other in person and talking to other mentors and maintainers. Most of them have the same issue as we do at the moment: how to handle LLM-heavy contributions to our projects.

GSoC 2026 was my first time participating. When we announced our participation in December 2025, I was really surprised by how quickly young people spotted our project and started contributing code to get a foot in the door and make a good impression, hoping we would accept their upcoming proposals.

This year is even crazier to me: we have not announced our participation yet (and to be honest, we don't really know if we will participate at all), but still, half a year before the expected proposal deadline, there are around 20 people who regularly open issues and work on PRs. I really appreciate all the work they have done and how they move the project forward, but I am also aware that most of their work is probably highly automated. Whether it's code or text, the probability that an LLM wrote it is extremely high.

A few weeks ago, I started questioning how I handle those contributions. While most of the contributors are real people, not bots (I guess), I am primarily interacting with LLMs. Code is written by LLMs, comments are written by LLMs; the humans behind them are only proxies. This raises some problems:

- It's just too much work to maintain the project. New issues and PRs usually pop up faster than I can assess and review them. I also use an LLM to assist with reviews, but it's also important to me to check the code with my own brain, understand it and test it locally. Doing this in a way that meets my own standards would require me to maintain the project full-time (which I don't). I know that I could just ignore PRs, and I sometimes do when I don't have much time, but that's not how I'd like to maintain the project.
- New contributors don't learn much. Part of my motivation is to make new contributors familiar with open source and software engineering. If most of their work is automated, their contributions don't make them better software engineers anymore.
- The contributors' incentives point in the wrong direction. At least, that is my assumption. They try to work on as many issues and PRs as possible, thinking that this will increase their chances of becoming GSoC participants. To keep up with the most diligent competitor, they probably see no other choice than to use LLMs extensively. Quantity is more important than quality.
- Evaluating the contributors before GSoC starts becomes difficult. When all you see is LLM output, it's hard to find promising candidates for GSoC. Worse, if we evaluated contributors only by the code they push, we might have a strong bias towards people who can afford better LLMs. We'd like to mentor people who think for themselves, who are critical, who question decisions (including ours), and who can work both independently and in cooperation with others.

That's why we will do things differently from now on by establishing an AI policy for the project that includes a simple rule: **Every contributor who is interested in participating in any future GSoC must not use any LLM-based tools**. We are aware that LLMs are now part of the workflow of most software developers and that they probably won't go away any time soon. Still, we hope that banning their use for contributors interested in GSoC will solve all the mentioned problems. In addition, we will add an "AI policy" section to our contribution guidelines and an `AGENTS.md` file reflecting this policy. Let's see how it works.
