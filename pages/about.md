---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I love to tinker with data, solve constrained systems of equation and implement algorithms and heuristics (mostly) geared towards optimization purposes. <br>
Having worked in the manufacturing industry, I enjoy getting my hands dirty in the shop-floor as well, where I can implement tangible improvements through optimization.<br>
Also I absolutely love composing music! 🎸🎶

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Packages and Frameworks" source=site.data.packages-frameworks %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
