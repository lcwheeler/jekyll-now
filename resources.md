---
layout: page
title: Resources
permalink: /resources/
---

This page contains information on software and other resources that I have had a hand in producing. All of these materials are free and open source.

## Scientific software tools
<hr><hr>

#### Enzo

Enzo is a simple python library that allows mathematical models of metabolic pathways to be evolved between phenotypic states. I developed this approach for a [paper](https://www.biorxiv.org/content/early/2019/01/03/511089) on the simulated evolution of the anthocyanin biosynthesis pathway. Enzo is a wrapper for the [Tellurium](http://tellurium.analogmachine.org/) environment, which is an excellent tool for developing reproducible systems biology simulations in Python. Enzo is a work in progress and I am planning to add additional functionality as time goes by. 

*To install or contribute to enzo, go to the [github repo](https://github.com/lcwheeler/enzo).*


#### Orbweaver

Orbweaver is a pet project that is still a work in progress. It is a Python library designed to analyze gene co-expression relationships. Currently the functionality is limited, but it contains some useful tools for calculating distance matrices and generating network data structures.

*To install or contribute to orbweaver, go to the [github repo](https://github.com/lcwheeler/orbweaver).*


#### Ambigauss

Ambigauss is another pet project and another work in progress, developed by the members of the [Beer and Theory Society](https://github.com/BeerTheorySociety). It's a Python library designed specifically for analyzing spectral datasets. It includes tools for finding peaks, fitting various spectral shapes to data, and simulating data. 

*To install or contribute to ambigauss, go to the [github repo](https://github.com/BeerTheorySociety/ambigauss).*


## Educational materials
<hr><hr>

#### Python for Scientists

Python is a very useful programming language that has become increasingly popular in the scientifc community in recent years. 
My friends and I found that there was a lack of a single centralized guide to help scientists set up a working Python environment. 
So, we decided to do something about it! We created a web page using "readthedocs" that walks through setting up a useful Python ecosystem and also contains brief overviews of popular scientific packages and visualization tools. 

*Follow this link to reach the guide:* 

[Python for Scientists](https://python-for-scientists.readthedocs.io/en/latest/#)


*To make a contribution to the guide:* 

Fork and clone the master [github repo](https://github.com/Zsailer/python-for-scientists)


#### Pyway
Emergent properties arise from interactions between multiple agents in systems with simple rules. Think of a school of fish or a flock of starlings. One of the most famous computational examples is the simulated world of Conway's game of life. By following just three simple rules that determine the behavior of individual agents in the model, beautifully complex and interesting patterns emerge. I created a simple Python package that contains all the tools necessary to simulate Conway's game of life on a grid of any size, using either random or user-defined initital conditions. Pyway is meant as a teaching tool. It simplifies the initialization of the game and allows visualizations to be made of game trajectories. 

*You can install pyway from it's [github repo](https://github.com/lcwheeler/pyway).* 


