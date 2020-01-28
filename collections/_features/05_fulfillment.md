---
layout: feature
title: Post-sales Asset Fulfillment
identifier: fulfillment
description: Manage any type of asset and provide title- or deal-based download access to selected clients via package downloads and high speed file transfer.
icon: /assets/img/icons/shopping-basket-solid.svg
image: /assets/img/features/fulfillment.jpg
header_image: "/assets/img/bg/features.jpg"

text: "If you'd like to use our platform beyond the sales and marketing phase, it can also take care of delivering assets to your licensees. Using our flexible access controls, you can selectively provide (timed) access to any set of assets to a specific client, who can then retrieve them in the client-site by using any of the several self-service download options including ZIP package delivery and Aspera Faspex file transfer. However, you can also take care of sending email-based download links to your clients in case you'd like to minimise their share of the effort even further."

subtitle: 
subimage: /assets/img/features/details/fulfillment-aspera_download.png
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
