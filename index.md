---
layout: default
title: Ondrej Bloguje
image: /static/content/home.jpg
---

Chci se podelit o sve zazitky a zkusenosti, hlavne z cest. Vlastne o vsem, co delam ve svem volnem case. Vysledkem je tento blog. Doufam, ze se bude cist hezky a nektere veci se Vam budou hodit.

Muzete me najit na [Facebooku](https://facebook.com/sikaondrej2), [Instagramu](https://instagram.com/ondrejsika) a [Flickeru](https://www.flickr.com/photos/ondrejsika/).

---

<p>
{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.title }}</a>, {{ post.date | date: "%d. %m. %Y" }}<br>
{% endfor %}
</p>

