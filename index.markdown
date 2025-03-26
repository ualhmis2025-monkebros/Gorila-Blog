---
layout: default
title: "Cómo crear un blog utilizando Jekyll"
---

# Cómo crear un blog utilizando Jekyll

Bienvenidos a nuestro blog, un espacio donde compartimos conocimientos sobre desarrollo web utilizando Jekyll para la asignatura de "Herramientas y Metodologías de Ingeniería de Software".

---

## 📌 Posts más recientes

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
*Publicado el* {{ post.date | date: "%d de %B, %Y" }}
{{ post.excerpt }}
[Leer más...]({{ site.baseurl }}{{ post.url }})
{% unless forloop.last %}<hr style="border: none; height: 0.5px; background-color: #ccc; margin: 15px 0;">{% endunless %}
{% endfor %}

## <img src="{{ site.baseurl }}/assets/gorilla.gif" alt="Gorila" style="width: 60px; height: 60px; display: inline; margin-left: 10px;"> Miembros del Equipo

- <a href="{{ site.baseurl }}/miembros/francisco/">Francisco Siles Berenguel</a>
- <a href="{{ site.baseurl }}/miembros/manuel/">Manuel Quinta Sánchez</a>

