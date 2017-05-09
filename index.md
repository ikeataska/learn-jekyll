---
layout: page
title: Home
---
 
# Vítejte!

Harry Bruce, Ph.D., je profesorem a současným děkanem Informační školy na Washingtonské univerzitě. Ve výzkumu se zajímá o informační chování, vyhledávání informací, správu osobních informací a síťová informační prostředí. Je autorem mnoha publikací zaměřujících se na informační chování a informační vědu.

## Příspěvky

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Kategorie

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

