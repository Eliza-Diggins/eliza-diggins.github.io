---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
customjs:
  - "/assets/js/accordian.js"
---

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

<p>Hello and welcome to my website!</p>
   
<p>
My name is Eliza Diggins; I'm a theoretical astrophysicist and applied mathematician at the University of Utah. My research 
is split between the Dept. of Physics and Astronomy where I study the dynamics and evolution of extragalactic systems 
and the School of Dentistry, where I study the epidemiology of autoimmune disease. Within academia, my research interests
are supplemented by advocacy for better pedagogy and inclusivity in physics and by passionate engagement with the public through 
science communication objectives. Out of the office, I am also deeply
involved in social work and activism on behalf of the LGBTQIA+ and neurodiverse communities. 
</p>
<p>
On this website, you can find information and resources regarding all of the various components of my work.</p>


Science
=======


Research Philosophy
-------------------

I believe in the inherent importance of scientific progress for its own sake and for the sake of the human endeavour. I am staunchly against
isolationism in science and believe that science in both its practice and its implementation should be a diverse and inherently human affair. 
Diversity in science is important to me and, in my opinion, one of the most important things we can use to improve the productivity, communicativity, and impact of
science on all scales. 

In my research, I strive to be radically skeptical and challenge paradigms for the sake of forcing them to stand up to challenge. It is my philosophy that
scientific skepticism drives the division between (as Kuhn would say) "normal science," and paradigm shifting research. In my research, I allow normal science, as done by myself and by others, to
drive my skeptical assessment of the paradigms we exist within. I do not believe that normal science is esoteric or unimportant, but instead that (with as much 
skepticism as can be mustered) normal science should be seen as a probe by which to methodologically challenge every aspect of every paradigm seeking faults which might lead to
new science.

As a researcher, I am deeply committed to the philosophy of interdisciplinary and holistic exploration of science in all its
forms. I am, first and foremost, a theoretical astrophysicist, but I make time to explore areas of interest in other disciplines, particularly
epidemiology and applied mathematics. I am fascinated by the methodological, cultural, and philosophical cross-over between
these various fields of scientific inquiry and the different ways in which each informs my thinking on research questions in the others.

Research Interests
------------------

In the menus below, you can find some details on my research interests and current projects in each of these areas.

<div>
<button class="accordion"><b> &#128301; Physics and Astronomy</b></button>
<div class="panel">
<p>My research interests in physics focus on the nature of extragalactic phenomena and how they inform our understanding of
more fundamental physical truths. I'm particularly interested in the nature of gravity, dark matter, dark energy, and the cosmological history
of our universe. I believe that our understanding of each of these phenomena is incomplete and that one of the next frontiers in physics could occur 
due to a paradigm shift in the way we understand the dynamics of our universe.</p> 
<p>
Right now, my research largely focuses on galaxy clusters and their role in shaping our understanding of the universe. Galaxy clusters are
the largest relaxed structures in the universe and can tell us a lot about the nature of dark matter, gravity, and cosmology. Unfortunately, these
structures are not as well understood as we would like and many of the micro-physical processes underlying the hot, X-ray emitting gas in these systems
are incompletely described leading to systemic issues in our use of these systems for cosmology. My core focus is two-fold. Firstly, what are the 
relevant physical constraints on these systems? How does the plasma physics of the gaseous component drive phenomena? How can we better model these processes
to constrain our observational measurements? Secondly, how can galaxy clusters instruct us in the nature of gravity? Are they entirely self-consistent with General Relativity?
Modified gravity theories are known to break down in galaxy cluster regimes... Why does this happen? What can that tell us about the underlying nature of the universe?
</p>
<p>
To pursue this research, I work as a member of the <a href="https://www.astro.utah.edu/~wik/">X-ray Astrophysics group at the University of Utah</a> (led by Dr. Daniel R. Wik). I focus on analytic, semi-analytic, and numerical
models of phenomena in galaxy clusters in both standard gravitational paradigms and in modified paradigms. In my role as a theorist, I have spend considerable
time in recent years using the unique dynamics of galaxy clusters to constrain theories of modified gravity; however, most recently, my attention
has shifted somewhat to the unique micro-processes that influence the intra-cluster gas dynamics of these systems. Much of this work relies
on numerical simulations (both my own and those from the wider community like the Illustris-TNG Simulations). I am also involved
in the eROSITA all-sky survey mission and have developed software for the analysis of sources from that mission.</p>
<h3>
Things I'm Thinking About Right Now
</h3>
<ul>
<li> MOND gravity theories are really successful in galaxies... Why do they suck in galaxy clusters? Why do they succeed in galaxies? </li>
<li> How can we improve the fidelity of our simulations of galaxy clusters to those observed in the real universe? </li>
<li> What drives the cosmological tensions we observe in galaxy clusters? </li>
<li> How does the micro-physics of the ICM (turbulence, viscosity, etc.) impact or theoretical predictions? </li>
<li> How do assumptions used in the analysis process influence bias in hydrostatic mass inference?</li>
</ul>

</div>
</div>
<br>
<div><button class="accordion"> &#129440; <b>Epidemiology</b></button>
<div class="panel">
  <p>As an epidemiologist, I'm most interested in the applications of mathematical modeling to our predictions about emergent pathogens. With the increasing
globalization in various regimes of our daily lives, pathogen emergence and rapid transmission is an ever increasing threat. To confront it, one needs to have a stable
understanding of the underlying dynamics of the threat. Unfortunately, COVID-19 illustrates that we still have a long way to come in this respect.</p>

<p>
At present, I'm working as part of the <a href="https://dentistry.utah.edu/research/labs/weller">Weller Lab</a> at the <a href="https://dentistry.utah.edu/research/labs/weller">University of Utah School of Dentistry</a> to model
emergent, trade-mediated pathogens. These pathogens, which could range from the relatively common <i>Salmonella enteritidis</i> to yet unknown entities of disease, are characterized by their mobility 
in the international food supply. My research interests are largely focused on asking questions regarding the epidemiological consequences of an emergent pathogen with the infectious potential of
a COVID-19 like epidemic. I work on designing mathematical models for the prediction and characterization of these threats as well as building early warning algorithms for these
emergent events. Our lab is uniquely focused on the intersections of healthcare access, infectious disease, and autoimmunity; as such, I am also active
in constructing mathematical models directed and improving our understanding of the interactions between these aspects of our research.
</p>

<p>
In addition to my mathematical role in the lab, I am also the science lead of the Weller Lab Data Science Group. This group is focused
in the use of unparalleled EHR databases to better understand and model the dynamics and relationships between auto-immune disease and
infectious disease.
</p>
<h3>
Things I'm Thinking About Right Now
</h3>
<ul>
<li> Can emergent infectious diseases trigger auto-immune disease during acute infections? </li>
<li> Why are autoimmune diseases predominantly found to affect female patients?</li>
<li> What testing procedures can improve overall patient care for those with rare / stigmatized diseases?</li>
</ul>
</div>
</div>
<br>
<div><button class="accordion"> &#127759; <b>Climate Science</b></button>
<div class="panel">
  <p>As part of my work as an epidemiologist, I am very interested in exploring the role that climate change plays in the 
behavior of pathogens and the epidemics that they cause. The global impacts of climate change are extremely diverse and play out in many ways
which influence human disease. Food scarcity weakens immune response in those suffering from it and drives mass migration which is tied to epidemic outbreaks. Drought conditions
drive increased pathogen susceptibility in plants, which threatens our food supplies. All of these issues and others are the focus of my interests in climate science.
</p>
Currently, my work is focused on the way that drought induced pathogen susceptibility in plants underpinning our food supply can drive epidemic emergence and threaten
that food supply. I have been honored to engage in this research field as <a href="https://wilkescenter.utah.edu/">a Wilkes Scholar</a> at the University of Utah.
</div>
</div>
<br>
<div>
<button class="accordion"> &#9854;&#65039; <b>Applied Mathematics</b></button>
<div class="panel">
  <p>Applied mathematics is the backbone of everything I do in both epidemiology and in astrophysics. As such, much of my research in applied math is focused on relatively esoteric
questions regarding my other work. Nonetheless, research in mathematics is one of my favorite activities!</p>
<p>
Recently, I've been most interested in numerical analysis questions. I spend a lot of time characterizing algorithms for generating large scale networks from underlying datasets. In studying epidemiology in
the global food supply, I am required to characterize the underlying network structure which drives that phenomenology.
</p>
<p>
I also spend a lot of time building algorithms for various numerical analysis tasks in astrophysics. Currently, i'm really interested in interpolation methods for 
requiring physical models (say radial profiles of density or mass) to have the correct, physically reasonable, structures. This problem is one which is usually confronted in a case-by-case manner; however,
a more standard algorithm (while not ground breaking) would be extremely helpful in reducing the labor around many tasks of this type.
</p>
</div>
</div>
<br>

More Than a Scientist
---------------------

![Static Badge](https://img.shields.io/badge/Encircle_Utah-Donate-pink?style=for-the-badge&labelColor=lightblue&link=https%3A%2F%2Fencircletogether.org%2Fcommunitycircle)

I firmly believe that the fundamental research of scientists is a critical component of the human endeavour.
Nonetheless, scientific fields (particularly physics) remain a space largely occupied by those with the economic, social, and educational
freedom to pursue abstract and esoteric knowledge for its own sake. Implicit in that reality is the universal conception that scientists are
(all else being equal) worthy of respect and admiration solely on behalf of their intellect. 

As a transgender woman (and as an autistic one), I feel a strong sense of duty to utilize the social capital that comes with 
my intellect to advocate for others like me who have not been as fortunate. Within academia, this component of my ethos has driven
my interest in public outreach, diversity and inclusion education, and inclusive pedagogical methods in the classroom.

Outside of academia, I have found great purpose in advocating for my communities and for those who experience the same intersectional
difficulties that I do. I am the facilitator (and intern) of a peer support group for transgender adults hosted by [Encircle](https://www.encircletogether.org)'s Salt Lake City Home.
Due to the unique challenges faced by this community, I have dedicated significant time to pursuing positions of responsibility and advocacy within the queer
community of Utah; to better equip community members, organizations, and LGBTQ+ individuals with the resources and support they need to succeed.

([Read More](https://eliza-diggins.github.io/service.html))

<script type='text/javascript' src='/assets/js/accordian.js'>

</script>