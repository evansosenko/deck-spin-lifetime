---
layout: default
title: Effect of contacts on spin lifetime measurements in graphene
author: Evan Sosenko
short_url: goo.gl/rc8q83
ucr_url: http://www.physics.ucr.edu/
coauthors: [ Vivek Aji ]
---

{% slide header %}

<h1>{{ page.title }}</h1>
<ul class="authors">
  <li class="author"><a href="http://{{ site.data.meta.site_name }}">{{ page.author }}</a>
  </li>
  <li class"connector">with</li>
{% for coauthor in page.coauthors %}
  <li class="author coauthor">{{ coauthor }}</li>
{% endfor %}
</ul>
<div class="qrcode"></div>
<a class="short_url" href="https://{{ page.short_url }}">{{ page.short_url }}</a>
<a class="ucr_logo" href="{{ page.ucr_url }}"></a>

{% endslide %}{% slide %}

## Body

{% endslide %}{% slide.my-class %}

## More body

{% endslide %}{% slide footer %}

## Final slide

{% if site.social %}
  {% capture social_buttons %}{% include social-buttons.html %}{% endcapture %}
{% endif %}

<a class="ucr_logo" href="{{ page.ucr_url }}"></a>
<div class="colophon">
  <a href="http://{{ site.data.meta.site_name }}">{{ site.data.meta.site_name }}</a>
</div>
<div class="web-colophon">
  <a class="html5-badge" href="http://www.w3.org/html/logo/" title="HTML5 Powered with CSS3 / Styling, and Semantics"></a>
  {{ social_buttons | strip_newlines }}
</div>

{% endslide %}
