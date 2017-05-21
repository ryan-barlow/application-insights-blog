<ul class="posts">
	{% for post in site.posts %}
	<li>
		<span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
		<p>{{ post.content | truncatewords:50 | strip_html }}</p>
	</li>
	{% endfor %}
</ul>
