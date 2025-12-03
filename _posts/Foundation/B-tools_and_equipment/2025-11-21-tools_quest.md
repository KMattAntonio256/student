---
toc: false 
layout: post
title: Tools Journey 
description: Journey with development tools -- GitHub, Cloning, Virtual Environments, and Running a local website.
permalink: /tools/journey
---

## Visual Journey

Linux is the most compatible OS for Developers.  

![Tux the Linux Mascot]({{site.baseurl}}/images/tuz.png)

This visual helps remind me of the steps I’ve taken in my Computer Science journey.


```mermaid
flowchart TD
    %% Day 1-7: Computer Setup
    subgraph Day_1[Day 1-7: Computer Setup]
        A[1-3<br/><br/>Created GitHub and Slack account<br/>Joined Open Coding Society Slack<br/>Discussed PII<br/>Cloned OpenCS repo<br/>Set up GitHub Pages]:::dayuno
        B[Installed different ways<br/>WSL, Homebrew, Kasm<br/>Pulled GitHub repo to Linux]:::daydos
    end

    %% Day 4-7: OS Setup
    subgraph Day_2[Day 4-7: OS Setup]
        C[Configured Linux environment<br/>Set up VSCode website<br/>Learned to commit & push changes<br/>Created and managed issues on GitHub]:::daytres
    end

    %% Day 8-10: VSCode App & Terminal
    subgraph Day_3[Day 8-10: VSCode App + Terminal]
        D[Installed VSCode App locally<br/>Cloned repo using terminal<br/>Edited files locally and pushed changes]:::daycuatro
    end

    %% Day 11-14: Git Workflow Practice
    subgraph Day_4[Day 11-14: Git Workflow Mastery]
        E[Learned full Git workflow step-by-step<br/>Practiced terminal-based commits and pushes<br/>Understanding importance of following each step]:::daycinco
    end

    %% Connect the Phases
    A --> B
    B --> C
    C --> D
    D --> E
```
