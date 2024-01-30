---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in the LTl at the University of Cambridge. My research focuses on natural language processing. I am particularly interested in parameter efficient tuning methods and transfer learning. I contribute to the [AdapterHub](https://adapterhub.ml/), a well-established framework for easily adding and training new parameters within transfer-based language models, and to research projects related to adapters.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>