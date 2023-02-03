---
layout: single
title: "Django block contents"
---


# Django template, block_contents

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



#### common (head + footer) make base.html
