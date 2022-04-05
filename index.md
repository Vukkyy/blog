## Stuff you can read right now
{% for post in site.posts %}
<span><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_long_string: "ordinal", "US" }}</span>
{% endfor %}
