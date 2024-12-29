---
layout: home
title: Welcome to My Blog!
permalink: /
---

Hello, and welcome to my blog. Here, I share insights, and experiences related to:

- **Programming and Development**
- **Computer Networks and Protocols**
- **Deep Learning**
- **Hobbies and Interests** like hiking, table tennis, and video games.

## Latest Posts
Below, you'll find my most recent posts. Click on the title to read more!
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About Me
My name is **Akhil Chuliyat Jose**, and I'm a Master's student in International Software Systems Science at the University of Bamberg. I have experience in software development, mobile application, and exploring the fascinating world of **AI and software quality management**.

Feel free to explore, and thank you for visiting!

---

### Contact Me
Have questions or want to connect? Reach out via:
- akhiljose1999@gmail.com
- [GitHub](https://github.com/akhilcjose)
- [LinkedIn](https://www.linkedin.com/in/akhil-chuliyat-jose-701014195/)

---
{% if paginator.previous_page %}
[Previous]({{ paginator.previous_page_path }})
{% endif %}

{% if paginator.next_page %}
[Next]({{ paginator.next_page_path }})
{% endif %}
