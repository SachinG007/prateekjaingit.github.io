---
title: "Home"
layout: textlay
excerpt: "Prateek Jain -- Microsoft Research India."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
