---
layout: default
title: Effect of contacts on spin lifetime measurements in graphene
author: Evan Sosenko
short_url: goo.gl/rc8q83
src_url: https://github.com/razor-x/deck-spin-lifetime
ucr_url: http://www.physics.ucr.edu/
coauthors: [ Vivek Aji ]
---

<style>h2::after{content:"{{ page.short_url }}"};</style>

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
<div class="web-colophon">
  <a class="html5-badge" href="http://www.w3.org/html/logo/" title="HTML5 Powered with CSS3 / Styling, and Semantics"></a>
  {{ social_buttons | strip_newlines }}
</div>
<div class="colophon">
  <a href="http://{{ site.data.meta.site_name }}">{{ site.data.meta.site_name }}</a>
  <a class="src_url" href="{{ page.src_url }}">Source available on GitHub.</a>
</div>

{% endslide %}
