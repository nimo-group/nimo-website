---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research



{% include section.html %}

## Most recent publication

{% assign sorted_citations = site.data.citations | sort: "date" | reverse %}
{% assign most_recent_citation = sorted_citations | first %}

{% include citation.html lookup=most_recent_citation.title style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
