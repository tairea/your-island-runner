---
starIndex: 4
missionIndex: 3
starTitle: Scripting Essentials
title: Checkpoint Spawns
learningObjective: Script spawn points that save player progress
estimatedDuration: "25 minutes"
previousMission: "MISSION_4_2"
nextMission: "MISSION_4_4"
keywords:
  - checkpoints
  - respawn
  - spawn location
  - game progress
  - leaderstats
  - debounce
---

# Mission 4.3: Checkpoint Spawns

**Learning Objective**: Script spawn points that save player progress

## Summary
Build a checkpoint system that lets players save their progress! When players touch a checkpoint, it becomes their new spawn point. This is essential for any platformer or runner game - nobody wants to restart from the beginning every time they make a mistake.

## Key Concepts
- SpawnLocation objects control where players respawn
- Checkpoints save progress by changing player spawn points
- Debounce prevents code from running too many times too fast
- Player data can be stored and accessed using leaderstats
- Visual feedback confirms checkpoint activation

## Prerequisites
- Completion of Mission 4.2 (Touched Events)
- Understanding of Touched events and the hit parameter
- Ability to detect players and humanoids
