---
layout: post
title:  "Gravitational Waves in an Inhomogeneous Universe"
author: Shashank Pandey
permalink: shashank_pandey_gravitational_waves_inhomogeneous_universe
categories: [Cosmology and Nongalactic Astrophysics]
tags: [Cosmology, Inhomogeneous universe, Gravitational waves]
class: [Review article]
image: ../assets/images/shashank_pandey_gravitational_waves_inhomogeneous_universe_images/cover_image.jpg
featured: False
hidden: False
review: true
---
>Space is quite inhomogeneous at small scales. These inhomogeneities may play a significant role in governing the physical phenomena at this scale. Here we have analysed the impact of these inhomogeneities on the Gravitational Wave (GW) observables. For this analysis we have made use of a toy model of the inhomogeneous spacetime. Our analysis shows that the amplitude of GW gets affected by these inhomogeneities and this effect is governed by our model parameters.
>
---

# Introduction
The Cosmological Principle states that the Universe is homogeneous and isotropic at large scales. Various surveys like <a href="https://www.sdss.org/">Sloan Digital Sky Survey</a> have revealed <a href="https://academic.oup.com/mnras/article-pdf/443/1/241/4292640/stu1118.pdf">deviations from homogeneity on samples as large as 500 h<sup>-1</sup> Mpc</a>. In comparison, <a href="https://imagine.gsfc.nasa.gov/features/cosmic/milkyway_info.html">Milky Way galaxy is about 30 kpc across</a>. These inhomogeneities play an important role in governing the physical phenomena at this scale. The physical phenomena that we have considered here is the propagation of Gravitational Waves (GWs). 

GWs have been a fascinating feature of Physics ever since <a href="https://onlinelibrary.wiley.com/doi/pdf/10.1002/3527608958.ch7">Einstein</a>
predicted their existence. <a href="https://www.ligo.caltech.edu/page/gravitational-waves">GWs are ripples in spacetime</a>
produced when the acceleration of the second mass moment of the associated motion of a system of masses is non-vanishing. This is valid provided higher order moments are neglected. In <a href="https://ned.ipac.caltech.edu/level5/March01/Carroll3/Carroll6.html">TT (transverse traceless) gauge</a> this second mass moment is given by the quadrupole moment. These waves move outwards from their source. Before reaching the observer these waves propagate through the spacetime. In this work, we have analysed how the amplitude of these GWs gets affected by the inhomogeneities present in spacetime.

# Formalism 

<i><sub></sub></i>

To study an inhomogeneous spacetime, a suitable averaging procedure is required. In this work, we have used <a href="https://doi.org/10.1023/A:1001800617177">Buchert's averaging procedure</a>
proposed by Thomas Buchert. Buchert's approach was to first decompose Einstein's equation into a set of dynamical equations for scalar quantities using Raychaudhuri equation and then average those scalar quantities. <a href="https://www.ias.ac.in/article/fulltext/pram/069/01/0049-0076">Raychaudhuri equation is concerned with the kinematics of flow.</a>
Using Einstein's equation and Raychaudhuri equation ensures that the procedure is GR compliant.

For our analysis we have used a <a href="https://doi.org/10.1088/1475-7516/2006/11/003">toy model</a>
based on Buchert's averaging procedure. This toy model presents a simplified picture of the inhomogeneous spacetime where a domain of space has been divided into two types of regions - one overdense region and one underdense region. Here, overdense region is a closed, dust only <a href="https://www.physicsforums.com/insights/journey-cosmos-flrw-metric-friedmann-equation/">Friedmann–Lemaître–Robertson–Walker</a>
(FLRW) region while the underdense region is an empty FLRW region. The physical interpretation of this toy model is that the domain of space of our toy model represents the spacetime through which GW is propagating. The overdense region is the matter filled region that the GW encounters in its path while the underdense region is the region of cosmic void.

There are two parameters governing our model; <i>f<sub>u</sub></i>,the volume fraction of the underdense region and <i><b>&beta;</b></i>, the factor governing the time evolution of the scale factor for the underdense region. For the overdense region, there is also <i>f<sub>o</sub></i>, the volume fraction of the overdense region, which is related to <i>f<sub>u</sub></i> by the relation: <i>f<sub>u</sub></i> + <i>f<sub>o</sub></i> = 1. These parameters completely determine our toy model. The intervening region between source and observer through which GWs propagate can have any combination of this (<i>f<sub>o</sub></i>,<i>f<sub>u</sub></i>). Therefore we have used different combinations of (<i>f<sub>o</sub></i>,<i>f<sub>u</sub></i>) for our analysis. Using Buchert's averaging procedure and this toy model, we can calculate various averaged scalar quantities for the domain under analysis, like averaged density, averaged Hubble parameter, etc.

Our toy model is a theoretical model. In order to check the validity of our analysis, we need to relate the quantities calculated using our toy model with observational quantities. This is where <a href="https://doi.org/10.1088/1475-7516/2009/02/011">Covariant Scheme</a>
comes to our rescue. It relates the theoretically calculated quantities from our toy model, averaged density of the domain and averaged Hubble parameter of the domain, with angular diameter distance <i>D<sub>A</sub></i>, an observational quantity.


# Results 

<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>MathJax example</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
          src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
</head>
<body>
<p>
  The redshift-dependent part of GW amplitude is given by,

  \[A = {(1+z)^{5/3} \over D_L},\]
  
  where z is the redshift factor and \(D_L\) is the luminosity distance which is related to angular diameter distance by the relation,
  
  \(D_L = (1+z)^2 D_A.\)
  
</p>
</body>
</html>

We have plotted this quantity <i>A</i> for different combinations of our model parameter in Figure 1 & Figure 2 and we have related these plots with the homogeneous <b>&Lambda;<sub>CDM</sub></b> plot as well. Figure 1 shows that for a certain combination of our model parameters, the plot for our inhomogeneous toy model is very close to the plot of homogeneous <b>&Lambda;<sub>CDM</sub></b> model. As we vary our model parameters from this particular combination, the plot for our toy model starts deviating from the plot of the <b>&Lambda;<sub>CDM</sub></b> model and this deviation increases as we vary our model parameters more and more from that particular combination.

![A new image here](../assets/images/shashank_pandey_gravitational_waves_inhomogeneous_universe_images/image1_Shashank_Shekhar_Pandey.png)
<p align = "center">
Figure 1: Plot of the redshift dependent part of the gravitational wave amplitude w.r.t. redshift <i>z</i>, for the <b>&Lambda;<sub>CDM</sub></b> model and for our model for various combinations of the volume fractions <i>f<sub>o</sub></i> and <i>f<sub>u</sub></i>, with <i><b>&beta;</b></i> = 1. 
Credits: <a href="https://arxiv.org/abs/2201.06489">Shashank S. Pandey et al., 2022</a>.
</p>

![A new image here](../assets/images/shashank_pandey_gravitational_waves_inhomogeneous_universe_images/image2_Shashank_Shekhar_Pandey.png)
<p align = "center">
Figure 2: Plot of redshift dependent part of the gravitational wave amplitude  w.r.t. redshift <i>z</i>, for the <b>&Lambda;<sub>CDM</sub></b> model and for our model for different values of the parameter <i><b>&beta;</b></i>, for the combination of fractions <i>f<sub>u</sub></i> = 0.91 and <i>f<sub>o</sub></i> = 0.09. 
Credits: <a href="https://arxiv.org/abs/2201.06489">Shashank S. Pandey et al., 2022</a>.
</p>

Figure 2 shows that for only one particular combination of (<i>f<sub>o</sub></i>,<i>f<sub>u</sub></i>) and <i><b>&beta;</b></i>, the plot for our toy model is very close to the homogeneous <b>&Lambda;<sub>CDM</sub></b> plot. For all other combinations of (<i>f<sub>o</sub></i>,<i>f<sub>u</sub></i>) and <i><b>&beta;</b></i>, there is substantial deviation from the homogeneous <b>&Lambda;<sub>CDM</sub></b> case. This shows that inhomogeneities in spacetime play an important role in the propagation of GWs and therefore should not be ignored.

# Conclusions
Our study shows that the inhomogeneities present in the spacetime have substantial effect on the observables of GWs traversing through this spacetime. Our present analysis should inspire further studies of the effect of inhomogeneous spacetime on various other physical phenomena.




**Original paper:**
<a href="https://iopscience.iop.org/article/10.1088/1475-7516/2022/06/021" target="_blank">Effect of inhomogeneities on the propagation of gravitational waves from binaries of compact objects
</a>

**First Author:** Shashank Shekhar Pandey

**Co-authors:** Arnab Sarkar, Amna Ali and A.S. Majumdar

**First author’s Institution:** 
 Department of Astrophysics and Cosmology, S. N. Bose National Centre for Basic Sciences,JD Block, Sector III, Salt lake city, Kolkata-700106, India


<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://cosmicvarta-in.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
