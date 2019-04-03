# 美食摄影


{% assign image_files = site.static_files | where: "meishi", true %}
{% for myimage in image_files %}
<a href="{{ myimage.path }}" target="_blank"><img src="{{ myimage.path }}" max-width: 100%></a>
{% endfor %}