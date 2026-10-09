---
layout: post
title: "What 150+ hyperscale deployments taught me about clean turnover"
date: 2026-10-06 08:10:00 -0500
image: /images/covers/racks.svg
category: Data Center
description: The habits that keep a data center connectivity build on track from EDP review to NOC sign-off.
---

Over 150+ Meta hyperscale deployments, the goal at the end of every site is the same: hand it to the NOC with zero defects. Here's what I've learned about getting there.

## 1. Catch problems on paper first

The cheapest fix is the one made before anything is installed. I review the BOM and EDP against the design before work starts, and I adjust cabling layouts and patch panel assignments while they're still just lines on a page.

## 2. Test everything against the loss budget

Each site has hundreds of endpoints to validate: singlemode, multimode, MPO, AOC/DAC, and copper. A link that "lights up" isn't the same as a link that passes. OTDR traces, light meter readings, and insertion and return loss numbers tell you whether it will hold up.

## 3. Write the procedure down

When several sites are running at once, consistency comes from MOPs and SOPs, not memory. Written procedures aligned with TIA-568, BICSI, and NEC mean every crew installs, tests, and cuts over the same way.

## 4. Photos settle arguments

When an installation has a deficiency, a pre/post photo package makes it clear what was wrong and that it was fixed. It keeps vendor follow-ups short and objective.

## 5. As-builts are part of the job

The site isn't done until the documentation matches what's physically there. Accurate as-builts and turnover packages are what the next team relies on.

---

*More field notes coming. If you work in data center connectivity, I'd like to hear what's worked for you.*
