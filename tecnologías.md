---
layout: page
title: Tecnologías
permalink: /tecnologías/
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<div class="container">
<div class="row">
{% for doc in site.tecnologias %}
<div class="col-md-3">
{% include collection-excerpt.html %}
</div>
{% endfor %}
</div>
</div>
