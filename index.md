---
title       : Rapid host switching in generalist *Campylobacter* strains erodes the signal for tracing human infections
subtitle    : NotMolEpi, 23rd October 2015
author      : Bethany Dearlove
job         : University of Cambridge
framework   : revealjs      # {io2012, html5slides, shower, dzslides, ...} 
revealjs    :
  theme     : serif
  center    : "false"
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
license     : 

--- 

<br>
## <b><small>Rapid host switching in generalist *Campylobacter* strains erodes the signal for tracing human infections</small></b>
<br><br>Bethany Dearlove

<div style="font-size:30px">University of Cambridge</div>

<br>
<br>
<span style="font-size:20px"><img src="assets/img/twitter-icon.png" style="background:none; border:none; box-shadow:none; vertical-align:middle"/> &nbsp;<a href="http://www.twitter.com/bethanydearlove" target="_blank" style="vertical-align:middle">@bethanydearlove</a></span>

---

### *Campylobacter*
<br>
* Major cause of bacterial gastroenteritis.
  + Causes severe diarrhoea, vomiting and abdominal pain.
  + Symptoms last 7-10 days.
  + Can lead to more serious diseases such as Guillain-Barr� syndrome and reactive arthritis.

---

### Increasing incidence

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 
<p><a href="https://www.gov.uk/government/publications/campylobacter-cases-2000-to-2012" target="_blank" style="vertical-align:middle; font-size:16px">Data source: HPE</a></p>

---

### Transmission
<br>
* Common transmission routes:
  + Undercooked meat and unpasteurised milk
  + Untreated water
* Human-to human-transmission rare

---


### Zoonosis
<br>
* Range of wild and domestic hosts
* Asymptomatic carriage in the gut microbiota.
* Contamination can occur any time from farmyard to fork.
<br><br>
<div style="text-align:center">
<img src='assets/img/zoonosis.svg' width=50% style="background:none; border:none; box-shadow:none; padding-bottom:0; bottom:0; margin: 0 auto;"/>
<div style="font-size:16px;"><img src='assets/img/CC3.png' style="background:none; border:none; box-shadow:none; vertical-align:bottom"> &nbsp;<a href="http://www.snap2objects.com/2009/06/9-free-vector-animal-farm/" target="_blank" style="vertical-align:middle">Mauricio Duque</a></span></div>
</div>

--- &vertical

### Characterising zoonosis
<br>
* MLST analyses have shown that:
  + Populations in different host species tend to be genetically isolated, despite shared geography.
  + However, some of the most common disease-causing strains are isolated from multiple host species.

***

### Characterising zoonosis

<br>
<div style="text-align:center">
<img src='assets/img/Sheppard2013a.svg' width=100% style="background:none; border:none; box-shadow:none; padding-bottom:0; bottom:0; margin: 0 auto;" onmouseover="this.src='assets/img/Sheppard2013.svg'" onmouseout="assets/img/Sheppard2013a.svg'" />
<div style="font-size:16px;"><a href="http://www.pnas.org/content/110/29/11923" target="_blank" style="vertical-align:middle">Sheppard et al. (2013). PNAS.</a></div>
</div>

---
### Characterising zoonosis
<br>
* Genuine generalists?
* Just the limited resolution of MLST?

---

### Aim: 
<br>
To investigate the utility of whole-genome sequences for
<p>
<ul style="padding-left: 60px;">
<li>estimating the rate of zoonosis</li>
<li>improving the accuracy of source attribution for clinical cases</li>
</ul>
</p>
<p style="float:left; padding-left:60px">in these clonal complexes.</p>

--- 

### Challenges
<br>
* Zoonosis model
* Recombination
* Computation 

--- &vertical

### Modelling zoonosis
<br>
* Phylogeography model (Lemey et al., 2009)
* If adapted in the past, would expect isolates from same host population to cluster together.

***

### Phylogeography
<br>
<div style='float:left;width:48%;' class='centered'>
  <img src='assets/img/phylogeo_zoo.svg' style="background:none; border:none; box-shadow:none;"/>
  <span style="font-size:16px; vertical-align:bottom"><img src='assets/img/CC3.png' style="background:none; border:none; box-shadow:none; vertical-align:bottom"> &nbsp; <a href="http://www.snap2objects.com/2009/06/9-free-vector-animal-farm/" target="_blank" style="vertical-align:middle">Mauricio Duque</a></span>
  <p>Transitions between  hosts</p>
  <p style="font-size:24px">Human = chicken or pig or cattle</p>
</div>
<div style='float:right;width:48%;'>
  <img src='assets/img/phylogeo_nuc.svg' style="background:none; border:none; box-shadow:none;"/>
  <span style="font-size:16px"></span>
  <p>Transitions between nucleotides</p>
  <p style="font-size:24px">N = A or C or G or T</p>

--- 

### Accounting for ancestral recombination
<br>
* Substitution model
  + Relaxed clock
  + Gamma site heterogeneity
* Removal of homoplasies
  + <a href="http://mbio.asm.org/content/5/6/e02158-14.short" target="_blank" style="vertical-align:middle"><font color="black">Hedge and Wilson (2014)</font></a> 

---

### ST-45 complex

<img src='assets/img/ST45-tree.svg' style="background:none; border:none; box-shadow:none;width:68%"/>

---

### ST-21 complex

<img src='assets/img/ST21-tree.svg' style="background:none; border:none; box-shadow:none;width:68%"/>

---

### ST-828 complex

<img src='assets/img/ST828-tree.svg' style="background:none; border:none; box-shadow:none;width:68%"/>

---

### Parameter estimates
<br>
Estimated one jump every...
* 1.6 years in ST-21
* 1.8 years in ST-45
* 12 years in ST-828

---

### Parameter estimates
<br>
<img src='assets/img/table.svg' style="background:none; border:none; box-shadow:none;"/>

---

### Source of clinical cases

<img src='assets/img/clinical-source.svg' style="background:none; border:none; box-shadow:none; width:100%"/>

---

### Summary
<br>
* Isolates from different host species are often more closely related than those isolated from the same host species. 

* As expected from previous MLST studies, much ancestry is inferred to occur within chickens.
  + MRCA of all three complexes. 

---

### Summary
<br>
* Cannot properly attribute at the individual level in these complexes due to weak host signal.
  + Most likely due to generalist nature of these complexes, and uncertainty reflects make up of host population.
  + Signal could be drowned out or in accessory genome.

* Evidence of potential for whole genomes 
  + BUT the extra information from WGS does not overcome the need for detailed sampling.

---

### Acknowledgements
<br>
Daniel Wilson

Samuel Sheppard

Ben Pascoe

Guillaume Meric

Alison Cody

Simon Frost


<a href='http://www.nature.com/ismej/journal/vaop/ncurrent/abs/ismej2015149a.html' border='0'><img src='https://chart.googleapis.com/chart?cht=qr&chl=http%3A%2F%2Fwww.nature.com%2Fismej%2Fjournal%2Fvaop%2Fncurrent%2Fabs%2Fismej2015149a.html&chs=150x150&choe=UTF-8&chld=L|2' alt='' target="_blank" style="width:130px"></a>

---

