---
layout: page
title: Work
permalink: /work/
---

# Coming Soon

Where posts categorized as projects will go.
<div>
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