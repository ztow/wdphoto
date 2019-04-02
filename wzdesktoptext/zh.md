# 丸图


新的图片在最上面，老规矩，右键另存即可，其他尺寸自己裁剪吧。5K屏虽然不足，但也足够清楚。

每张图片我都会留下一些话，详见这里：
[ https://ztow.me/archive/?tag=%E4%B8%B8%E5%AD%90%E5%A3%81%E7%BA%B8 ][1]


{% assign image\_files = site.static\_files | where: "desktop", true %}
{% for myimage in image\_files %}
<img src="{{ myimage.path }}" width="760px">
<br>
{% endfor %}

[1]:	https://ztow.me/archive/?tag=%E4%B8%B8%E5%AD%90%E5%A3%81%E7%BA%B8 "查看与这些图片有关的文章"