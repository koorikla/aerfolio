---
title: Photos Sample
subtitle: Creating a Gallery
date: 2023-10-16
tags: ["example", "photo", "360photo"]
---

{{< panorama-container >}}
    {{< panorama id="pano1" img="aerfolio/img/photo2.jpg" >}}
    {{< panorama id="pano2" img="aerfolio/img/photo2.jpg" >}}
    {{< panorama id="pano2" img="aerfolio/img/photo2.jpg" >}}
    {{< panorama id="pano2" img="aerfolio/img/photo2.jpg" >}}  
{{< /panorama-container >}}


{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="aerfolio/img/hexagon.jpg" >}}
  {{< figure thumb="-thumb" link="aerfolio/img/sphere.jpg" caption="Sphere" >}}
  {{< figure thumb="" link="aerfolio/img/photo2.jpg" caption="Triangle" alt="This is a long comment about a triangle" >}}
{{< /gallery >}}

