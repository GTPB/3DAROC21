---
layout: page
title: Learning Objectives and Course Pre-requesites
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial
  isPartOf:
      url: "https://gtpb.github.io/3DAROC18/"
      name: "3DAROC18 - 3C-based data analysis and 3D reconstruction of chromatin folding"
---

# Learning Objetives

In this course, participants will learn to use TADbit, a software designed and developed to manage all the dimensionalities of the Hi-C data:

 - 1D - Map paired-end sequences to generate Hi-C interaction matrices
 - 2D - Normalize matrices and identify constitutive domains (compartments, TADs)
 - 3D - Generate populations of model structures which reproduce the Hi-C interaction matrices
 - 4D - Compare samples at different time points

Participants can bring specific biological questions and/or their own 3C data to analyze during the course. At the end of the course, participants will be familiar with the TADbit software, and will be able to fully analyze Hi-C data.
*__Note__: Although the TADbit software is central in this course, alternative software will be discussed for each part of the analysis.*

<br/>

# Course Pre-requisites

Recommended Linux and basic Python programming skills, graduate level in Life Sciences.
All hands-on will be given at 2 levels of computational expertise (command-line tool and python scripting).

<br/>

## TADbit API

This tutorial is associated with a __specific version of TADbit__, if you wish to reproduce exactly the results in the notebooks you should use the version of TADbit tagged `3DAROC_2020`.

To install this version do:

    git clone https://github.com/3DGenomes/TADbit
    cd tadbit
    git checkout tags/3DAROC_2020
    sudo python setup.py install

<br/>

## TADbit tools

Most of the tasks of the "core pipeline" can be tunned directly from command line (without any python), using [TADbit tool](/TADbit_tools). Have a look to the commands, and the metadata of the results.

<br/>

## Virtual research environment


<img align="right" src="./images/MUG_logo.jpg" width="160">

With small datasets TADbit core pipeline can be runned through a new Virtual Research Environment ([VRE](https://vre.multiscalegenomics.eu/workspace/)), hosted by the [MuG project](https://www.multiscalegenomics.eu/).

This might also be the best place to try TADkit for visualizing genomes in 3D together with interactions matrices and any other genomic track.

<br/>

### Back

Back to [main page](../index.md).
