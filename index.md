---
home: true
---

## Stuff you can read right now
<audio autoplay loop preload="auto" src="https://litdevs.org/miiversel.mp3"></audio>
{% for post in site.posts %}
<div class="preview-box">
<h2 style="margin-bottom: 0;">{{ post.title }}</h2> {{ post.date | date_to_long_string: "ordinal", "US" }}<br>
<p>{{ post.excerpt }} <a href="{{ post.url }}">Continue reading...</a></p>
</div>
{% endfor %}

<h2 style="margin-top: 20px">Other things</h2>
This is not my main website. You can find my main website [here](https://sus.omg.lol).<br>There is also an RSS feed available, which can be found [here](https://blog.sus.omg.lol/feed.xml).<br>I also write things on [status.cafe](https://status.cafe/users/vukky).

<h2 style="margin-top: 20px">oi bukk this layout seems familiar</h2>
It's a modified version of the [modernist](https://github.com/pages-themes/modernist/) theme.

I'll make my own theme at some point, but for now I like this one.