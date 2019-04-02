# 丸图


新的图片在最上面，老规矩，右键另存即可，其他尺寸自己裁剪吧。5K屏虽然不足，但也足够清楚。

{% assign image\_files = site.static\_files | where: "desktop", true %}
{% for myimage in image\_files %}
<img src="{{ myimage.path }}" width="760px">
<br>
{% endfor %}

