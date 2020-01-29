---
layout: feature
title: Secure Screener Links
identifier: security
description: Share screeners individually or to multiple users via secure, time or view restricted branded email links to engage closer with your clients.
icon: /assets/img/icons/lock-solid.svg
image: /assets/img/features/security.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Targeted screening links can be sent to anyone, whether they're already a user of your client platform or not. Trigger a screening recommendation from a single title immediately or compile a package first, then simply define the recipient(s) and key validity parameters such as an expiry date, login/registration requirement and, optionally, the maximum number of views. Each recipient will get their own private screening link accessible immediately through the email, or at any time in their logged-in client dashboard."

subtitle: Selections and Screening Rooms
subimage: /assets/img/features/details/security-screening_link.png
subtext: "In addition to screening recommendations, larger content packages - especially if they are liable to change over time - can be deposited as selections in each client's dashboard. Alternatively, the same goes for individual videos, which can also be showcased as straight-up playlists in customizable screening rooms."
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
            <img src="{{ page.subimage }}" alt="{{ page.title }}">  
          </a>
          {% endif %}
        </div>
    </div>
</div>
