---
date: '2025-10-06T00:41:33+01:00'
draft: false
title: 'Station Sentinels'
hideMeta: true
weight: 7

tags: ["C++", "Procedural Generation", "Pathfinding"]

summary: |
    Top-down shooter with procedurally generated levels.

    Built with Abertay's Game Education Framework.

    Features tile-based level generation and A* pathfinding for enemies.

params:
    cover:
        image: "/img/stationSentinels/1.png"
        alt: "Station Sentinels top-down shooter cover image"
        relative: true
        hidden: false
        hiddenInList: false
        hiddenInSingle: true
---

{{< carousel >}}
/img/stationSentinels/1.png
/img/stationSentinels/2.png
/img/stationSentinels/3.png
{{< /carousel >}}

A top-down shooter with procedurally generated levels.

Built for the Game Programming and System Architectures module at Abertay University, in a two-person team, using Abertay's Games Education Framework.

I mainly worked on:

- **Tile-based level generation** — procedurally assembling station layouts from a set of tiles each playthrough, so no two runs are identical
- **Enemy AI and A\* pathfinding** — routing enemies through the procedurally generated tile grid in real time as it changes
- **3D modelling** — creating props and environment assets for the station interior

<iframe frameborder="0" src="https://itch.io/embed/2102307?bg_color=000000&amp;fg_color=3347c3&amp;link_color=5b82fa&amp;border_color=333333" width="100%" height="167"><a href="https://fraxle.itch.io/station-sentinels">Station Sentinels by fraxle, No1Goblin</a></iframe>