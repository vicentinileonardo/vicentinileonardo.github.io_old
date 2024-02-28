---
layout: single
permalink: /projects/distributed_cache
title: "Multi-level Distributed Cache"
categories:
  - Projects
author_profile: true
header:
  overlay_image: /assets/images/back.png
  overlay_filter: 0.5
toc: true
toc_sticky: true
toc_label: "Contents"
---


## Project descriptions

This distributed cache system is designed to support multiple clients that read and write data items stored in a database.
There are **2 levels of cache nodes**, arranged in a tree structure.

The system is implemented leveraging the **Akka** framework: clients, caches, and the main database are all modeled as actors within the Akka actor system.

Clients interact with the system through the cache nodes, which are responsible for processing read and write requests. These requests include basic operations namely **Read** and **Write**, as well as critical variants, **Critical Read** and **Critical Write**, each with specific guarantees.

Additionally, the system considers the possibility of cache crashes and implements a crash detection algorithm based on timeouts.
A**recovery procedure** is also implemented to restore the system to a consistent state after a crash.

The goal of the system is to maintain **eventual consistency** between the database and the cache nodes, even in the presence of crashes.

A web server was created to interact with the system, firing: client operations, cache crashes and recoveries, system consistency check.

## Repository, Report and Demo

{% raw %}
<center>
  <a href="https://github.com/vicentinileonardo/distributed-cache" target="_blank" class="btn"><i class="fa fa-github" style="font-size: 42px;"></i></a>
  <a href="/projects/reports/distributed_cache.pdf" target="_blank" class="btn"><i class="fa fa-file-pdf-o" style="font-size: 42px;"></i></a>
  <a href="https://leonardovicentini.com/dc_demo_to_be_uploaded" target="_blank" class="btn"><i class="fa fa-video-camera" aria-hidden="true" style="font-size: 42px;"></i></a>
</center>
{% endraw %}


## Team and role

Team size: 2

+ Designed **protocols for each operation** (Read, Write, Critical Read, Critical Write) along with the other team member.
+ I proposed and implemented the request and response message mechanisms to correctly **route messages** through the system.
+ I implemented **Critical Write**, **Crash Detection** and **Recovery** algorithms.
+ I proposed and implemented the **web server** to interact with the system.

## Tech stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
