videos here...

{% assign vids = site.static_files %}
<ul>
{% for f in vids %}
    <li><a href="{{ f. path }}" target="_blank">{{ f.basename }}</a></li>
{% endfor %}
</ul>