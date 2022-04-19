---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

I do not update this page with preprints, but in most cases you can find them looking at <u><a href="https://arxiv.org/search/cs?searchtype=author&query=Zappella%2C+G"> my Arxiv profile</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
