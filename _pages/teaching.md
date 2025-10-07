---
permalink: /teaching/
title: "Teaching"
author_profile: true
noindex: False
redirect_from:
  - /teaching
  - /teaching.html
customjs:
  - "/assets/js/accordian.js"
---

I find great joy in teaching astronomy and physics, from introductory undergraduate courses to advanced
topics in astrophysics and cosmology. My approach is grounded in curiosity, accessibility,
and empowering students to think like scientists — not just to know facts, but to understand
how we come to know them. On this page, you can find some information about courses that I've taught or assisted in
teaching as well as classroom resources I've built and demos that you can use in your own classroom.

## Teaching Philosophy

My teaching is built on three principles that guide how I help students learn physics and astronomy:

1. Building **Intuitive Students**: True understanding in physics comes not from memorizing formulas, but from
   being able to explain them.
   I emphasize reasoning, dimensional analysis, and physical intuition so that students learn to think like
   scientists — curious, critical, and grounded in understanding rather than rote performance.


2. Building **Collaborative Students**:
   Science advances through community, not isolation. In my classrooms, collaboration replaces
   competition — students learn from one another, share responsibility for collective understanding, and see
   mistakes as opportunities for insight.


3. Building **Capable Students**:
   Real science is messy, uncertain, and full of discovery. I help students develop the confidence and skills
   to navigate that reality — from computational fluency to data literacy — so they can bridge the gap between
   textbook physics and the practice of doing science.

You can read my **full statement of teaching philosophy** 
[here](https://docs.google.com/document/d/1Ze1iYOsBw1hqgj-Hql_-Tw0Icnqa-7m_bbjBtf6gQh0/edit?usp=sharing)!

---

## Courses Taught

### Graduate Student Instructor – UC Berkeley
- **ASTRON 7A: Introduction to Astrophysics (Fall 2025)**  
  Led weekly discussion sections, guided inquiry-based problem solving, and developed interactive demonstrations.
  Served as guest lecturer and assisted with course logistics and grading.

### Teaching Interests
I enjoy teaching a broad range of topics across physics and astronomy, and I’m particularly excited about developing and teaching:
- **Astrophysical Dynamics and Cosmology**
- **Open Questions in Astrophysics** (seminar format)
- **Scientific Philosophy for Astronomers**
- **Open-Source Software in Astronomy**

---

## Classroom Activities / Resources

In the course of my teaching duties and outreach activities, I've developed a number of classroom resources and
demos that you can use in your own teaching. I've provided a repository of these materials below for easy access. If
you choose to use one or many of these teaching resources, please simply credit me as the original author.

{% include base_path %}

<div class="publications-list">
  {% for post in site.teaching reversed %}
    {% include archive-single.html %}
  {% endfor %}


_Last updated: {{ site.time | date: "%B %Y" }}_
