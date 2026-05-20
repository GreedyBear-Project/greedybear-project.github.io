---
title: Google Summer of Code 2026 and New Features
date: 2026-05-20
cover: /images/greedybear.png
author: Tim Leonhard
layout: post
---

Today we had a meeting with our three Google Summer of Code participants, who will implement their projects in the next couple of months. They are already quite familiar with the project and the maintainers, as they have been contributing since December last year. It was a pleasure to meet in person after only knowing them from PR reviews and issue discussions. We look forward to working with them on the projects, which will add exciting new functionality to GreedyBear:
- A pipeline to extract payload files from T-Pot instances.
- A new API for injecting events into GreedyBear.
- A major overhaul of the Dashboard, making it extensible and modular.


Huge thanks also to everyone else who contributed over the past months — many of them appear by name below.

## New features
Since the v3 release post, a lot has changed. Thanks to all these new contributors, we modernised the project's foundation, added loads of test cases, and shipped a number of new features. All of these are available in our latest release, 3.5.1 — here are some of the highlights:

### Feeds API
- Support for STIX 2.1 export, thanks to [R1sh0bh-1](https://github.com/R1sh0bh-1).
- Users can create shareable feed URLs (and share them), thanks to [R1sh0bh-1](https://github.com/R1sh0bh-1).
- API responses contain GeoIP information, thanks to [drona-gyawali](https://github.com/drona-gyawali).
- Tracking of IoC-to-Sensor relationships, thanks to [rahulgunwanistudy-2005](https://github.com/rahulgunwanistudy-2005).
- Enrichment from external sources (ThreatFox and AbuseIPDB), thanks to [opbot-xd](https://github.com/opbot-xd).

### Honeypot support
- New specialised extraction process for the honeypots Tanner and Heralding, thanks to [rootp1](https://github.com/rootp1).

### Frontend
- Attack Origin Visualizer on the Dashboard, thanks to [armoredvortex](https://github.com/armoredvortex) and [chauhan-varun](https://github.com/chauhan-varun).
- Enrichment Lookup component on the Dashboard, thanks to [armoredvortex](https://github.com/armoredvortex).
- Dynamic GreedyBear news widget, thanks to [drona-gyawali](https://github.com/drona-gyawali).

### Setup & Maintenance
- New `gbctl` setup/update script for easier installation, thanks to [opbot-xd](https://github.com/opbot-xd).
- New health overview endpoint, thanks to [drona-gyawali](https://github.com/drona-gyawali).

### Under the hood
- Migration from Celery/RabbitMQ to Django Q2, thanks to [opbot-xd](https://github.com/opbot-xd).
- Migration from uWSGI to gunicorn, thanks to [SupRaKoshti](https://github.com/SupRaKoshti).
- Several frontend migrations: from Create React App to Vite, from Jest to Vitest, and an upgrade to React 19, thanks to [R1sh0bh-1](https://github.com/R1sh0bh-1), [armoredvortex](https://github.com/armoredvortex) and [rootp1](https://github.com/rootp1).
- Migration of Python tooling to uv.
- Docker build improvements that cut the image size in half and drastically reduced build times.

Special thanks to [rahulgunwanistudy-2005](https://github.com/rahulgunwanistudy-2005) for an impressively efficient data migration that [normalises credentials into a separate model](https://github.com/GreedyBear-Project/GreedyBear/pull/902).
