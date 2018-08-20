---
layout: page
title: Work
permalink: /work/
---

# Coming Soon

Where posts categorized as projects will go.

{%- if site.work.size > 0 -%}
    <ul class="post-list">
      {%- for post in site.work -%}
      <li>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
          {{ post.excerpt }}
      </li>
      {%- endfor -%}
    </ul>


{%- endif -%}