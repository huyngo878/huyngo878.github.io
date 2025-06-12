---
title: Devlog 1.0 Foundation of my game
date: 2025-6-12 12:00:00 +/-TTTT
categories: [Devlog]
tags: [GameDev, IndieDev, Unity, Devlog]    # TAG names should always be lowercase
---

---
## Overview
Welcome to the first devlog for my upcoming game **Stratacore**! This is a Top Down 2D MMO that I’m building solo using Unity. This log will cover the early development milestones, the decisions I’ve made, and the challenges faced so far!
---


---

## Core Progress
- 1.5 month into development
### What’s Done

#### Animation System
- Fully functional **4-directional character animations**.
- **Weapon-specific animation sets**.
- Smooth **state-driven transitions** including Idle, Run, Shoot, and Death.

#### Multiplayer Foundation
- Real-time **position synchronization** across clients.
- **Shooting events**, **health updates**, and **weapon states** broadcasted efficiently.
- Implemented **hit detection and damage processing** in multiplayer context.

#### Asset & Code Organization
- Modular **weapon system** using `ItemData` ScriptableObjects.

#### Key Gameplay Features
- **Character Control**: Smooth 4-directional movement tied to animation system.
- **Combat System**: Mouse-aimed shooting with real-time **weapon switching**.
- **Multiplayer**: Functional networking layer for syncing movement, combat, and state.
- **Health System**: Full cycle from damage to healing, death, and respawn.
- **UI Management**: Inventory and player profile interfaces (Still Under Development).
- **Camera**: Cinemachine-powered smooth following camera with custom tuning.
- **Audio**: Integrated shooting sounds.

---


## Challenges till this point
- Figuring out the best multiplayer solution
- Syncing Players together
- Making it server authoritive
- Smoothing out character movements and make it very crisp
- Creating Graphics
- Creating the database and linking them together with the game
- Adding security measures early
- Finding the best way to make items in game and the most efficient
- and many more...


## Lessons Learned

- Small steps really add up even tiny updates make a big difference when you're consistent.  
- Having a clear game plan helps a ton it keeps things on track and makes the end goal feel more achievable.  
- It's okay to pause and brainstorm... sometimes the best ideas come from stepping back and thinking outside the box.

## Goals for Next Week Devlog
- Polish the Shooting animation.
- Transfer into a script base animation to require less graphics
- Add audio manager to centralize sound effects.
- Add Muzzle Flash to gun for added effects
- Add a death animation
- Create bullet sprites

## Closing Thoughts
- I'm learning so much while working on this game - one I've always dreamed of making since I was a kid! I'm super excited to keep building, improving, and sharing my progress with you. Stay tuned for the next devlog!

## Screenshots/Gif
-- First initial look =D (its very rough i know but it'll get better I promise!)
> ![Picture of player!](/assets/img/devlog/FirstScreenshot.png)
