---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h3>List of Posts</h3>
<div class="list-group">
    {% for post in site.posts %}
        <a href="{{ post.url }}" class="list-group-item list-group-item-action">{{ post.title }}</a>
    {% endfor %}
</div>