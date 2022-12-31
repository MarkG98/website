---
layout: archive
title: "Publications"
show_title: false
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h1><u>Publications</u></h1>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
<h1><u>Presentations</u></h1>

{% for post in site.presentations reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
<h1><u>Posters</u></h1>

{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Authors listed alphabetically