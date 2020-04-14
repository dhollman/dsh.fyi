---
title: "C++ Proposals"
layout: archive
permalink: /cpp-proposals/
author_profile: true
---

An incomplete list of the C++ standard proposals I've been involved in. More complete list coming soon.

---

{% for proposal in site.cpp_proposals reversed %}
  {% include cpp-proposal-single.html type="cpp_proposal" %}
{% endfor %}