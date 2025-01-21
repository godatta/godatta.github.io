---
noteId: "c17d3ed06e9411ee895efb2747317f94"
tags: []
layout: "archive"
title: "Publications"
permalink: "/publications/"
author_profile: true

---

You can find the list of all publications on my [Google scholar](https://scholar.google.com/citations?user=hxSN-fcAAAAJ&hl=en){:target="_blank"} profile.

{% include base_path %}

{% if author.googlescholar %}
  You can find the list of all publications on my <u><a href="{{author.googlescholar}}">Google Scholar</a></u> profile.
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
