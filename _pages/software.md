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

.container {
    width: 100%;
    padding: 4%;
    position: relative;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.container .card {
    position: relative;
    border-radius: 10px;

}

.container .card .icon {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #f00;
    transition: 0.7s;
    z-index: 1;
}

.container .card:nth-child(1) .icon {
    background: #e07768;
}

.container .card:nth-child(2) .icon {
    background: #6eadd4;
}

.container .card:nth-child(3) .icon {
    background: #4aada9;
}


.container .card .icon .fa {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 80px;
    transition: 0.7s;
    color: #fff;
}

i {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 80px;
    transition: 0.7s;
    color: #fff;
}

.container .card .face {
    width: 75%;
    height: 200px;
    transition: 0.5s;
}

.container .card .face.face1 {
    position: relative;
    background: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 1;
    transform: translateY(100px);
}

.container .card:hover .face.face1{
    background: #ff0057;
    transform: translateY(0px);
}

.container .card .face.face1 .content {
    opacity: 1;
    transition: 0.5s;
}

.container .card:hover .face.face1 .content {
    opacity: 1;
}

.container .card .face.face1 .content i{
    max-width: 100px;
}

.container .card .face.face2 {
    position: relative;
    background: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
    box-sizing: border-box;
    box-shadow: 0 20px 50px rgba(0,0,0,0.8);
    transform: translateY(-100px);
}

.container .card:hover .face.face2{
    transform: translateY(0);
}

.container .card .face.face2 .content p {
    margin: 0;
    padding: 0;
    text-align: center;
    color: #414141;
}

.container .card .face.face2 .content h3 {
    margin: 0 0 10px 0;
    padding: 0;
    color: #fff;
    font-size: 24px;
    text-align: center;
    color: #414141;
}

.container a {
    text-decoration: none;
    color: #414141;
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
<div class="container">
        <div class="card">
            <div class="face face1">
                <div class="content">
                    <div class="icon">
                        <i class="fa fa-linkedin-square" aria-hidden="true"></i>
                    </div>
                </div>
            </div>
            <div class="face face2">
                <div class="content">
                    <h3>
                        <a href="https://www.linkedin.com/in/adamdipinto/" target="_blank">_adamdipinto</a>
                    </h3>
                    <p>This is where I network and build my professional protfolio.</p>
                </div>
            </div>
        </div>
        <div class="card">
            <div class="face face1">
                <div class="content">
                    <div class="icon">
                        <i class="fa fa-twitter-square" aria-hidden="true"></i>
                    </div>
                </div>
            </div>
            <div class="face face2">
                <div class="content">
                    <h3>
                        <a href="https://twitter.com/AdamDipinto" target="_blank">@AdamDipinto</a>
                    </h3>
                    <p>This is where I read news and network with different social groups.</p>
                </div>
            </div>
        </div>
        <div class="card">
            <div class="face face1">
                <div class="content">
                    <div class="icon">
                        <i class="fa fa-github-square" aria-hidden="true"></i>
                    </div>
                </div>
            </div>
            <div class="face face2">
                <div class="content">
                    <h3>
                        <a href="https://github.com/atom888" target="_blank">atom888</a>
                    </h3>
                    <p>This is where I share code and work on projects.</p>
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

