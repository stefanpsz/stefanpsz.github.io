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

<div>
<p><h3>Peer-reviewed journal publications</h3></p>
<ol>
{% for post in site.publications-journal reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>
</div>

<div>
<p><h3>Conference publications</h3></p>
<ol>
{% for post in site.publications-conference reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>
</div>

<div>
<p><h3>Conference abstracts</h3></p>
<ol>
{% for post in site.publications-abstract reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>
</div>

<div>
<p><h3>Thesis</h3></p>
<ol>
{% for post in site.publications-thesis reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>
</div>

<div>
<p><h3>Other</h3></p>
<ol>
{% for post in site.publications-other reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}
</ol>
</div>

