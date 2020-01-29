---
layout: feature
title: Detailed Analytics
identifier: analytics
description: Real-time, actionable analytics tracking to provide comprehensive insights into retentions of any marketing activity.
icon: /assets/img/icons/chart-bar-solid.svg
image: /assets/img/features/analytics.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Client activity is captured in real time using metrics which can be reviewed for any time range directly in the platform. Review our one-stop dashboards for a glance at overall activity and the most viewed titles and videos, or dive into deep links to any object's dedicated analytics page in order to review activity more specifically - e.g. which titles a specific user viewed or who watched the most minutes of a specific screener. Excel exports provide deeper insights, down to individual view traces, for further offline analysis and processing."

subtitle: Automated weekly email reports
subimage: /assets/img/features/details/analytics-screen.png
subtext: "Sign up for the platform's analytics reports for a weekly email summarizing key activity, including week-on-week trends. For a more specific view of activity made by clients who are allocated to a specific sales agent, a separate email report is available, as well as an optional spreadsheet attachment of video views segmenting clients by responsible sales agent."
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
          <a href="{{ page.subimage }}" class="view">
            <img src="{{ page.subimage }}" class="border" alt="{{ page.title }}">  
          </a>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>{{ page.subtitle }}</h3>
            <p>{{ page.subtext }}</p>
        </div>
    </div>
</div>
