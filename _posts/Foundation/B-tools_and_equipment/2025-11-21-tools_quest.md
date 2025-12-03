---
toc: false 
layout: post
title: Tools Journey 
description: Journey with development tools -- GitHub, Cloning, Virtual Environments, and Running a local website.
permalink: /tools/journey
---

## Visual Journey

Linux is the most compatible OS for Developers.  

![Tux the Linux Mascot]({{site.baseurl}}/images/tux.png)

This visual helps remind me of the steps I’ve taken in my Computer Science journey.

```mermaid
flowchart TD
    subgraph Day1[Days 1-3: Getting Started]
        A[Created GitHub Account]
        B[Set Up Slack]
        C[Made First GitHub Repository]
    end

    subgraph Day2[Days 2-5: Learning GitHub Features]
        D[Learnt GitHub Issues]
        E[Practiced Commits and Pushes on GitHub Website]
        F[Explored VSCode Web Version]
    end

    subgraph Day3[Days 5-10: Moving to VSCode App]
        G[Installed VSCode on OS]
        H[Cloned Repository Using Terminal]
        I[Edited Files Locally]
        J[Learnt Full Commit → Push Workflow]
    end

    subgraph Day4[Day 10-12: Understanding Process Discipline]
        K[Followed Steps Carefully]
        L[Realized Missing Any Step Causes Errors]
    end

    A --> B --> C --> D --> E --> F --> G --> H --> I --> J --> K --> L
