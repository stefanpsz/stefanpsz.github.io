---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<p><h4>Peer-reviewed journal publications</h4></p>
<ol>
{% for post in site.publications-journal reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>

<p><h4>Conference publications</h4></p>
<ol>
{% for post in site.publications-conference reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>

<p><h4>Abstracts</h4></p>
<ol>
{% for post in site.publications-abstract reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>

<p><h4>Thesis</h4></p>
<ol>
{% for post in site.publications-thesis reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>