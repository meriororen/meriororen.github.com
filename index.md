---
layout: page
title: ヽ(`Д´)ﾉ︵ ┻━┻　オアア！
tagline: Supporting tagline
---
{% include JB/setup %}
<div class="post">
		<ul class="unstyled">
		{% for post in site.posts %}
			<li style="padding: 0.5em 1em;">
				<span>{{ post.date | date_to_string }}</span> &nbsp; // &nbsp;  
				<a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
				<span class="pull-right">
					{% for tag in post.tags %}
						<span><a class="btn btn-mini btn-info disabled" href="index.html#{{ tag }}-ref">{{ tag }}</a></span>
					{% endfor %}
				</span>
			</li>
		{% endfor %}
		</ul>
</div>



