---
title: "What is DevSecOps?"
image: "images/post/whatisdevsecops.png"
author: "Michelle Ribeiro"
date: 2020-04-11T05:00:00Z
description: "What is DevSecOps?"
categories: ["DevSecOps"]
tags: ["DevSecOps", "DevOps", "Security"]
featured: true

---

###### To better understand what DevSecOps is, lets first revise how we used to think about security before the DevOps moment, during the waterfall times:

<hr>

##### From Reactive Security to Continuous Security

**Reactive Security**: The waterfall methodology introduced a series of sequential processes to get code out the door. From a security stand point of view, the InfoSec team were a kind of gatekeepers, with our activities restricted to act in the final stage of development.

The used to schedule a security audit to revise the application code only after it’s was fully baked, grading the program against some predefined and static list.

After days or weeks, this audit resulted in a PDF with hundreds of pages that went first to the C-Level professionals,  and took another couple of weeks to reach the Development and Operations team to revise, postponing the deploy of necessary changes.

**Monolithic Code**: Not only the company lost time and money, by not separating the unapproved code from the safer one, but also, sometimes, the application went into production anyway! And we all know where this is going, right?

**DevOps + Sec**: With DevOps,  we ensured rapid and frequent development cycles (sometimes weeks or days), but outdated security practices still can undo even the most agile initiatives. Who never had a successful deploy effected by restrictions of the web application firewall (WAF)?

**Automated threads requires automated responses**: Any Internet-facing business has to deal with the bot problem that plagues websites, mobile applications, and the APIs that power them. After all, while almost 58 percent of web traffic comes from humans, the rest comes from bots. Bad bots alone account for almost 22 percent of all web traffic today. This number is only expected to increase.

**Continuous Security**: To prevent these issues, in the rapid changing framework of DevOps, security must become integrated into our pipelines and infrastructure,  from code security to cloud security. We must decentralize and automate vulnerability assessments, giving fast feedback to Dev and Ops members, empowering them to make security assessments and vulnerability fixes as part of their daily routines.

<hr>

#####  The 3 Faces of DevSecOps

Okay, so all that I need to do is to automate some tests and reports and am I doing DevSecOps?

No. Just as DevOps is not just about tools, neither it is DevSecOps.

A good explanation of the term comes from Guy Podjarny, the CEO & Co-Founder of Snyk. On his talk delivered at the Qcon London 2019, he showed us the 3 Faces of DevSecOps:

If **DevOps** can be divided into 3 principles:<br>
1. **DevOps Culture:** Rapid changes, shared ownership, etc
2. **DevOps Methodologies:** Microservices, CI/CD, etc
3. **DevOps Technologies**: Tools such as containers, cloud, etc

Then, somehow **DevSecOps** means to:
1. **Include security into DevOps Culture,**
2. **Secure DevOps methodologies and**
3. **Secure DevOps technologies.**

Simple, right?

{{< youtube eC_Y74sfFrI >}}