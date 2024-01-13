<ul>
  {% assign sorted_posts = site.posts | sort: 'priority' %}
  {% for post in sorted_posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
