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

* { margin: 0; padding: 0; box-sizing: border-box }
body {
  padding: 2rem;
  font-family: 'Roboto', sans-serif;
  min-height: 100vh;
  display: grid;
  place-items: center;
}
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

The University of Utah Department of Physics and Astronomy hosts a student lectureship program, the Student Lecture Series (SLS), 
with the intention of allowing students at all levels to practice their
scientific communication skills and teaching skills.

<iframe src="https://calendar.google.com/calendar/embed?src=c_5bcefeecf034030f62660e05b25be644fdc40f5cd003453944074dc9c8e2f689%40group.calendar.google.com&ctz=America%2FDenver" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>


# About The Student Lecture Series

The SLS is committed to providing opportunities for students at all stages of their education to practice scientific communication and pedagogy
through instruction. SLS lectures are held every other week throughout the fall and spring semesters and are intended to be accessible 
to an general undergraduate audience. 

<ul>
  <li class="card" style="--color:#ececec; --bg-color:#E98B43">
    <div class="icon"><i class="fa-solid fa-house"></i></div>
    <div class="title">Lorem ipsum</div>
    <div class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis pretium euismod. Aenean elit sapien, varius quis ante sit amet, tincidunt finibus orci. Ut consectetur imperdiet quam, at ultrices mi rutrum ut. Sed semper justo quis nisl ornare interdum in ut ante. </div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#C23D2A">
    <div class="icon"><i class="fa-solid fa-gear"></i></div>
    <div class="title">Lorem ipsum</div>
    <div class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis pretium euismod. Aenean elit sapien, varius quis ante sit amet, tincidunt finibus orci. Ut consectetur imperdiet quam, at ultrices mi rutrum ut. Sed semper justo quis nisl ornare interdum in ut ante. </div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#842C2A">
    <div class="icon"><i class="fa-solid fa-magnifying-glass"></i></div>
    <div class="title">Lorem ipsum</div>
    <div class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis pretium euismod. Aenean elit sapien, varius quis ante sit amet, tincidunt finibus orci. Ut consectetur imperdiet quam, at ultrices mi rutrum ut. Sed semper justo quis nisl ornare interdum in ut ante. </div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#022F46">
    <div class="icon"><i class="fa-solid fa-chart-column"></i></i></div>
    <div class="title">Lorem ipsum</div>
    <div class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis pretium euismod. Aenean elit sapien, varius quis ante sit amet, tincidunt finibus orci. Ut consectetur imperdiet quam, at ultrices mi rutrum ut. Sed semper justo quis nisl ornare interdum in ut ante. </div>
  </li>
  <li class="card" style="--color:#ececec; --bg-color:#032437">
    <div class="icon"><i class="fa-solid fa-circle-star"></i></div>
    <div class="title">Lorem ipsum</div>
    <div class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis pretium euismod. Aenean elit sapien, varius quis ante sit amet, tincidunt finibus orci. Ut consectetur imperdiet quam, at ultrices mi rutrum ut. Sed semper justo quis nisl ornare interdum in ut ante. </div>
  </li>
</ul>