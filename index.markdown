---
layout: default
title: Como crear un blog utilizando jekyll
---

# Como crear un blog utilizando jekyll

Bienvenidos a nuestro blog, un espacio donde compartimos conocimientos sobre desarrollo web utilizando jekyll para la asignatura de "Herramientas y Metodologías de Ingeniería de Software".

---

## 📌 Posts más recientes

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
🗓 *Publicado el* {{ post.date | date: "%d de %B, %Y" }}  
{{ post.excerpt }}  
[Leer más...]({{ post.url }})
{% endfor %}

---

## 👥 Miembros del Equipo

- [Francisco Siles Berenguel](/miembros/juan/)
- [Manuel Quinta Sánchez](/miembros/maria/)

---

## 📩 Contacto

[Ir a la página de contacto](/contacto/)


