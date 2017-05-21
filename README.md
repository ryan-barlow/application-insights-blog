<ul class="posts">
	{% for post in site.posts %}
	<li>
		<span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
		<p>{{ post.content | truncatewords:150 }}</p>
		<a href="{{ post.url }}" title="{{ post.title }}">Read the full post</a>
	</li>
	{% endfor %}
</ul>
