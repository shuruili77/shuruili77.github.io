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
* Ph.D in Electrical and Computer Engineering, UCLA, 2019-2024 (expected)
* M.Eng. (B.Eng. integrated) in Electrical and Electronic Engineering with Management, Imperial College London, 2015-2019, First Class Honours



Research experience
======
### Graduate Student Researcher, NanoCAD Lab, UCLA, 2019-present
#### Architecture design of photonic neural network accelerators, ongoing
  *	Work on system scaling analysis and parallelization strategies for free-space 4F optical neural network accelerators
  *	Design efficient architectures for on-chip photonic neural network accelerators with co-optimization of software and hardware (dataflow, reuse scheme, memory hierarchy, etc.)
  *	Develop custom performance simulators to estimate the system performance of different configurations
  *	Develop custom training functions with integrated hardware simulation models for different types of photonic neural networks

#### Deep learning on microcontrollers, completed
  *	Proposed a software framework to compress and accelerate arbitrary precision neural networks on resource-constrained microcontrollers based on weight sharing, bit-serial computation, and lookup tables
  *	Designed and implemented a microcontroller runtime library for the proposed framework
  *	Implemented custom PyTorch functions for training neural networks with various weight-sharing techniques


#### Low-power deep learning accelerator design, completed
  * Proposed hardware accelerator architecture based on systolic array for low-power neural network inference that leverages bit-level sparsity
  *	Analyzed various trade-off between system performance and power efficiency
  *	Co-designed the software and hardware to achieve optimal efficiency-accuracy trade-off
  *	Implemented custom PyTorch functions for training neural networks with bit-level sparsity

### Summer Researcher, Custom Computing Group, Imperial College London, summer 2017
*	Conducted research on accelerating quantum chemistry simulation with FPGA-based data flow engines 
*	Wrote C codes to parallelize Monte Carlo simulation on data flow engines 
*	Conducted performance bottleneck analysis and optimized the algorithm accordingly

Work experience
======
### Summer Intern, Qualcomm, summer 2020
* Participated in a neural network accelerator design project and worked on the middleware design and development
* Developed a complete microcontroller program to control hardware modules and handle various execution modes
* Designed control flow to handle communication and synchronization between different hardware modules and guarantee correct execution sequence

Skills
======
*	Programming languages: Python, C/C++, Verilog HDL, JAVA, assembly language, PHP
* Software: PyTorch, Tensorflow, ModelSim, Cadence Genus, Cadence Innovus, Cadence Virtuoso, MATLAB, Android Studio, MS Office
* Languages: English (fluent), Mandarin (native)

Service and leadership
======
### Organizer, UCLA Computer Engineering Bootcamp, summer 2022
*	Organized a comprehensive 5-day bootcamp program for incoming UCLA computer engineering freshmen, aimed at equipping them with the necessary skills and knowledge to excel in their future studies and campus life
*	Developed and curated structured modules for the bootcamp and find suitable instructors to deliver high-quality instruction across all modules
*	Taught the Machine Learning module and provided students with hands-on lab sessions to practice their skills

### Instructor, Los Angeles Compuyting Circle (LACC), summer 2021, summer 2022
*	Volunteered at LACC for two consecutive years, which is a free summer program for high school students with the objective of engaging and mentoring younger students for careers in computing and engineering
*	Taught the Machine Learning and Artificial Intelligence Module and provided students with hands-on lab sessions to practice their skills


Publications
======
  <ul>{% for post in site.publications %}
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
  

