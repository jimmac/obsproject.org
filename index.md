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

FIXME: stencil logos

# Extend 

FIXME: Plugins and other resouces.
