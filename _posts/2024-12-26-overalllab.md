---
layout: post
title: Lab overview
categories: [security, lab]
tags: [security, lab, tools]
date: 2024-12-26 20:04:00 -600
---

# Overview
## machines

* Host
  * Win 11 Home running Virtualbox
  * 32 GB RAM
* Guests
  * Attackbox
  * SIEM/loghost
  * windows server
  * linux server
  * network equipment?

The plan for this lab is to set up the most barebones "enterprise environment" as one does for a lab. The contents of the lab will vary as I learn more stuff.

## The (current) plan

1. Get machines set up and talking.
2. Get Splunk set up to receive logs
3. Poke Around with AtomicTests and Splunk

### Future Plans

1. build a simple webapp or wordpress site.
2. get it all to deploy automatically via Terraform or Container shenanigans
3. get the security stuff also automatic. everything as code.

But first, gotta do it traditionally.
1. build machines and set it up.
2. containerize.
3. figure out how to make it infrastructure as code.
4. stretch goal: serverless, and serverless security? This is probably just cloud access and role/permissions management, huh.

