---
layout: default
title: Inicio
lang: es
ref: home
---

# ¡Hola, soy Carlos!

Bienvenido/a a mi portafolio profesional.

[Ver mi CV](/assets\CV_es.pdf) | [LinkedIn](https://www.linkedin.com/in/carlos-enrique-nosa-guzman-069258300/)

## Últimas publicaciones del blog

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%d/%m/%Y" }})
{% endfor %}