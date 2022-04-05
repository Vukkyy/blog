## Stuff you can read right now
{% for post in site.posts %}
<p style="margin:0;"><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_long_string: "ordinal", "US" }}</p>
{% endfor %}
