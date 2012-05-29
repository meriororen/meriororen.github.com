---
layout: page
title: ┻━┻ ︵ヽ(`Д´)ﾉ︵ ┻━┻
tagline: Supporting tagline
---
{% include JB/setup %}
<div class="row">
	<div class="span4">
		<h2>recent posts</h2>
		<ul>
			{% for post in site.posts %}
				<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
			{% endfor %}
		</ul>
	</div>
	<div class="span4">
		<h2>recent posts</h2>
		<ul >
			{% for post in site.posts %}
				<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
			{% endfor %}
		</ul>
	</div>
</div>



