## Stuff you can read right now
{% for post in site.posts %}
<p><a href="{{ post.url }}">{{ post.title }}</a> {{ page.date | date: "%-d %B %Y" }}</p>
{% endfor %}
