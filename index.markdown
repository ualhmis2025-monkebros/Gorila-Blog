---
layout: default
title: "Cómo crear un blog utilizando Jekyll"
---

# Cómo crear un blog utilizando Jekyll
 <img src="https://github.com/ualhmis2025-monkebros/Monke-Blog/blob/paco/Img/1708339_18a55.gif" alt="gorila gracioso" style="width: 50px; height: 50px; border-radius: 50%; object-fit: cover; display: block; margin: 0 auto;"> <br>
Bienvenidos a nuestro blog, un espacio donde compartimos conocimientos sobre desarrollo web utilizando Jekyll para la asignatura de "Herramientas y Metodologías de Ingeniería de Software".

---

## 📌 Posts más recientes

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
🗓 *Publicado el* {{ post.date | date: "%d de %B, %Y" }}  
{{ post.excerpt }}  
[Leer más...]({{ post.url }})
{% unless forloop.last %}<hr style="border: none; height: 0.5px; background-color: #ccc; margin: 15px 0;">{% endunless %}
{% endfor %}

## 👥 Miembros del Equipo

- [Francisco Siles Berenguel](/miembros/francisco/)
- [Manuel Quinta Sánchez](/miembros/manuel/)

---

## 📩 Contacto

[Ir a la página de contacto](/contacto/)
