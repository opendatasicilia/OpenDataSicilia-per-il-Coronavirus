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
