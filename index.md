---
title: Home
permalink: /
---
<section class="hero">
  <h1>Keep your espresso machine clean, working and cozy.</h1>
  <p>Step-by-step maintenance, cleaning and troubleshooting guides for the Breville Barista Express, plus accessory guides for the Ninja Luxe Café.</p>
  <a class="btn" href="{{ '/breville-barista-express/' | relative_url }}">Start with Breville guides</a>
</section>

<h2>Browse by topic</h2>
<ul class="grid">
  <li class="card"><h3><a href="{{ '/breville-barista-express/' | relative_url }}">Breville Barista Express</a></h3><p>Cleaning, descaling and filters.</p></li>
  <li class="card"><h3><a href="{{ '/ninja-luxe-cafe/' | relative_url }}">Ninja Luxe Café</a></h3><p>Care guides and accessories.</p></li>
  <li class="card"><h3><a href="{{ '/cleaning-descaling/' | relative_url }}">Cleaning &amp; Descaling</a></h3><p>Guides that apply to most machines.</p></li>
  <li class="card"><h3><a href="{{ '/troubleshooting/' | relative_url }}">Troubleshooting</a></h3><p>Fix common problems.</p></li>
  <li class="card"><h3><a href="{{ '/accessories-parts/' | relative_url }}">Accessories &amp; Parts</a></h3><p>What to buy and what to skip.</p></li>
  <li class="card"><h3><a href="{{ '/best-picks/' | relative_url }}">Best Picks</a></h3><p>Our shortlists of useful products.</p></li>
</ul>

{% if site.posts.size > 0 %}
<h2>Latest guides</h2>
<ul class="grid">
  {% for p in site.posts limit:6 %}
  <li class="card"><h3><a href="{{ p.url | relative_url }}">{{ p.title }}</a></h3><p>{{ p.description }}</p></li>
  {% endfor %}
</ul>
{% endif %}

<p class="disclosure">Some links on this site are Amazon affiliate links. <a href="{{ '/affiliate-disclosure/' | relative_url }}">Read the full disclosure</a>.</p>
