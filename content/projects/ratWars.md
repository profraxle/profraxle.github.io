---
date: '2025-10-06T00:41:33+01:00'
draft: false
title: 'RAT WARS'
hideMeta: true

weight: 3

summary: |
    Horde shooter with dynamic music from HEALTH.

    Gain score to progress the music, shoot on beat to hear the drums, and don't miss shots to unlock vocals!

    <br>

    Created for the Audio Programming module at Abertay University

tags: ["C++", "WWise", "Unreal Engine", "Enemy AI", "Blueprint"]

params:
    cover:
        image: "/img/ratWars/cover.png"
        alt: "RAT WARS horde shooter cover image"
        relative: true
        hidden: false
        hiddenInList: false
        hiddenInSingle: false

---

A horde-shooter FPS where scoring points advances the soundtrack in real time.

Built solo for the Audio Programming module at Abertay University, RAT WARS takes the song "HATEFUL" by HEALTH and drives it dynamically through an arena shooter against relentless rats — implemented in WWise.

On this project I implemented:

- **Horizontal and vertical dynamic music** — gaining score progresses the song horizontally through its sections, while firing the gun triggers the drum layer vertically, live over the current section
- **Score-multiplier-driven mixing** — building a higher multiplier by avoiding missed shots gradually raises the volume of the vocal track, tying the intensity of the mix directly to how well the player is doing

{{< carousel >}}
/img/ratWars/1.png
/img/ratWars/2.png
/img/ratWars/3.png
{{< /carousel >}}
