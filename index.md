videos here...

{% assign vids = site.static_files | where: "extname", "mp4" %}
<ul>
{% for f in vids %}
{% assign people = people_hash[1] %}
    <li><a href="{{ f. path }}" target="_blank">{{ f.basename }}</a></li>
{% endfor %}
</ul>