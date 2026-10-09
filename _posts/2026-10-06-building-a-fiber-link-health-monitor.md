---
layout: post
title: "Why I built a fiber link health monitor"
date: 2026-10-06 08:20:00 -0500
image: /images/covers/dashboard.svg
category: Projects
description: Turning OTDR exports into a pass/fail dashboard with Python, Flask, SQLite, and React.
---

During cluster turn-up, a lot of test data gets generated and a lot of it sits in exported files. I wanted a faster way to see which links were failing, and where loss was trending the wrong way, at the rack and site level.

## What it does

The [Fiber Link Health Monitor](https://github.com/AInturi18/fiber-monitor) is a small pipeline that:

1. **Ingests OTDR exports**
2. **Classifies each link** as pass or fail against loss thresholds
3. **Flags failing links and loss trends** on a dashboard

## The stack

- **Python** for parsing and classification
- **SQLite** for storing results
- **Flask** for the API
- **React.js** for the dashboard

## Why it matters

In high-density builds, the question is rarely "did we test it?" It's "which of these hundreds of links needs attention right now?" A dashboard that answers that at a glance saves time during turn-up.

*I'll write a deeper walkthrough of how it works in a future post.*
