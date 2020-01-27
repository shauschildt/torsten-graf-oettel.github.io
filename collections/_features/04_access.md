---
layout: feature
title: Granular Access Control
identifier: access
description: Users, depending on their permissions, can view selected titles and marketing assets, instantly preview, and download. 
icon: /assets/img/icons/user-lock-solid.svg
image: /assets/img/features/access.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Each object in our platform comes with a dedicated set of access settings, giving you full transparency and keeping you in control of which user is currently receiving which degree of access, be it internal or external users. In addition, titles and/or assets can be grouped in order to give specific clients increased access - for instance in order to keep global access restricted and provide download access only to confirmed licensees."

subtitle_1: Access, permissions and scheduling
subimage_1: /assets/img/features/details/access-schedule.png
subtext_1: "General access settings range incrementally from Private (high-level admins only) to Public (public visitors of the client site). For assets, an additional, separate download permission determines whether or not client users (or even visitors) may download the source file. Each parameter can be scheduled to change at a given point in the future, e.g. to coincide with launch dates or license expiries."

subtitle_2: Group-based access and divisions
subimage_2: /assets/img/features/details/access-groups.png
subtext_2: "While global access parameters can serve to keep titles and assets as restricted as needed, privileged access can easily be granted to selected clients simply by grouping both the titles/assets and users while defining increased group-wide access. Even your company's internal divisions can be separated through a dedicated access parameter and allocation of internal users to the appropriate unit."
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
          <a href="{{ page.subimage_1 }}" class="view">
            <img src="{{ page.subimage_1 }}" alt="{{ page.title }}">  
          </a>
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
          <a href="{{ page.subimage_2 }}" class="view">
            <img src="{{ page.subimage_2 }}" class="border" alt="{{ page.title }}">
          </a>
        </div>
    </div>
</div>
