---
permalink: /sls/
title: "Physics and Astronomy Student Lecture Series"
author_profile: false
redirect_from: 
  - /sls.html
customjs:
  - "/assets/js/accordian.js"
---

<style>
@import url('https://pro.fontawesome.com/releases/v6.0.0-beta1/css/all.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

ul{
  width: min(100%, 60rem);
  overflow: hidden;
  margin-inline: auto;
  padding-inline: clamp(1rem, 5vw, 4rem);
  list-style: none;
  perspective: 1000px;
  display: grid;
  row-gap: 0.5rem;
}
ul li.card{
  position: relative;
  padding-block: 1.5rem;
  padding-inline: 2rem;
  background-color: var(--bg-color);
  background-image: linear-gradient(to right, rgb(0 0 0 / .15), transparent);
  transform-style: preserve-3d;
  color: var(--color);
  
  display: grid;
  grid-template: 'icon' 'title' 'content';
  row-gap: 0.5rem;
  column-gap: 2rem;
}
ul li.card::before, ul li.card::after {
  --side-rotate: 60deg;
  content: "";
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
  transform-origin: calc(50% - (50% * var(--ry))) 50%  ;
  transform: rotateY(calc(var(--side-rotate) * var(--ry)));
  background-color: inherit;
  background-image: linear-gradient(calc(90deg * var(--ry)), rgb(0 0 0 / .25), rgb(0 0 0 / .5));  
}
ul li.card::before {--ry: -1; right: 100% }
ul li.card::after {--ry: 1; left: 100% }

ul li.card .icon {
  grid-area: icon;
  display: grid;
  place-items: center;
}
ul li.card .icon i {
  font-size: 2rem;
}
ul li.card .title{
  grid-area: title;
  font-size: 1.25rem;
  font-weight: 700;
  text-align: center;
}
ul li.card .content{
  grid-area: content;
}

@media (min-width: 30rem){
  ul li.card {
    grid-template: 'icon title' 'icon content';
    text-align: left;
  }
  ul li.card .title { text-align: left }
}
</style>

<div class="row" style="column-count: 2;max-height: 1000px; break-inside: avoid">
<div class="column" style="width:80%">
The University of Utah Department of Physics and Astronomy hosts a student lectureship program, the Student Lecture Series (SLS), 
with the intention of allowing students at all levels to practice their
scientific communication skills and teaching skills.
</div>
<div class="column" style="width:20%">
    <h2><u>Submit a Proposal</u></h2>
</div>
</div>

# Talk Schedule

The SLS is hosted on alternate Tuesday nights from 4:00pm to 5:00pm. You can find the selected lecturers and their proposed
talks in the calendar below.

The SLS committee meets once monthly to select the speakers for the month following the current one. Speakers are generally given at least 1 month notice before their speaking date.

<iframe src="https://calendar.google.com/calendar/embed?src=c_5bcefeecf034030f62660e05b25be644fdc40f5cd003453944074dc9c8e2f689%40group.calendar.google.com&ctz=America%2FDenver" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>


# About The Student Lecture Series

The SLS is committed to providing opportunities for students at all stages of their education to practice scientific communication and pedagogy
through instruction. SLS lectures are held every other week throughout the fall and spring semesters and are intended to be accessible 
to an general undergraduate audience. 

## Our Commitments
<ul>
  <li class="card" style="--color:#ececec; --bg-color:#E98B43">
    <div class="icon"><i class="fa-solid fa-house"></i></div>
    <div class="title">Engaged Pedagogy</div>
    <div class="content">The SLS seeks to highlight students who place an emphasis on engaged, innovative, and effective pedagogical methods.</div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#C23D2A">
    <div class="icon"><i class="fa-solid fa-gear"></i></div>
    <div class="title">Educational Value</div>
    <div class="content">SLS Lectures are selected particularly to highlight topics and ideas which are applicable, interesting, and engaging for students. We seek to present
lectures on topics which extend and improve the core curriculum of offered course work.</div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#842C2A">
    <div class="icon"><i class="fa-solid fa-magnifying-glass"></i></div>
    <div class="title">Learning First Culture</div>
    <div class="content">SLS is committed to promoting a culture of curiosity and collaboration within the P&A community. Student instructors are not experts in
    those topics which they teach and we therefore encourage SLS lectures to be a space to acknowledge limitations in our knowledge, to foster discussion, and
    to encourage students to explore without fear of judgement for imperfect execution.
</div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#022F46">
    <div class="icon"><i class="fa-solid fa-chart-column"></i></div>
    <div class="title">Encouraging Student Engagement</div>
    <div class="content">SLS seeks to provide an opportunity for undergraduate and graduate students to better mingle both between one another and with faculty.</div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#032437">
    <div class="icon"><i class="fa-solid fa-circle-star"></i></div>
    <div class="title">Reinforcing A Shared Love for Physics</div>
    <div class="content">Being a student can be hard and stressful. SLS aims to provide students with a space to enjoy learning and thinking about physics outside of the
stressors of actual course work.</div>
  </li>
</ul>
<br>
<br>

