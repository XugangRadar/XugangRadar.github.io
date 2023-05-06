---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
toc: true
---
My academic research falls into two main categories:

1) High-resolution Sparse Radar Imaging

■ Structured low-rank based sparse imaging

■ Compressive sensing based sparse imaging

■ Sparsity-driven based autofocusing

■ Advanced wide-swath sparse SAR imaging

■ Multidimensional feature-enhanced sparse SAR imaging
<br>
<br>

2) Millimeter-wave Radar and Mini-SAR Imaging

■ Automotive millimeter-wave 4D point cloud imaging

■ Automotive mini-SAR imaging

■ Airborne mini-SAR imaging

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html%}
{% endfor %}
