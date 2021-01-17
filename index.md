videos here...

{% assign vids = site.static_files | where: "extname", ".mp4" %}
<ul>
{% for f in vids %}
    <li><a href="/vid/{{ f. path }}" target="_blank">{{ f.basename }}</a></li>
{% endfor %}
</ul>