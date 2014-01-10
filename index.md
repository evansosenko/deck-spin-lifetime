---
layout: default
title: Effect of contacts on spin lifetime measurements in graphene
short_url: goo.gl/rc8q83
qr_code: rc8q83.qr.png
---

{% slide header %}

# {{ page.title }}

[{{ page.short_url }}](https://{{ page.short_url }})

![{{ page.short_url }}]({{ page.qr_code | asset_path }})

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
