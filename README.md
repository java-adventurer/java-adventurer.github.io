# java-adventurer.github.io
Capturing journey to learn more technologies and techniques

{% for post in site.posts %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://java-adventurer.github.com{{ post.url }}#disqus_thread"></a></small></p>            
{% endfor %}
