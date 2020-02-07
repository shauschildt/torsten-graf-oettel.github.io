---
layout: service
title: Website Setup & Operation
description: Whether you opt for a white-label or a custom-designed client site - we will get your new marketing site up and running within days rather than months.
image: /assets/img/services/platform_operation.jpg
header_image: "/assets/img/bg/services.jpg"

text: "Offering you the tools you need to optimize your content sales and distribution workflows is our bread and butter. No matter if you're a small distributor shopping for a one-stop sales and marketing website, or a multinational content owner looking to consolidate teams and workflows into a shiny new interface, we are happy to determine your requirements and how our suite of tools and features might best achieve your desired outcome."

subtitle_1: White-label turnkey sites
subimage_1: /assets/img/services/details/website-white-labelled.png
subtext_1: "Our standard design features a sleek, state-of-the-art responsive look and feel, and is readily available off the shelf to be customized with key properties such as your logo, colors and custom texts. We are happy to provide an in-depth introduction and, even during the negotiation phase, can give you access to a demo system allowing you to test-drive all features. When the time has come, our project managers will keep track of deliverables and to-do's, and keep you posted on the implementation processes. Just rest easy and let us put your new platform together."

subtitle_2: A fully customized client experience
subimage_2: /assets/img/services/details/website-custom.png
subtext_2: "There is no hard border between our standard white label platform and added features or visual customization. Based on your scope and the complexity of e.g. your design, your ideas for feature modifications and add-ons, or any integrations with existing systems, we can develop entirely new components and work with your UI team directly on how they will be presented to your clients, be it as part of our standard design or within a fully custom client-facing site. Even if you're in need of a comprehensive solution and have nothing but a few visual details and some ideas to go by, we have developers and designers on hand who are experienced with our system and can put comprehensive concepts, wireframes and screen designs together. Long story short, let us consult with you in order to gauge your requirements, then we can perform as much of the process on our side as needed."
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
        <div class="s-details-img mb-30">
          {% if page.subimage_1 %}
          <a href="{{ page.subimage_1 }}" class="view">
            <img src="{{ page.subimage_1 }}" class="border" alt="{{ page.title }}">  
          </a>
          {% endif %}
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>{{ page.subtitle_1 }}</h3>
            <p>{{ page.subtext_1 }}</p>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>{{ page.subtitle_2 }}</h3>
            <p>{{ page.subtext_2 }}</p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
          {% if page.subimage_2 %}
          <a href="{{ page.subimage_2 }}" class="view">
            <img src="{{ page.subimage_2 }}" class="border" alt="{{ page.title }}">  
          </a>
          {% endif %}
        </div>
    </div>
</div>
