+++
title = "Projects"
description = ""
template = "pages.html"
+++

{% projects(path="projects.toml", format="toml") %}
<!-- Project entries are configured in projects.toml. -->
{% end %}
