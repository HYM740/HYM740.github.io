# 主页

这些文章都托管在 Github Page 上。

不是很想折腾建站那些事，所以暂时就先放在这里了

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url }})

{% endfor %}
