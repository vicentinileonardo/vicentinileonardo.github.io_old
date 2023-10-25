---
layout: single
permalink: /projects/daytrip
title: "Daytrip: service-oriented web app for daytrips suggestions in Italy"
categories:
  - Project
author_profile: true
header:
  overlay_image: /assets/images/back.png
  overlay_filter: 0.5
toc: true
toc_sticky: true
toc_label: "Contents"
---

<!-- ### [ Feb. 2023 - Mar. 2023 ] -->

## Project description

The project aims to create a web application that suggests daytrip destinations in Italy based on weather conditions, travel time, and other indicators. A service-oriented architecture was used to build decoupled services that can be expanded and modified independently.

## Repository, Report and Demo

{% raw %}
<center>
  <a href="https://github.com/vicentinileonardo/daytrip" target="_blank" class="btn"><i class="fa fa-github" style="font-size: 42px;"></i></a>
  <a href="/project_reports/daytrip.pdf" target="_blank" class="btn"><i class="fa fa-file-pdf-o" style="font-size: 42px;"></i></a>
  <a href="https://drive.google.com/file/d/1k0KBPMmt-DaVHthZ1S2wKzhBID33X0ad/view?usp=sharing" target="_blank" class="btn"><i class="fa fa-video-camera" aria-hidden="true" style="font-size: 42px;"></i></a>
</center>
{% endraw %}

## Team and role

Team size: 2 people

+ I was responsible for the design and implementation of many of the core services, spanning from data layer to business logic and process centric services. <br>
+ I implemented services both in **Node.js** and **Python** to show the flexibility of this kind of architecture. <br>
+ I was responsible for the configuration of the **Docker** images and the **Docker Compose** file. <br>
+ I proposed and implemented a workaround for a Docker issue that was preventing the correct execution of a service leveraging **matplotlib** Python library: the service is running in a serverless fashion, leveraging **AWS Lambda** and **AWS API Gateway**. <br>

## Tech stack

![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)

![NGINX](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) 
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 
![ExpressJS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)