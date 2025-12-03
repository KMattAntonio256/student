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

This visual helps remind me of the steps I’ve taken in my Computer Science journey so far.


```mermaid
flowchart LR
    %% Day 1-7: Computer Setup
    subgraph Day_1[Day 1-7: Computer Setup]
        A[1-3<br/><br/>Created GitHub and Slack account<br/>Joined Open Coding Society Slack<br/>Discussed PII<br/>Cloned OpenCS repo<br/>Set up GitHub Pages]:::dayuno
        B[Installed different ways<br/>WSL, Homebrew, Kasm<br/>Pulled GitHub repo to Linux]:::daydos
    end

    %% Day 4-7: OS Setup
    subgraph Day_2[Day 4-7: OS Setup]
        C[Installed VSCode App locally<br/>Cloned repo using terminal<br/>Edited files locally and pushed changes<br/>Configured Linux environment<br/>Set up VSCode localhost<br/>Learned to commit & push changes<br/>Created and managed issues on GitHub]:::daytres
    end

    %% Day 8-10: VSCode App & Terminal
    subgraph Day_3[Day 8-10: VSCode App + Terminal]
        D[learned to make new files <br/> learned mermaid and markdown optional <br/> ]:::daycuatro
    end


    %% Connect the Phases
    A --> B
    B --> C
    C --> D
    D --> E
```
