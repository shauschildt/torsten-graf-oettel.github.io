---
layout: feature
title: Comprehensive API Interfacing
identifier: api
description: Use our fully API-based infrastructure to easily interface with external systems and accommodate complex two-way interactions.
icon: /assets/img/icons/plug-solid.svg
image: /assets/img/features/api.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Our platform doesn't merely offer an API as an afterthought - the entire system is API-based, meaning that any available interactions can also be performed by external systems. Whether you'd like to push titles or assets into the system, synchronize user data with your own CRM system, or even manage your own interface for all of the system's processes - our platform can accommodate you. Once we've identified your potential needs, a documentation of our API is available to get you started. But we can also make things work the other way round: If you'd like us to speak to your system's interface in its own language, building a custom process is also no problem for us. We will assist you in finding the best way to integrate with your existing infrastructure."

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
