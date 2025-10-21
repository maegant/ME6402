---
title: Python Notebooks
layout: page
permalink: code
---

# Python Notebooks

Below is a list of hosted Jupyter notebooks that I've written to accompany the course:

<ul>
  {% for notebook in site.notebooks %}
    <li>
      <a href="{{ site.baseurl }}{{ notebook.url }}">{{ notebook.title }}</a>
    </li>
  {% endfor %}
</ul>

---