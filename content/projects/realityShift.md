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

    Mixed Reality card game app allowing gameplay online on your real tabletop!

    <br>
    Using the Meta Quest 3, projects onto the real environment while representing players with estimated full body avatars.
params:
    cover:
        image: "/img/realityShift/2.png" # path to your image
        alt: "Reality Shift Cover Image"
        relative: true
        hidden: false
        hiddenInList: false
        hiddenInSingle: true

---
A mixed reality tabletop card game client developed for the Meta Quest 3.

Developed for my honours project at Abertay University, Reality Shift allows people to play tabletop card games together over the internet in a shared XR environment.

Integrated Meta's XR SDK to handle spatial anchoring, pass-through layer blending, and real-time environment interaction, ensuring a seamless blend between digital assets and the physical room.

Utilized Meta’s hand-tracking APIs to create intuitive, physics-based gesture controls, translating natural hand movements into stable gameplay interactions like drawing, flipping, and playing cards.

Engineered an asynchronous API integration with Scryfall to dynamically parse text-based decklists, fetch external card metadata, and stream image textures over HTTP, caching assets at runtime to prevent gameplay hitches.

{{< carousel >}}
/img/realityShift/3.png
/img/realityShift/2.png
{{< /carousel >}}