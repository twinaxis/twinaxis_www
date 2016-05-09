---
layout: page
title: Members
permalink: /members/
members:
 - name: Sorakiu
   subdomain: sorakiu      
   twitter: sorakiu
   github: sorakiu
 - name: Kitla&auml;n
   subdomain: kitlaan
   github: kitlaan

---

# The Members

{% for member in page.members %}
# [{{ member.name }}](http://{{ member.subdomain }}.twinaxis.com)
<ul class="social-media-list">
  {% if member.github %}
  <li>{% include icon-github.html username=member.github  %}</li>
  {% endif %}
  {% if member.twitter %}
  <li>{% include icon-twitter.html username=member.twitter %}</li>
  {% endif %}
</ul>
{% endfor %}