## Test page !
Hello bob...

Site baseurl: {{ site.baseurl }}

Site URL: {{ site.url }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
