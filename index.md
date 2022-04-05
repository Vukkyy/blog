## Stuff you can read right now
{% for post in site.posts %}
<p style="margin:0;"><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_long_string: "ordinal", "US" }}</p>
{% endfor %}<br>

## Other things
This is not my main website. You can find my main website [here](https://sus.omg.lol).

There is also an RSS feed available, which can be found [here](https://blog.sus.omg.lol/feed.xml).
