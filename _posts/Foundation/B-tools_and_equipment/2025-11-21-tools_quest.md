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

This visual help remind me of Tools and their relationship to my Development Journey. 

mermaid```
flowchart TD
    %% Days 1–3: Accounts & Setup
    subgraph Days1_3[Days 1–3: Accounts & Initial Setup]
        A[Created GitHub Account]:::repo
        B[Created Slack Account]:::repo
        C[Created First GitHub Repository]:::repo
    end

    %% Days 4–6: VSCode Web & GitHub Workflow
    subgraph Days4_6[Days 4–6: VSCode Web & GitHub Basics]
        D[Learned VSCode Website]:::local
        E[Learned Commit & Push Workflow]:::local
        F[Learned to Make & Manage Issues]:::local
    end

    %% Days 7–10: VSCode App & Terminal Git
    subgraph Days7_10[Days 7–10: VSCode App + Terminal Workflow]
        G[Installed & Used VSCode App]:::local
        H[Cloned Repositories Using Terminal]:::cmd
        I[Edited, Committed & Pushed Locally]:::cmd
    end

    %% Days 11–14: Deeper Git understanding
    subgraph Days11_14[Days 11–14: Full Git Workflow Understanding]
        J[Learned Step-by-Step Git Process<br/>(Missing steps = failure)]:::cmd
        K[Practiced Repeated Terminal Workflow]:::cmd
    end

    %% Flow of Learning
    A --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
    J --> K
end
```