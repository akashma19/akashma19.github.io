---

layout: techness
title: Welcome to techness

---


## About me
 From ๐ฎ๐ณ ,  ๐ Waterloo, canada ๐ , โค๏ธ to travel ๐ซ, Play Table Tennis ๐

--- 

Hi ๐๐ปโโ๏ธ, My name is Aakash Achankutty, an aspirante cloud enginner. I very much attracted towards cuting-edge technologies and always exploring new techโก๏ธ. I have 3+ years of experince in IT industry.


---


## Tech Blogs

{% for post in site.category %}

{% if site.catg[0] == "tech blog" %}

<div>

      โญ๏ธ <a href="{{ post.url }}">{{ post.title }}</a>
  </div>
    
  {% endfor %}





## Projects


{% for catg in site.category %}

{% if site.catg[0] == "projects" %}

<div>

      โญ๏ธ <a href="{{ post.url }}">{{ post.title }}</a>
  </div>
    
  {% endfor %}


  

  ---

  