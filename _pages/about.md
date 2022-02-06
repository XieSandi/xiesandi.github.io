---
layout: page
title: Memoirs, a free minimalist Jekyll blogging theme with modern design 
permalink: /about
comments: false
---

<!-- Posts Index
================================================== -->
<div class="blog-grid-container">
    {% for post in paginator.posts %}
        {% include postbox.html %}
    {% endfor %}
</div>

<!-- Pagination
================================================== -->
<div class="bottompagination">
<span class="navigation" role="navigation">
    {% include pagination.html %}
</span>
</div>
