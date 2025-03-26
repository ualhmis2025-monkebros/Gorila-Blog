---
layout: page
title: 📩 Contacto
permalink: /about/
---

<style>
  h1 {
    font-size: 24px; /* Tamaño más pequeño para "Contacto" */
  }
  
  textarea {
    width: 100%; /* Ocupar todo el ancho disponible */
    height: 150px; /* Ajuste de altura para que se vea mejor */
    resize: vertical; /* Permitir solo redimensionamiento vertical */
  }
  
  .intro-text {
    font-style: italic;
    color: #555;
    margin-bottom: 10px;
  }
</style>

¡Buenas! Si tienes alguna pregunta o sugerencia, no dudes en enviarnos un mensaje. :)

<form action="https://formspree.io/f/xzzevoyb" method="POST">
  <label for="email">Tu correo electrónico:</label>
  <input type="email" id="email" name="email" required>
  
  <br><br>

  <label for="message">El mensaje que nos quieres comunicar:</label>
  <br>
  <textarea id="message" name="message" required></textarea>
  
  <br><br>

  <button type="submit">Send</button>
</form>