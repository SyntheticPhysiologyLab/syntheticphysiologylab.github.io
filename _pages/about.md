---
permalink: /
title: "RESEARCH"
excerpt: "About us"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align:left; vertical-align: middle border-left: 500px">
<h2><a href="{{site.url}}/news"><span style="color:gray">Latest news:</span></a></h2>
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted limit:5%}
<li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
<br>
</div>
<br>

## GENETIC ENGINEERING OF HUMAN CELLS 

We use genetic engineering and genome editing techniques to introduce fluorescent structural and functional sensors in human cell lines and human induced pluripotent stem cells.

![Cells video](/images/cells_video.gif){: width="100%" }


## COMPUTATIONAL MODELING

We use both continuous and discrete modeling frameworks to study cell and tissue mechanobiology.

![SEM video](/images/sem_video.gif){: width="100%" }


## ENGINEERING OF CELL CULTURE PLATFORMS

We use micro/nano-fabrication and biological self-assembly to create high-throughput, high-content biomimetic platforms to study human development, health, and disease in-vitro.

![Engineered cells video](/images/engineered_cells_video.gif){: width="100%" }


# FUNDED PROJECTS

1. Synthetic Matrix Biology: Designer matrices to program healthy and diseased myocardial morphogenesis<br>
   ERC Starting grant<br>
   2020-2025<br>
   ![ERC](/images/LOGO_ERC-FLAG_EU_.jpg){: width="250" }
   
2. All-Optical Engineering of Human Tissue Models for Ultra High-Throughput Drug Screening<br>
   MUR FARE<br>
   2022-2027<br>
   ![mUR](/images/logo-miur.png){: width="250" }
   
3. highLight: A competence center for bio/nano-sustainability<br>
   Regione Lombardia<br>
   2021-2023<br>
   ![RL](/images/RegioneLombardia.png){: width="250" }
   
4. Engineered in-vitro models of cardiometabolic diseases to screen RNA-based therapeutics <br>
   EU/MUR PNRR<br>
   2022-2025<br>
   ![PNRR](/images/PNRR-Next-Generation-EU-1024x576.jpg){: width="250" }

5. RESET. REsolving infections by modulating SEnescenT macrophages (in collaboration with the Infection Dynamics Lab of Loris Rizzello at UNIMI)
<br>
   2022PL44LM<br>
   2022-2027<br>
   ![mUR](/images/logo-miur.png){: width="250" }
