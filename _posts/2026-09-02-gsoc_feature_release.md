---
title: GSoC Feature Release 3.6.0 is out
date: 2026-09-02
author: Tim Leonhard
layout: post
---

Google Summer of Code came to an end last week and a lot of work was done by our three participants. All proposals were implemented brilliantly and the changes are all included in our most recent release 3.6.0. Every participant created a blog article describing their project and the results in detail — these articles are linked below:


- [armoredvortex](https://github.com/armoredvortex) implemented a [modular dashboard](https://www.honeynet.org/2026/08/14/16/) that is now configurable for admins. This will make it much easier to add new widgets in the future.
- [drona-gyawali](https://github.com/drona-gyawali) built a new set of [event collection](https://www.honeynet.org/2026/08/11/11/) API endpoints that allow pushing events to GreedyBear. Therefore, it is now possible to use GreedyBear as a honeypot data aggregator independent from T-Pot.
- [opbot-xd](https://github.com/opbot-xd) built a new tool, the [tpot-payload-server](https://www.honeynet.org/2026/08/17/17/). It serves payload files collected by T-Pot, which GreedyBear can fetch, store and deliver to authenticated users.

I want to thank all participants for their excellent work. It was a pleasure mentoring you!

## Other Highlights
- a new _trending attackers_ feed and a frontend for it, thanks to [rootp1](https://github.com/rootp1)
- NDJSON support for the Feeds API, thanks to [suvani-ctrl](https://github.com/suvani-ctrl)
- OpenAPI documentation of the most important user-facing API endpoints

In the next weeks, we hope to find time to update the Honeynet instance of GreedyBear to the most current version, so that all these new features are available on a public instance.
