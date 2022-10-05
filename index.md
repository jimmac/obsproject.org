---
layout: landing.liquid
title: OBS
permalink: /
---

# Download

Download and start streaming quickly and easily on Windows, Mac or Linux. Latest version {{site.data.downloads[0].version}} released on {{site.data.downloads[0].date}}.

<div class="downloads">
{% for download in site.data.downloads %}<a class="btn download" href="{{download.url}}">{{download.platform}}</a>
{% endfor %}
See [more platforms](download).
</div>

# Features

FIXME: nice cards

# Sponsors

The OBS Project is made possible thanks to generous contributions from our sponsors and backers. Learn more about how you can [become a sponsor](contribute).

# Extend 

FIXME: Plugins and other resouces.
