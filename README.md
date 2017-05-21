<ul class="posts">
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> - <span>{{ post.date | date_to_string }}</span>
		
		<p>
			{{ post.content | truncatewords:150 }}<br /><br />
			<a href="{{ post.url }}" title="{{ post.title }}">Read the full post</a>
		</p>
	{% endfor %}
