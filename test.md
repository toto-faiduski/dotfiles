## Test page !
Hello bob...

Site source: {{ site.source }}

Site URL: {{ site.url }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
