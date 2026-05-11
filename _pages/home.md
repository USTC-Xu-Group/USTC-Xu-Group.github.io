---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<h2 class="home-hero">{{ site.groupname }}</h2>
<!--
<p class="home-hero-sub">{{ site.title }}<br>  {{ site.institution }}</p>
-->
<p class="home-hero-sub"> {{ site.institution }}</p>

<div class="chip-container" markdown="0">
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Heavy-flavour hardons</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Heavy quark production</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">CPV and CKM</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Precision@STCF</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">High-rate MPGD</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Sci-Fi Tracker</a>
</div>

Collider experimental physics studies fundamental particles and their interactions through high-energy particle collisions. 
Our research focuses on heavy-flavour and hadron physics at LHCb at LHC, including the spectroscopy, production, and CP violation of charm and beauty hadrons. 
We also contribute to detector and physics studies for the future STCF experiment, with emphasis on precision measurements and detector-calibration requirements. 
As part of the USTC detector team, we conduct R&D on high-rate micro-pattern gaseous detectors for the LHCb MUON Upgrade, in close international collaboration with Italian partners.
[Building on previous experience with scintillating-fibre (SciFi) tracking technology.]


<div class="section-card" style="margin-top: var(--space-6);">
<h4 style="margin-top: 0;">News</h4>
<div class="news-timeline">
{% for article in site.data.news limit:3 %}
<div class="news-item">
<div class="news-date">{{ article.date }}
<div class="news-headline">{{ article.headline }}
</div>
{% endfor %}
</div>
<p style="margin-top: var(--space-4);"><a href="{{ site.url }}{{ site.baseurl }}/allnews.html">See all news &rarr;</a></p>
</div>



<!--
<div class="callout callout-success" markdown="0">
<div class="callout-title"><i class="fa-solid fa-award callout-icon"></i> Nobel Prize in Physics, 1965</div>
<p>Awarded the Nobel Prize jointly with Julian Schwinger and Shin'ichiro Tomonaga for fundamental work in quantum electrodynamics, with deep-ploughing consequences for the physics of elementary particles.</p>
</div>
-->

<!--
<div class="banner-frame" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" alt="Feynman diagrams" loading="lazy">
<div class="banner-caption">Examples of Feynman diagrams. Feynman R., <em>The theory of positrons. Phys. Rev.</em> (1949)</div>
</div>
-->

<!--
### About me
I am a physicist working in the field of quantum mechanics and quantum electrodynamics.
-->


