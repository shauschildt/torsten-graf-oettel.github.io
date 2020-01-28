---
layout: feature
title: Multi-layer Metadata
identifier: metadata
description: Maintain multiple sets of metadata per title and asset in order to manage multi-language and pitch data and even vendor-specific schemas.
icon: /assets/img/icons/layer-group-solid.svg
image: /assets/img/features/metadata.jpg
header_image: "/assets/img/bg/features.jpg"

text: "There can be many reasons for managing multiple sets of metadata: Perhaps you'd like to provide title metadata in several languages, or you'd like to be able to predefine properties in schemas requested by vendors you deal with. Our system can easily accommodate this through its layer architecture, which lets you manage multiple sets of metadata per title or asset. Even differing metadata schemas can be added on request, and you decide if and how multiple layers should be available to select or export directly in your client-facing site."

subtitle: 
subimage: /assets/img/features/details/metadata-language-layer.png
subtext: 
---

<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <p>{{ page.text }}</p>
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
