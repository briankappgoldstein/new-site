---
layout: page
title: Work
permalink: /work/
---
<p class="lead">Here's a sample of work I've done. Each item should feature a short description of the project, a few images from the project, my role, and technologies used. There's more to come.</p>

<div class="home">
{%- if site.work.size > 0 -%}
    <ul class="post-list">
      {%- for item in site.work -%}
      <li>
        <h3>
          <a class="post-link" href="{{ item.url | relative_url }}">
            {{ item.title | escape }}
          </a>
        </h3>
          {{ item.excerpt }}
      </li>
      {%- endfor -%}
    </ul>


{%- endif -%}
</div>