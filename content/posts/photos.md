---
title: Photos Sample
subtitle: Creating a Gallery
date: 2023-10-16
tags: ["example", "photo", "360photo"]
---

{{< panorama-container >}}
    {{< panorama id="pano1" img="/img/photo2.jpg" >}}
    {{< panorama id="pano2" img="/img/photo2.jpg" >}}
    {{< panorama id="pano2" img="/img/photo2.jpg" >}}
    {{< panorama id="pano2" img="/img/photo2.jpg" >}}  
{{< /panorama-container >}}


{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/img/hexagon.jpg" >}}
  {{< figure thumb="-thumb" link="/img/sphere.jpg" caption="Sphere" >}}
  {{< figure thumb="" link="/img/photo2.jpg" caption="Triangle" alt="This is a long comment about a triangle" >}}
{{< /gallery >}}

