---
layout: single
permalink: /projects/convex_hull_parallel_solver
title: "Convex hull parallel solver"
author_profile: true
header:
  overlay_image: /assets/images/back.png
  overlay_filter: 0.5
toc: true
toc_sticky: true
toc_label: "Contents"
---

<!-- ### [ Oct. 2022 - Dec 2022 ] -->

## Project description

Parallel implementation of the Divide and Conquer algorithm for the convex hull problem. The implementation is based on the **C** programming language and leverages **MPI** and **OpenMP** libraries. The solution was tested on a **High-Performance Computing cluster** with specific PBS configuration files.

## Repository and Report

{% raw %}
<center>
  <a href="https://github.com/vicentinileonardo/parallel-convex-hull" target="_blank" class="btn"><i class="fa fa-github" style="font-size: 42px;"></i></a>
  <a href="/projects/reports/parallel_convex_hull_solver.pdf" target="_blank" class="btn"><i class="fa fa-file-pdf-o" style="font-size: 42px;"></i></a>
</center>
{% endraw %}

## Team and role

Team size: 2 people

+ The team designed the general implementation strategy together. <br>
+ I contributed in part of the core implementation and debugging of the algorithm. <br>
+ I was responsible for the implementation fo the *OpenMP* section of the project. <br>
+ I investigated various PBS configurations for the HPC cluster and proposed the final one. <br>

## Tech stack
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
