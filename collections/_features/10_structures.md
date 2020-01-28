---
layout: feature
title: Customizable Data Structures
identifier: structures
description: Granular contextual metadata of titles, their marketing and auxiliary assets for instant recovery and sharing. 
icon: /assets/img/icons/file-invoice-solid.svg
image: /assets/img/features/structures.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Besides the obvious key properties, our standard metadata schemas allow you to capture a deep degree of detail, such as multiple genre assignments, many-to-one associations of cast and crew, and multi-language layers. However, our architecture also allows for fully custom schemas: Whether you'd like to concentrate on just a handful of key fields or go all-out and capture expansive additional information, we can provide the best structure to capture your data optimally. Of course, you also decide which portion of each title's or asset's metadata is shared with clients and which remains purely internal. We can even provide multiple schemas for you - say, a standard schema plus several schemas matching specific vendor formats."

subtitle: 
subimage: 
subtext: 
---

<div class="row">
    <div class="col-md-12">
        <div class="service-details mb-40">
            <p>{{ page.text }}</p>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>{{ page.subtitle }}</h3>
            <p>{{ page.subtext }}</p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
          {% if page.subimage %}
          <a href="{{ page.subimage }}" class="view">
            <img src="{{ page.subimage }}" class="border" alt="{{ page.title }}">  
          </a>
          {% endif %}
        </div>
    </div>
</div>
