---
layout: page
title: ヽ(`Д´)ﾉ︵ ┻━┻　オッラアア！
tagline: Supporting tagline
---
{% include JB/setup %}
<div class="span7">
		<h2>Latest posts</h2>
		<hr/>
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
<div class="span4">
		<h2>About Me <a href="#">&raquo;</a></h2>
		<hr/>
		<p>I am a software engineer. Just graduated from university. I work and live in Tokyo. And I am Indonesian.</p>
		<span><a href="http://twitter.com/isaansh">Twitter</a> | <a href="http://facebook.com/spinwheel">Facebook</a> | <a href="mailto:meriororen@gmail.com">Google</a></span>
</div>


