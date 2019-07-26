---
title: "News"
layout: textlay
excerpt: "Gurjit Kaur Lab at Delhi Technological University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
