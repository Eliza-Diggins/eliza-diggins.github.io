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

   I'm a theoretical astrophysicist and mathematician at the University of Utah. My research is shared between the Department of Physics
and Astronomy, where I study galaxy cluster dynamics and gravitational theory; and the School of Dentistry, where I work on mathematical models
of trade-mediated pathogens in complex global trade networks. 



Research Interests
==================

As a researcher, I am deeply committed to the philosophy of interdisciplinary and holistic exploration of science in all its
forms. I am, first and foremost, a theoretical astrophysicist, but I make time to explore areas of interest in other disciplines, particularly
epidemiology and applied mathematics. I am fascinated by the methodological, cultural, and philosophical cross-over between
these various fields of scientific inquiry and the different ways in which each informs my thinking on research questions in the others.

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
models of phenomena in galaxy clusters in both standard gravitational paradigms and in modified paradigms. In doing this research, I have contributed to our theoretical
understanding of the dynamics of both modified gravity theories and galaxy clusters in general. I am also a very active software developer for numerical approaches to these problems. See
my software page for a description of my code projects and those that I make heavy use of!</p>
<h2>
Things I'm Thinking About Right Now
</h2>
<ul>
<li> MOND gravity theories are really successful in galaxies... Why do they suck in galaxy clusters? Why do they succeed in galaxies? </li>
<li> How can we improve the fidelity of our simulations of galaxy clusters to those observed in the real universe? </li>
<li> What drives the cosmological tensions we observe in galaxy clusters? </li>
<li> How does the microphysics of the ICM (turbulence, viscosity, etc.) impact or theoretical predictions? </li>
</ul>

</div>
</div>
<br>
<div><button class="accordion"> &#129440; <b>Epidemiology</b></button>
<div class="panel">
  <p>As an epidemiologist, I'm most interested in the applications of mathematical modeling to our predictions about emergent pathogens. With the increasing prevailance
of globalization in various regimes of our daily lives, pathogen emergence and rapid transmission is an ever increasing threat. To confront it, one needs to have a stable
understanding of the underlying dynamics of the threat. Unfortunately, COVID-19 illustrates that we still have a long way to come in this respect.</p>

<p>
At present, I'm working as part of the <a href="https://dentistry.utah.edu/research/labs/weller">Weller Lab</a> at the <a href="https://dentistry.utah.edu/research/labs/weller">University of Utah School of Dentistry</a> to model
emergent, trade-mediated pathogens. These pathogens, which could range from the relatively common <i>Salmonella enteritidis</i> to yet unknown entities of disease, are characterized by their mobility 
in the international food supply. My research interests are largely focused on asking questions regarding the epidemiological consequences of an emergent pathogen with the infectious potential of
a COVID-19 like epidemic. I work on designing mathematical models for the prediction and characterization of these threats as well as building early warning algorithms for these
emergent events.
</p>

<p>
In addition to my mathematical role in the lab, I also work on data science related projects. With the availability of massive, global, and diverse healthcare datasets, our lab focuses
much of its time on characterizing relationships between rare diseases, autoimmune disorders, and emergent pathogens. One of the most interesting questions we are working on is characterizing the capacity of
pathogenic entities to induce autoimmune responses in vulnerable patients.
</p>
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

Research Philosophy
===================

I believe in the inherent importance of scientific progress for its own sake and for the sake of the human endeavour. I am staunchly against
isolationism in science and believe that science in both its practice and its implementation should be a diverse and inherently human affair. 
Diversity in science is important to me and, in my opinion, one of the most important things we can use to improve the productivity, communicativity, and impact of
science on all scales. 

In my research, I strive to be radically skeptical and challenge paradigms for the sake of forcing them to stand up to challenge. It is my philosophy that
scientific skepticism drives the division between (as Kuhn would say) "normal science," and paradigm shifting research. In my research, I allow normal science, as done by myself and by others, to
drive my skeptical assessment of the paradigms we exist within. I do not believe that normal science is esoteric or unimportant, but instead that (with as much 
skepticism as can be mustered) normal science should be seen as a probe by which to methodologically challenege every aspect of every paradigm seeking faults which might lead to
new science.

Learning Interests
------------------

The opportunity to engage in research as a career is extremely exciting, but it is also somewhat limiting. Unfortunately, there are only so
many hours in any given day! Nonetheless, there are variety of other areas of academics / life which interest me greatly even if the aren't the focus
of my research. I'm a big advocate for life-long curiosity, especially when that takes you outside of your comfort zone! Below are some of the things that I'm extremely interested
in, yet only marginally (if at all) competent in!

<ul>
<li><h3>Science</h3>
<ul>
<li>Circuit design and all things almost getting electrocuted.</li>
<li>Deeply theoretical physics, mathematically physics, Lie Algebras, other moderately arcane math stuff.</li>
<li>Immunology (even though I don't understand it).</li>
<li>I have a (semi-unhinged) passion for herpetology.</li>
</ul>
</li>
<li><h3>Social Science</h3>
<ul>
<li>Psychiatry / Psychology particularly as it pertains to fellow people on the autism spectrum and in the LGBTQ+ community.</li>
<li>Behavioral psychology</li>
</ul>
<li><h3>Social Work</h3></li>
<ul>
<li>As a transgender person and as an autistic one, I exist in an intersection of experience which often comes with a lot of hardship. Due to my circumstances, I've been very privledged in
both of those identities and therefore spend a great deal of effort giving back to those less fortunate than myself. For that reason, I am 
extremely passionate about the practice of social work in all its forms and the ways in which excellent social workers change the lives of those around them!</li>
</ul>
</li>
</ul>

<script type='text/javascript' src='/assets/js/accordian.js'>

</script>
