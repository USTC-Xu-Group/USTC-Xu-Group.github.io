---
title: "News"
layout: gridlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="section-card" markdown="0">
<div class="news-timeline">
{% for article in site.data.news %}
<div class="news-item">
<span class="news-date">{{ article.date }}</span>
{% if article.image %}
<img class="news-image" src="{{ article.image | relative_url }}" alt="{{ article.headline }}">
{% endif %}
<div class="news-headline">
{% if article.link %}<a href="{{ article.link }}"><strong>{{ article.headline }}</strong></a>{% else %}<strong>{{ article.headline }}</strong>{% endif %}
</div>
{% if article.content %}<p class="news-content">{{ article.content | newline_to_br }}</p>{% endif %}
</div>
{% endfor %}
</div>
</div>
