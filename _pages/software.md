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
  max-height: 1000px;
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

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:sans-serif;
}

.container{
  max-width:1000px;
  min-height: 500px;
  display:flex;
  align-items:center;
  justify-content:center;
}
.card{
  min-height:200px;
  width:260px;
  margin:40px 10px;
  padding:1rem;
  cursor:pointer;
  background-color:#fff;
  border-style: solid;
  border-color: black;
  border-radius: 30px;
}
.card img{
  width:100%;
  height:160px;
  border-radius:10px;
  background-color: white;
  position:relative;
  z-index:1000;
  transition:all .5s ease-in-out;
}
.card__content{
  margin:1rem 0;
  color:#222;
  overflow:hidden;
  margin-top:-200px;
  opacity:0;
  visibility:hidden;
  transition:all .5s ease-in-out;
}
.card__content h2{
  margin:.6rem auto;
  text-align:center;
  visibility: visible;
}
.card__content p{
  font-size:0.8rem;
  line-height:1.0rem;
  text-align:center;
  color: black;
}
.card__content a{
  width:200px;
  padding:10px 15px;
  display:block;
  text-align:center;
  margin:.6rem auto;
  font-size:1.1rem;
  color:#444;
  text-decoration:none;
  background-color:#222;
  border-radius:10px;
  transition:.3s;
}
.card__content a:hover{
  color:#fff;
  background-color:#111;
  box-shadow:0 0 2px 2px rgba(0,0,0,0.4);
}
.card:hover img{
  margin-top:-60px;
  box-shadow:0 0 4px 6px rgba(0,0,0,0.3);
}
.card:hover>.card__content{
  margin-top:0;
  opacity:1;
  visibility:visible;
}
@media screen and (max-width:800px){
  .container{
    flex-wrap:wrap;
  }
}

</style>

<div>
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
<div class="container">
  <div class="card">
    <img src="https://raw.githubusercontent.com/yt-project/yt/main/doc/source/_static/yt_logo.png"/>
    <div class="card__content">
      <h2>The yt Project</h2>
      <p>
         <code style="color:black">yt</code>is the gold standard for analyzing volumetric data of all types. The vast
          majority of my personal analysis pipeline relies heavily on <code style="color:black">yt</code>.
      </p>
      <a href="https://github.com/yt-project/yt">Read More</a>
    </div>
  </div>
  <div class="card">
    <img src="http://pynbody.github.io/pynbody/_static/logo.svg"/>
    <div class="card__content">
      <h2>pynbody</h2>
      <p>
      A lighter weight approach to simulation analysis than yt, pynbody is extremely useful for analysis with SPH
      datasets and provides very quick snapshots of data without as much setup as yt. It is not well suited to AMR simulations.
</p>
      <a href="https://www.github.com/jzuhone/cluster_generator">Read More</a>
    </div>
  </div>
</div>
</div>
</div>
<div>
<button class="accordion"><b> &#128301; N-Body / Hydrodynamics Simulations</b></button>
<div class="panel">
<div class="container">
  <div class="card">
    <img src="/images/ramses.png"/>
    <div class="card__content">
      <h2>RAMSES</h2>
      <p>
         Documentation be damned, RAMSES is a great option for hydrodynamics / N-body simulation. Just 
         hope to god you don't need to dive under the hood. Or find a logo.
      </p>
      <a href="https://bitbucket.org/rteyssie/ramses/src/master/">Read More</a>
    </div>
  </div>
</div>
</div>
</div>
<div>
<button class="accordion"><b> &#128301; Initial Conditions</b></button>
<div class="panel">
<div class="container">
  <div class="card">
    <img src="/images/cluster_generator_logo.png"/>
    <div class="card__content">
      <h2>Cluster Generator</h2>
      <p>
         <code style="color:black">cluster_generator</code>is an actively supported
         initial conditions generator for galaxy clusters. It supports ICs for most of the 
         popular simular codes. Developed by John ZuHone.
      </p>
      <a href="https://www.github.com/jzuhone/cluster_generator">Read More</a>
    </div>
  </div>
</div>
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

