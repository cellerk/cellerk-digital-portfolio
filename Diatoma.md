# Diatoma Biofilm Modeling

The aim of my MSc thesis project was to explain by numerical modeling how different colony architectures of Diatoma microbial streamers are formed in rivers. I developed a mass-and-spring mechanical model of filament formation, coupling individual-based models for biofilm formation, including microbial growth, attachment and detachment, with river hydrodynamics

```{figure} ./img/Diatoma.jpg  
---
height: 500 px
name: Diatoma_figure
---
```

Given a hydrodynamic microenvironment characteristic for the river bottom crest (ie. where water flows quickly and unidirectionally) and the trough (ie. where water is more turbulent), the proposed model provided a reasonably realistic picture of the Diatoma chain architecture and behaviour (see videos below).

<video width="560" height="315" controls autoplay>
  <source src="_static/Valley_3.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

In the trough, zigzagged Diatoma chains developed rapidly over two days and moved following the flow patterns of water, becoming entangled with neighbouring chains. Model simulations suggest that long chains with a potentially larger interaction radius had higher chance to become entangled and to form prominent arch-like structures as those observed in natural biofilms.


<video width="560" height="315" controls autoplay>
  <source src="_static/Ridge_3.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

At the crest, unidirectional and faster flow bent growing Diatoma chains over and pulled them in one preferential direction. The flow environment prevented the development of an arch formation from the entanglement of neighbouring chains and ultimately the dome-like structures. Generally, interactions between chains were reduced compared to the trough, though inevitably, as chains grew longer, entanglement and sticking did occur to form elongated dreadlock-like streamers that oscillated in the flow.


For more information, see my publication: <b>Celler, K.</b>, Hödl, I., Simone, A., Battin, T., Picioreanu, C. A mass-spring model unveils the morphogenesis of phototrophic Diatoma biofilms. Sci. Rep. 4: 3649. 2014. https://www.nature.com/articles/srep03649
