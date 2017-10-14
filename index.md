---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: Make music great again !
---

C'est parti pour le Code Camp ! Ce site sera là pour vous accompagner tout au long de l'aventure ;)

{% for jour in site.jours %}
<article class="card" style="cursor: pointer;" onclick="window.location='{{ jour.url |  prepend:site.baseurl }}';">
  <img src="{{ jour.img }}">
  <div>
    <h4>{{ jour.title }}</h4>
    <p>{{ jour.description }}</p>
  </div>
</article>
{% endfor %}
