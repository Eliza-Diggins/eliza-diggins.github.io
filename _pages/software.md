---
permalink: /software/
title: "Code"
author_profile: true
redirect_from: 
  - /code/
  - /code.html
customjs:
  - "/assets/js/accordian.js"
---

<style>
#container{
    width: 100%;
}
#floated{
    float: left;
    width: 50%;
}
</style>
<style>
.accordion {
  background-color: #eee;
  border-radius: 10px;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  text-align: left;
  border: 1px solid blue;
  outline: none;
  transition: 0.4s;
}

/* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the mouse over it (hover) */
.active, .accordion:hover {
  background-color: #ccc;
}

/* Style the accordion panel. Note: hidden by default */
.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0px;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}
.accordion:after {
  content: '\02795'; /* Unicode character for "plus" sign (+) */
  font-size: 13px;
  color: #777;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2796"; /* Unicode character for "minus" sign (-) */
}
</style>

<div id="container">
<div id="floated" style="float: right; padding: 10px">
<a href="https://xkcd.com/979/"><img decoding="async" loading="lazy" class="size-full" src="https://imgs.xkcd.com/comics/wisdom_of_the_ancients.png" alt="Frustration while programming? Never."></a>
</div>
All joking aside, its no secret that physicists spend a great deal of their time on the verge of tears (you heard it here first) because their C (or FORTRAN) code isn't running
or (heaven forbid) they can't find the answer they need on stack exchange. I won't even mention how annoying this website can be to work on!
<p>
Unfortunately, scientific software is often very niche and isn't easy to find, let alone use. This becomes an extra nuisance because *some people* (cough cough physicists) don't seem particularly
interested in writing good documentation or any documentation for that matter. Fortunately, I actually quite enjoy developing software! For that reason, I've used this page
to feature some of the excellent code that I use in my day-to-day research. Only a few of these codes are ones that I've personally worked on developing, but they are all invaluable tools
for the sort of research that I do!
</p>
</div>

Astrophysics Codes
==================


<div>
<button class="accordion"><b> &#128301; Analysis</b></button>
<div class="panel">
</div>
</div>
<div>
<button class="accordion"><b> &#128301; N-Body / Hydrodynamics Simulations</b></button>
<div class="panel">
</div>
</div>
<div>
<button class="accordion"><b> &#128301; Initial Conditions</b></button>
<div class="panel">
</div>
</div>
<br>

Epidemiological Software
========================
<div>
<button class="accordion"><b> &#129440; Analysis</b></button>
<div class="panel">
</div>
</div>

<script type='text/javascript' src='/assets/js/accordian.js'>

</script>

