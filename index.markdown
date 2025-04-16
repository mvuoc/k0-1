---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Presentacion
---

# Bienvenido
Bienvenido a mi sitio web personal.

---
## Sobre mí
Me encanta programar

- **Lenguajes favoritos:** c++, javascript
- **Intereses** web e IA

---
{% for post in site.posts %}
### [{{ post.title }}]({{ post.urll }}})
**Publicado:** {{ post.date | date: "%d/%m/%Y" }}
{{ post.excerpt }}
[Leer más]({{ post.url }})
---
{% endfor %}
---

_Gracias por visitar mi página_
