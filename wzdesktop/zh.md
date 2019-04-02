# 丸子汤

新的图片在最上面，老规矩，右键另存即可，其他尺寸自己裁剪吧。5K屏虽然不足，但也足够清楚。


{% assign image_files = site.static_files | where: "desktop", true %}
{% for myimage in image_files %}
<img src="{{ myimage.path }}" width="760px">
<br>
{% endfor %}

