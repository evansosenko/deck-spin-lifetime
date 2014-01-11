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
<p>
  <a href='http://www.w3.org/html/logo/'>
    <img alt='HTML5 Powered with CSS3 / Styling, and Semantics' height='64' src='{% asset_path html5-badge-h-css3-semantics.png %}' title='HTML5 Powered with CSS3 / Styling, and Semantics' width='165'>
  </a>
</p>
{% if site.social %}
  {% capture social_buttons %}{% include social-buttons.html %}{% endcapture %}
  {{ social_buttons | strip_newlines }}
{% endif %}

{% endslide %}
