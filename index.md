---

layout: techness
title: Welcome to techness

---


## About me
 From 🇮🇳 ,  📍 Waterloo, canada 🍁 , ❤️ to travel 🛫, Play Table Tennis 🏓

--- 

Hi 🙋🏻‍♂️, My name is Aakash Achankutty, an aspirante cloud enginner. I very much attracted towards cuting-edge technologies and always exploring new tech⚡️. I have 3+ years of experince in IT industry.


---


## Tech Blogs

{% for post in site.category %}

{% if site.catg[0] == "tech blog" %}

<div>

      ⭐️ <a href="{{ post.url }}">{{ post.title }}</a>
  </div>
    
  {% endfor %}





## Projects


{% for catg in site.category %}

{% if site.catg[0] == "projects" %}

<div>

      ⭐️ <a href="{{ post.url }}">{{ post.title }}</a>
  </div>
    
  {% endfor %}


  

  ---

  