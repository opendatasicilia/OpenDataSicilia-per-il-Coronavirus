## test
```
<!-- Add announcement here, including arbitrary HTML 
(https://squidfunk.github.io/mkdocs-material/setup/setting-up-the-header/#announcement-bar) -->
```

``` html
	{% block announce %}
<span style="background-color: #f50505; color: #ffffff; padding: 0px 3px; border-radius: 4px;"><b>Importante news</b>:</span> questa è una <strong><span style="color: #ff0000;">prova</span></strong> di announcement nell'header sopra il titolo, ed è posizionata dal rigo 5 a 8 del file <code> main.html </code>
	{% endblock %}
```

```
    {% block extrahead %}
      {% set title = config.site_name %}
      {% if page and page.meta and page.meta.title %}
        {% set title = title ~ " - " ~ page.meta.title %}
      {% elif page and page.title and not page.is_homepage %}
        {% set title = title ~ " - " ~ page.title %}
      {% endif %}
      <meta name="twitter:card" content="summary_large_image" />
      <meta name="twitter:title" content="{{ title }}" />
      <meta name="twitter:description" content="{{ config.site_description }}" />
      <meta name="twitter:image" content="<url>" />
    {% endblock %}
```


``` html
{% extends "base.html" %}

{% block htmltitle %}
  <title>Lorem ipsum dolor sit amet</title>
{% endblock %}
```
