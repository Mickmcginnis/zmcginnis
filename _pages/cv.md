---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
### B.S. in Engineering: Computing, Olin College of Engineering, 2023
GPA: 3.73 / 4.0
  * Four-year 50% tuition Olin Merit Scholarship recipient
  * Xilinx Empowering Women in Technology $5,000 Merit Scholarship recipient

Research and Work experience
======
### Kyruus Health
Data Analyst | August 2023 - Present
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

### OCCaM Lab @ Olin College of Engineering
Research in the lab of [Paul Ruvolo, Ph.D.](http://occam.olin.edu/) | Summer 2023
  * Research on image-based localization techniques for an app to enhance indoor navigation for blind and low-vision users
  * Used Niantic's [Accelerated Coordinate Encoding (ACE)](https://nianticlabs.github.io/ace/) model with Pytorch, Python, Apple ARKit, and Swift to implement a localization solution to replace [Google Cloud Anchors](https://developers.google.com/ar/develop/cloud-anchors) for accessibility iPhone app
  * Research and codesign with blind and low-vision users

### Nugent Lab @ Olin College of Engineering
Research in the lab of [Carrie Nugent, Ph.D.](https://www.crnugent.com/research) | Fall 2022 - Spring 2023
  * Research on asteroids and comets discovery and detection through analysis of high definition images of the sky taken in the early 2000s

### Simplisafe
AI Research Intern | Summer 2022
* Tested and compared performance of several deep learning object and text detectors, then integrated best performing detectors into the existing codebase using S3 and EC2
* Fine tuned a model to detect logos in images

### The MITRE Corporation
Advanced Technologies Intern | June 2020 - November 2021
* Created client-facing information dashboard to showcase data using Flask, MySQL, S3, and Python
* Trained two separate image classifiers using tensorflow and integrated them into the existing data pipeline

Papers
======
  <ul>{% for post in site.papers reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>