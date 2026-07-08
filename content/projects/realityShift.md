---
date: '2025-10-06T00:41:33+01:00'
draft: false
title: 'Reality Shift'
hideMeta: true
weight: 2

tags: ["C#", "Unity", "XR", "Networking", "Meta SDKs"]

summary: |
  ### **Honours Project Artifact**
  <br>

    Mixed reality card game allowing players to sit down at your real tabletop from anywhere online.

    <br>
    Built for the Meta Quest 3, projecting cards onto the real environment while representing remote players with estimated full-body avatars.

params:
    cover:
        image: "/img/realityShift/2.png"
        alt: "Reality Shift mixed reality tabletop card game screenshot"
        relative: true
        hidden: false
        hiddenInList: false
        hiddenInSingle: true

---

A mixed reality tabletop card game client built for the Meta Quest 3.

Developed solo as my Honours Project at Abertay University over two semesters, Reality Shift lets people play tabletop card games together over the internet in a shared XR environment — as if a remote friend were sitting across the same table.

On this project I:

- Integrated Meta's XR SDK to handle spatial anchoring, pass-through layer blending, and real-time environment interaction, ensuring a seamless blend between digital cards and the physical room
- Used Meta's hand-tracking APIs to build intuitive, physics-based gesture controls, translating natural hand movements into stable gameplay interactions like drawing, flipping, and playing cards
- Engineered an asynchronous integration with the Scryfall API to dynamically parse text-based decklists, fetch card metadata, and stream image textures over HTTP — caching assets at runtime to prevent gameplay hitches when new cards were drawn

{{< youtube d5f73D9zxCQ >}}

{{< carousel >}}
/img/realityShift/3.png
/img/realityShift/2.png
{{< /carousel >}}


