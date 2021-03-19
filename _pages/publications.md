---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!--<p>You can also see a <a href="/publications/network">network</a> of all my publications.</p>-->

<!--{% if author.googlescholar %}
  You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}-->

<p>Here is a network representing my work and collaborators; the color of each node specifies what it represents: <span style="color:#1722C1">co-authors</span>, <span style="color:#90d185">preprints</span>, <span style="color:#138400">publications</span> and <span style="color:#8e20c1">theses</span> (in this case co-authors are supervisors and co-supervisors).<br>
Hover and click on each node for more information, or drag them around to change the network's shape.</p>
<iframe src="/network/network.html" height="300" width="100%" style="border: none"></iframe>

<p>Here is instead a list of all my publications:</p>
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
