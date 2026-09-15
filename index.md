Hi my name is Elhadj and this is my blog!


# My posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
@ebbetsfiels
Comment
