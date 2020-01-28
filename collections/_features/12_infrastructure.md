---
layout: feature
title: Auto-scaling Infrastructure
identifier: infrastructure
description: Our platform is fully cloud-based and scales to your needs, requiring no more than a web browser and and internet connection to interact with.
icon: /assets/img/icons/network-wired-solid.svg
image: /assets/img/features/infrastructure.jpg
header_image: "/assets/img/bg/features.jpg"

text: "With our cloud-based, virtualized infrastructure hosted on AWS, we can not only ensure exceptional uptime and disruption-less rolling updates, but also scale storage and processing capabilities to your needs. Whether you're a small distributor with a few dozen new titles per year or a heavyweight distributor eager to host tens of thousands of titles and assets, you get the same level of service. Our auto-scaling infrastructure ensures that even at peak times, resources are simply amped up to match whatever throughput is required."

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
