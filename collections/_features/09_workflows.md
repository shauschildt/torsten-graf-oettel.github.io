---
layout: feature
title: Complex Workflows
identifier: workflows
description: Under the hood, our workflow engine achieves complex multi-step tasks and can easily be leveraged to suit your business requirements.
icon: /assets/img/icons/cogs-solid.svg
image: /assets/img/features/workflows.jpg
header_image: "/assets/img/bg/features.jpg"

text: "All processes in the platform, from uploading an asset to sending batch download link, are handled by a powerful and flexible workflow engine. Atomizing technical processes into discrete steps with individual status reporting, this system is not only versatile for handling off-the-shelf processes, but also as a backbone to implement any custom processes you may have in mind - whether to accommodate a custom feature you have in a mind or a regular interaction with an external system. Furthermore, each workflow's status is available to review in a filterable list for immediate transparency of their status and any errors."

subtitle: 
subimage: /assets/img/features/details/workflow-flow.jpg
subtext: 
---


<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <p>{{ page.text }}</p>
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
