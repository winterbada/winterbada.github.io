---
layout: single
title: "Django template"
---



# Django template contents

#### base.html

```
{% block contents %}
-------others_input----------
{% endblock %}
```

#### others.html

```
{% extends "base.html" %}


{% block contents %}
--------self----------
{% endblock %}
```

#### common (head+footer) make base.html
