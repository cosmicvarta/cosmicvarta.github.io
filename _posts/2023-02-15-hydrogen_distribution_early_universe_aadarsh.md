---
layout: post
title:  "Exploring the topology of hydrogen distribution in the early universe"
author: Aadarsh Pathak
permalink: hydrogen_distribution_early_universe_aadarsh
categories: [Cosmology and Nongalactic Astrophysics]
tags: [Cosmology, Epoch of Reionization, Largest Cluster Statistics, Percolation]
class: [Review article]
image: assets/images/hydrogen_distribution_early_universe_aadarsh/image_cover.jpg
featured: False
hidden: False
review: true
---
<hr color="black">
>
We study how galaxies and other sources in the early universe change the neutral universe or InterGalactic Medium (IGM) into the ionized one. We compare different kinds of source models and how they ionize the neutral universe which mainly consists of neutral hydrogen. We trace the largest ionized region formed by these sources by using a statistic known as the Largest Cluster Statistics (LCS). We found that LCS of different source models evolve differently and hence show different natures of ionizing photons or sources. We also investigate the geometry and topology of these ionized regions and how they are different for each model.
>
---

<hr color="black">
# Introduction
<hr color="black">

The universe on a very large scale seems like a web which we astronomers refer to as the cosmic web. Entities like galaxies and clusters of galaxies are trapped within this giant web (see figure 1). The unknown but the most abundant matter, dark matter, plays a governing role in shaping these giants by capitalizing the full potential of the most dominant force on a cosmic scale, gravitational force. We put our efforts to understand the formation and evolution of the universe including these giants by looking at the driving physics behind these. 

<p align="center">
  <img src="../assets/images/hydrogen_distribution_early_universe_aadarsh/image1.jpg">
</p>
<p align = "center">
 Figure 1: Image of the cosmic web. Figure shows the dark matter distribution (taken from the Millennium simulation). Here, every bright point represents a galaxy cluster. Image Credit: V.Springel, Max-Planck-Institut für Astrophysics.
</p>
The universe has undergone a significant transition on a regular basis since its birth. Figure 2 shows the evolution of our universe from the Big Bang on the left hand side to the current local universe which we see today  on the right hand side of the plot. One of the major recent and remarkable phase transitions is the Epoch of Reionization (EoR), when the neutral Intergalactic Medium (IGM), mainly composed of neutral hydrogen, gets transformed into an ionized one. The galaxies residing within the dark matter halos (host of galaxies) act as one of the primary sources responsible for the reionization. 

<p align="center">
  <img src="../assets/images/hydrogen_distribution_early_universe_aadarsh/image2.jpg">
</p>
<p align = "center">
Figure 2: Pictorial representation of the evolution of our Universe according to the standard cosmological model. Image credit: <a href="https://astrobites.org/" target="_blank">astrobites</a> 
</p>

In order to understand this era, we use several techniques and approaches to recreate the environment. We use analytic models (refer to  <a href="https://arxiv.org/abs/1209.2215" target="_blank">  Wyithe and Loeb 2012</a>), semi-analytic models (refer to <a href="https://arxiv.org/abs/1512.00562" target="_blank">  Mutch et al 2016</a>), semi-numerical models (refer to <a href="https://doi.org/10.1093/mnras/stv2812" target="_blank">  Majumdar et al. 2016</a> ), etc., to understand the EoR and to comply with what we observe from large surveys conducted using advanced telescopes that are increasingly more sensitive.

It is evident that different sources during EoR emit different kinds of ionizing photons, and hence, ionize the IGM in a different way. In our analysis, we investigate this era by focusing on the properties of some of these possible sources which can ionize the IGM. We consider six reionization source models based on the semi-numerical method originally proposed in <a href="https://doi.org/10.1093/mnras/stv2812" target="_blank">  Majumdar et al. 2016</a>. These source models differ from each other in two main aspects: a) how the number of ionizing photons emitted by the sources are related to their host halo mass i.e. Nphotons ∝ (Mhalo)n and b) how the rest frame energy of the ionizing photons is distributed. The different source models considered in our work are mentioned in the table below. The Uniform Ionizing Background (UIB) dominated source model emits hard X-ray photons having large mean free path and hence creates a uniform ionizing background. The Soft X-Ray (SXR) dominated source model emits soft X-ray photons having limited mean free path. Source models like Fiducial (assumes 100% contribution of UV rays coming out from the galaxies residing inside the dark-matter halos) and Power Law (PL) (n=3) differ from each other in terms of the number of ionizing photons they emit following the relation shown in point (a) above.

<hr color="black">

| Reionization models | Ultraviolet photons (UV) | Uniform Ionizing Background (UIB) | Soft X-Ray photons (SXR) | Power Law (PL), (n) |
| :---:           |    :----:   |   :---:       |    :---:       |     :---:     | 
| Fiducial        | 100 %       | -   |     -    |     1    | 
| Clumping        | 100 % and Non Uniform Recombination        | -      |     -     |     1     |
| UIB Dominated   | 20 %        | 80%      |     -     |     1      |
| SXR Dominated   | 20 %        |    -   |     80%    |     1      |
| UV + SXR + UIB   | 50%        | 10%      |     40%      |     1      |
| PL (n=3)        | 100%        | -      |     -     |    3      |

<hr color="black">

Reionization scenario like clumping model shows an extreme reionization case considering the clumpiness of the density field and emits ultraviolet (UV) photons. On the other hand, UV + SXR + UIB source model shows a combined contribution of UV photons, hard X-ray photons and soft X-ray photons.

We investigate how the ionized regions formed by these sources evolve with redshift and what geometrical or topological information we can grab from their evolution by looking at their shape and size. One can use Minkowski functionals (a set of four functionals which gives information about the geometrical and topological distribution of matter in the universe) (for example,  <a href="https://doi.org/10.1093/mnras/sty714" target="_blank">Bag et al. 2018</a>, <a href="https://arxiv.org/abs/astro-ph/9312028" target="_blank">Mecke et al. 1994</a>) to define the morphology of an object. In our work, we specifically use this to define the shape and size of our object (ionized region in our case). We use an algorithm called SURFGEN2 which identifies ionized regions from the density field and informs about their shape and size in the form of three Shapefinders (namely, thickness, breadth and length).

If we look at these ionized regions, with time, different reionization source models forming these ionized regions grow in size as well as in numbers, which then start to overlap. At some point in time, they coalesce together and form a single large connected ionized region as one can notice from the middle and right panels in the figure 3. This transition phase is known as the percolation transition (one can look at the articles <a href="https://articles.adsabs.harvard.edu/pdf/1993ApJ...413...48K" target="_blank">Klypin and Shandarin 1993</a>, <a href="https://articles.adsabs.harvard.edu/pdf/1996ApJ...465....2Y" target="_blank">Capp Yess and Shandarin 1996</a>).  In our analysis, out of many ionized regions, we primarily focus on the largest ionized region and its evolution around the percolation. We use the Largest Cluster Statistics (LCS) which is defined as the ratio of the volume of the largest ionized region to that volume of all ionized regions in a simulation volume to trace the largest ionized region. 


<p align="center">

LCS = Volume of Largest Ionized Region / Volume of all ionized region 

</p>

Before percolation we have a very small largest ionized region but as we reach percolation and after percolation, the ionized region increases drastically, and at the end of reionization, almost the entire simulation box is filled with the largest ionized region as evident from the figure 3 as we go from left to right.

<p align="center">
  <img src="../assets/images/hydrogen_distribution_early_universe_aadarsh/image3.png">
</p>
<p align = "center">
Figure 3: Figure shows the transition of the largest ionized region from smaller size before percolation to the size of the entire simulation box after percolation. Middle panel shows the onset of percolation. 
</p>

As the reionization progresses, the neutral hydrogen present in the IGM ionizes and eventually the entire IGM converts into an ionized one at the end of the reionization. The neutral fraction (x<sub>HI</sub>) informs about the amount of neutral hydrogen present in a volume with respect to the entire hydrogen species including both neutral and ionized one at any time. In our analysis, we use this quantity to see the evolution of LCS and shapefinders which we discussed.

<hr color="black">
# Results
<hr color="black">

### Evolution of Largest Cluster Statistics
<hr color="black">

The largest ionized region evolves differently for different reionization source models. The point of percolation is also different for different models. The inside-out scenarios where the reionization starts from the denser part of the IGM and then proceeds to the less dense part, the percolation occurs at much higher neutral fraction as compared to its counterpart, the outside-in scenario, where reionization starts from less dense regions and then the high-dense region is covered. 

Figure 4 shows the variation of Largest Cluster Statistics (LCS) with the neutral fraction and Filling Factor (FF) for different reionization models. Here, Filling Factor is defined as the ratio of volume of all ionized regions to volume of our simulation box. One can notice from the left panel that the largest ionized region or LCS before percolation (shown by vertical lines) is significantly small for all reionization models but at the onset of percolation and after percolation, an abrupt increment in LCS can be observed. This result is quite obvious because as the reionization progresses, different ionized regions grow and interconnect with each other and hence form a single interconnected ionized region which is true for all reionization models as one can notice from the figure. Hence, before percolation, when we have a very small largest ionized region, it is indistinguishable from other ionized regions but as we reach percolation, they interconnect and become quite distinguishable. It depicts how the neutral IGM slowly transformed into an ionized one when the ionized bubbles got enough time to develop. However, percolation for different models occurs at different neutral fractions. The inside-out reionization models percolate at higher neutral fraction (shown by solid lines) whereas the outside-in reionization models percolate at lower neutral fraction. At the end of reionization, we can observe a single large ionized region occupying the entire simulation volume as is evident from the right panel of figure 4, where LCS is close to unity.

<p align="center">
  <img src="../assets/images/hydrogen_distribution_early_universe_aadarsh/image4.png">
</p>
<p align = "center">
Figure 4: The percolation transition has been compared for all six reionization models in terms of LCS. The left panel shows the LCS as a function of neutral fraction (x<sub>HI</sub>) whereas the right panel illustrates how LCS evolves with FF for the different reionization scenarios. In both panels, the vertical lines represent the percolation transitions in the reionization models with corresponding colors. 
</p>

Hence, we can say that following the LCS along with the percolation, we can distinguish between the two broad categories of reionization models i.e, inside-out and outside-in reionization models.

<hr color="black">
### Shape of Largest Ionized Region
<hr color="black">

The ionized bubbles formed by different sources, in principle, can be of complicated shape or geometry as they grow. For ease of understanding, one can use a simple geometrical or topological approach for the same. The Shapefinder technique uses Minkowski functionals to unveil the shape and size of the ionized region. The four Minkowski functions for a closed 2-D surface are:

1. **Volume enclosed, V:** Informs about the enclosed volume within the surface of an object or ionized region.
2. **Surface area, S:**  Informs about the surface area of the object.
3. **Integrated Mean Curvature (C):** Informs about the concavity or convexity of the surface or in other words principal curvature (or radius of curvature) of the surface.
4. **Gaussian Mean Curvature (Euler Characteristics):** Informs about the topological properties of an object.

The Shapefinders are expressed as the ratio of these Minkowski functionals to assess the shape of an object. In 3-D, the three shapefinders are : 

1. **Thickness: T**  = 3V/S
2. **Breadth: B** = S/C
3. **Length: L** = C/4π

These three are the good measures of the extension of an object in 3-dimension. We can further use these shapefinders to determine the morphology of an object by means of these two dimensionless quantities: 

1. **Planarity: P** = (B-T) / (B+T)
2. **Filamentarity: F** = (L-B) / (L+B)

We employ these aforementioned techniques to see how the geometry or topology of the largest ionized region evolves with the redshift. An ionized region can be expressed in terms of its length, breadth and thickness, which are the three Shapefinders mentioned earlier. We show the variation of cross-section and length with the neutral fraction in figure 5. We can observe that the cross-section of the largest ionized region for all reionization scenarios in the left panel remains almost constant with the variation in neutral fraction. Whereas, in the right panel, its length increases several orders of magnitude as the reionization progresses. Hence, one can robustly confirm the fact that as the reionization progresses, the topology of the largest ionized region becomes filamentary, as one can notice in figure 6 where the filamentarity (shown by thick line curves) has a larger value than the planarity (thin line curves) for all reionization scenarios.

<p align="center">
  <img src="../assets/images/hydrogen_distribution_early_universe_aadarsh/image5.png">
</p>
<p align = "center">
Figure 5: This figure illustrates the evolution of the shape of the largest ionized region (LIR) for the five reionization scenarios (excluding the clumping model since this is the only scenario where extreme reionization is considered and hence it’s shapefinders behave differently) near the respective percolation transitions. The left and right panels show the variation of cross-section (estimated by T x B) and the length (L) of the LIR on the y-axis against the neutral fractions on the x-axis. 
</p>

<p align="center">
  <img src="../assets/images/hydrogen_distribution_early_universe_aadarsh/image6.png">
</p>
<p align = "center">
Figure 6: Planarity and filamentarity of the largest ionized region in different models have been compared near the respective percolation transitions. The solid and dashed curves represent the reionization models following inside-out and outside-in reionizations respectively. The thick line curves (solid and dashed) represent the filamentarity and thin line curves represent the planarity of the largest ionized region in different models.
</p>

We also observe that as the reionization progresses, the largest ionized regions in all the scenarios become more multi-connected as their genus (in simple words, for any surface, it represents the number of holes present in the surface and hence informs about the multi-connected regions) increases. Thus, from our findings, we can conclude that at the later stage of reionization, we observe multi-connected filamentary structures for all reionization models. We found that the reionization model, like the clumping model, which follows extreme reionization, can be distinguished or separated quite easily by the Shapefinder technique. We crudely estimate the uncertainties by dividing each original simulation volume into eight smaller sub-volumes followed by estimating the variance of various quantities from these sub-volumes. Our research group at IIT Indore is currently working on noise which we get from the observations and the impact of primary beams on LCS analysis of the 21-cm signal considering the upcoming low-frequency Square Kilometer Array (SKA1-low) observations using a realistic simulations for such observations. 

<hr color="black">
# Conclusion 
<hr color="black">

* We consider the evolution of the largest ionized region by using a statistic called LCS in order to distinguish between the different reionization models.

* We found that LCS for all reionization models before percolation is quite small and hence indistinguishable, but it increases abruptly at the onset of percolation. However, different reionization models percolate at different neutral fractions. Hence, following the evolution of LCS along with the percolation can help to distinguish between different models, and especially the inside-out or out-side- in models.

* We also find that the cross-section of the largest ionized region in all the scenarios (except for the clumping model) remains stable at the percolation transition when the largest ionized region abruptly grows, mostly in terms of its third Shapefinder – ‘length.’ The genus of the largest ionized region also increases as reionization progresses. Hence, multi-connected filamentary structure is observed at a later stage of EoR.

<hr color="black">

---

**Original paper:**
<a href="https://doi.org/10.1088/1475-7516/2022/11/027" target="_blank">Distinguishing reionization models using the largest cluster statistics of the 21-cm maps</a>

**First Author:** Aadarsh Pathak

**Co-authors:** Satadru Bag, Saswata Dasgupta, Suman Majumdar, Rajesh Mondal, Prakash Sarkar

**First author’s Institution:** Department of Astronomy, Astrophysics & Space Engineering, Indian Institute of Technology Indore, Indore, India


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
