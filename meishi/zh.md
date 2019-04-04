# 美食照片

{％assign image_files = site.static_files | 其中：“美诗”，真％}
{% for myimage in image_files %}
<a href="{{ myimage.path }}" target="_blank"><img src="{{ myimage.path }}" width="100%"></a>
{% endfor %}
