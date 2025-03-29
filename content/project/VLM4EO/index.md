---
title: VLM4EO
summary: Urban Monitoring through Earth Observation

draft: false
featured: false
tags:
  - Deep Learning


date: 2025-03-29T09:07:29.350Z
---

<div class=article-style itemprop=articleBody>

<b><h2 id=geourban-ai-tool>GeoUrban-AI Tool</h2></b>
<p>GeoUrban-AI powered <a href="http://geoai.cnrs.edu.lb/urbanmodels/" target="_blank">[Tool]</a> allows to autonomously extract buildings' footprints from satellite/aerial imagery. The aim is to make our applied research findings accessible to a larger community. Though it is not common to develop such a web-based tool for a team that is mainly involved with research rather than product development; We believe this demo would help us target a larger audience and would open up new horizons for the GEOAI group.</p>

<img src="./lebanonmap.png">

<b><h2 id=national-urban-map>Automated National Urban Map Extraction</h2></b>
<p>Developing countries usually lack the proper governance means to generate and regularly update a national rooftop map. Using traditional photogrammetry and surveying methods to produce buildings map at the federal level is costly and time-consuming. Relying on earth observation and deep learning methods, we aim in this project to bridge this gap and propose a pipeline to autonomously produce national urban maps. We detail all engineering steps to replicate this work and ensure highly accurate results in dense and slum areas witnessed in regions that lack proper urban planning in the Global South. We applied a case study of the proposed pipeline to Lebanon and successfully produced the first comprehensive national building footprint map with approximately 1 Million units with an 84% accuracy. The proposed architecture relies on advanced augmentation techniques to overcome dataset scarcity, which is often the case in developing countries.

<a href="https://geogroup.ai/catalogue/" target="_blank">[Map]</a> encompases  ~1 MM urban units with an 84% accuracy. When you ZOOM IN, the dots on the map refer to the centroids of each building at a specific geographical location <a href="https://geogroup.ai/publication/2024igarss_nationalurbanmap/2024IGARSS_NationalUrbanMap.pdf">[Paper]</a></p>.

<img src="./solar.png">

<b><h2 id=solar-potential>Solar Potential Map for Lebanon</h2></b>
<p>Estimating the solar potential of buildings' rooftops at a large scale is a fundamental step for every country to utilize its solar power efficiently. However, such estimation becomes time-consuming and costly if done through on-site measurements. This project uses deep learning-based multi-class instance segmentation to extract buildings' footprints from satellite images. We propose a photovoltaic panels placement algorithm to estimate the solar potential of every rooftop, which results in Lebanon's first buildings' solar potential map. We report average and total solar potential per district and localize regions corresponding to the highest solar potential yield <a href="https://geogroup.ai/publication/2022SolarMapLebanon/">[Paper]</a>.</p>

</div>
