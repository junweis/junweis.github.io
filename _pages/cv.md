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
* B.S. in Computer Science, Peking University, 2011
* M.S. in Computer Vision, Western University, 2013
* Ph.D in Human-Computer Interaction, Simon Fraser University, 2019

Work experience
======
* Oct 2019 - Present: HCI Researcher at Huawei HMI Lab
  * Been project manager for 3 VR-related projects that led to publications to top conferences, worked hands-on on development (C# & Java), user experiment design, paper writing, etc.
  * Led a R&D project of designing an input device for remote interaction with large displays, worked on quick prototyping, users studies, and patent filing.
  * Led a R&D project of touchscreen input classification using deep learning (Python & TensorFlow).
  * Applied for 5+ HCI-related patents.

* Sep 2014 - Sep 2019: Research Assistant at VVISE Lab, Simon Fraser University
  * Used Unity engine, C#, and GPU programming to develop two novel interaction techniques for positioning of 3D objects, which profoundly outperformed industry standard approach.
  * Adapted my techniques to virtual reality (VR) with HTC Vive and Oculus Rift. Analyzed different input devices for in VR.
  * Conducted multiple user studies. Used Python, JMP, and SPSS to analyze the data.
  * Presented my work with talks, demos, and posters at multiple academic conferences.

* Aug 2018: Student Volunteer at ACM SIGGRAPH 2018
  * Worked 25 hours on various shifts. Helped attendees with a warm smile.

* Sep 2013 - Aug 2014: Research Assistant at York University
  * Implemented an efficient 3D manipulation technique.
  * Compared text entry performance of different input modes with user studies, with and without auto-correction.

* Sep 2011 - Dec 2012: Research Assistant at Western University
  * Used machine learning and computer vision algorithms to automatically detect and classify epilepsy lesions from digitized MRI images. Achieved 93% accuracy. Programmed with C++ and MATLAB.
  * Classified different human actions from video sequences with machine learning methods using MATLAB.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
  <ul>{% for post in site.patents %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
