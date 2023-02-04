---
layout: single
title: "Django template"
categories: django
tag: template
---



# Django template contents

#### base.html



```
{% raw %}{% block contents %}
-------others_input----------
{% endblock %}{% endraw %}
```

#### others.html

```
{% raw %}{% extends "base.html" %}{% endraw %}


{% raw %}{% block contents %}
--------self----------
{% endblock %}{% endraw %}
```

#### common (head+footer) make base.html
