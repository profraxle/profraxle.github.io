---
date: '2025-10-06T00:15:09+01:00'

params:
    cover:
        image: "/img/FAround/cover.png"
        alt: "F Around Cover Image"
        relative: true
        hidden: false
        hiddenInList: false
        hiddenInSingle: false

tags: ["C++", "Unreal Engine", "Blueprint", "Networking", "Nintendo DS"]

draft: false
title: 'F!#&CK AROUND AND FIND (your way) OUT'
weight: 6

hideMeta: true
showTags: true
summary: |
  Created for AGDS Spring Jam 2025 (48 hours, team of 2)
  <br>

  Role: Network / Gameplay Programmer, Designer

  <br>
  Asymmetric co-op game where a maze runner and a controller feed information back and forth to reach the exit! Playable across two PCs, or a PC and a Nintendo DS.

hideSummary: false
---

F!#&CK AROUND AND FIND (your way) OUT is an asymmetric co-op game where a maze runner and a controller feed information back and forth to reach the exit. Codes and clues are relayed to the "guy in the chair", who by process of elimination opens doors to help the runner reach the goal — or inadvertently triggers deadly traps.

The game can be played fully on two PCs, or with one player on PC and the other running the Nintendo DS version.

{{< carousel >}}
/img/FAround/1.png
/img/FAround/2.png
/img/FAround/3.png
/img/FAround/4.png
{{< /carousel >}}

Built in 48 hours for AGDS Spring Jam 2025 with a team of 2, I was the Network/Gameplay Programmer and Designer, taking on tasks such as:

- Implemented replication across two networked Unreal Engine instances, keeping the runner and controller's views of the maze in sync in real time
- Set up the Game Mode to enforce asymmetrical gameplay — each player sees and controls different information — while keeping a single, consistent game state authoritative on the server
- Designed the maze layout and the core feedback loop between runner and controller, balancing clue difficulty against time pressure

<iframe frameborder="0" src="https://itch.io/embed/3384132?dark=true" width="100%" height="190"><a href="https://fraxle.itch.io/f-around-and-find-out">F!#&amp;CK AROUND AND FIND (your way) OUT by fraxle, No1Goblin</a></iframe>
