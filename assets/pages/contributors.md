---
title: Contributors
permalink: /contributors/
include_nav: true
---


Every post in this blog has an edit link that lets you edit the blog post directly in the browser and automatically sends me a pull request.

Or [visit the repository]({{site.github.repository_url}}) and send me a pull request the old fashioned way.


{% if site.github.contributors.size > 0 %}
The following people have made content suggestions or fixes to this blog: 
<ul class="contributor-list">
{% for contributor in site.github.contributors %}
  <li>
    <img src="{{ contributor.avatar_url }}" /> <a href="{{ contributor.html_url }}">{{ contributor.login }}</a>
  </li>
</ul>
{% endfor %}
{% endif %}
