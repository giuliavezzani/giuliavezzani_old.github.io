---
layout: secondary
title: Memory unscented particle filter for 6-DOF tactile localization
author: G. Vezzani, U.Pattacini, G. Battistelli, L. Chisci, and L. Natale
---


## Abstract
This paper addresses 6-DOF (degree-of-freedom) tactile localization, i.e. the pose estimation of tridimensional
objects given tactile measurements. This estimation problem is fundamental for the operation of autonomous robots that are
often required to manipulate and grasp objects whose pose is a-priori unknown. The nature of tactile measurements, the strict
time requirements for real-time operation and the multimodality of the involved probability distributions pose remarkable
challenges and call for advanced nonlinear filtering techniques. Following a Bayesian approach, this paper proposes a novel
and effective algorithm, named Memory Unscented Particle Filter (MUPF), which solves 6-DOF localization recursively in real-time
by only exploiting contact point measurements. MUPF combines a modified particle filter that incorporates a sliding memory of
past measurements to better handle multimodal distributions, along with the unscented Kalman filter that moves the particles
towards regions of the search space that are more likely with the measurements. The performance of the proposed MUPF
algorithm has been assessed both in simulation and on a real robotic system equipped with tactile sensors (i.e., the iCub
humanoid robot). The experiments show that the algorithm provides accurate and reliable localization even with a low number of particles and, hence, is compatible with real-time requirements.

This work has been published to IEEE Transaction on Robotics, vol. 33 no. 5 pag. 1139-1155, October 2017.
The manuscript is available [on arxiv:1607.02757](https://arxiv.org/pdf/1607.02757.pdf).

The code I developed is available on _github_ <a href="https://doi.org/10.5281/zenodo.163860"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.163860.svg" style="vertical-align:middle;" alt="DOI"></a>.

<p align="center">
<img src="https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/hand.jpg">
</p>


[Home page](./)
