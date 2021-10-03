---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The name of the course
       # "description" -> Short description of the course
  name: "3DAROC21 - 3C-based data analysis and 3D reconstruction of chromatin folding"
  description: "Training Material focused in 3C-Data Analysis and 3D Chromatin Folding."

  # Keywords -> Consult EDAM:Topic
  keywords:  "http://www.ebi.ac.uk/efo/EFO_0007693"

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "Marc A. Martí-Renom"
    - "@type": Person
      name: "Marco Di Stefano"
    - "@type": Person
      name: "David Castillo"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/3DAROC21/"
---

![](./assets/material/Entry_Image.jpg)

## Course Description

3C-based methods, such as Hi-C, produce a huge amount of raw data as pairs of DNA reads that are in close spatial proximity in the cell nucleus. Overall, those interaction matrices have been used to study how the genome folds within the nucleus, which is one of the most fascinating problems in modern biology. The rigorous analysis of those paired-reads using computational tools has been essential to fully exploit the experimental technique, and to study how the genome is folded in space. Currently, there is a clear expansion on the wealth of data on genome structure with the availability of many datasets of Hi-C experiments down to 1Kb resolution (see for example: http://hic.umassmed.edu/welcome/welcome.php ; http://promoter.bx.psu.edu/hi-c/view.php or http://www.aidenlab.org/data.html).

In this course, participants will learn to use **TADbit**, a software designed and developed to manage all dimensionalities of the Hi-C data:
* 1D - Map paired-end sequences to generate Hi-C interaction matrices
* 2D - Normalize matrices and identify constitutive domains (TADs, compartments)
* 3D - Generate populations of structures which satisfy the Hi-C interaction matrices
* 4D - Compare samples at different time points

Participants can bring specific biological questions and/or their own 3C-based data to analyze during the course. At the end of the course, participants will be familiar with the TADbit software and will be able to fully analyze Hi-C data. Although the TADbit software is central in this course, alternative software will be discussed for each part of the analysis.

## Target Audience

The course design is oriented towards experimental researchers and bioinformaticians at the graduate and post-graduate levels. The last edition of this course was attended by people with different backgrounds and interested in the genome organization.

It is likely that the participants to this course aim at getting involved in generating Hi-C data for chromosome structure determination or that they just want to be able to correctly interpret and analyse publicly available data.

## Detailed Program

All the datasets used for this training course is available throughout the documentation.


<table>
  <tbody>
    <tr>
      <th>Days</th>
      <th>Lectures (pdf)</th>
      <th>Core pipeline (notebooks)</th>
    </tr>
    <tr>
     <td><strong>Day 1</strong></td>
     <td>
       <ul>
        <li> <a href="./assets/material/Presentations/Day1/20211004_01_Welcome.pdf">Welcome and introduction</a></li>
        <li> <a href="./assets/material//Presentations/Day1/20211004_02_introduction_to_structure_determination.pdf">Overview on structure determination</a></li>
        <li> <a href="./assets/material/Presentations/Day1/20211004_03_3D-genomes_overview.pdf">Overview of 3D genomes</a></li>
        <li> <a href="./assets/material/Presentations/Day1/20211004_04_Live_introduction_to_linux_and_environment.pdf">Live Introduction to Linux and working environment</a></li>
        <li> <a href="./assets/material/Presentations/Day1/20211004_05_Intro_TADbit.pdf">Introduction to TADbit and data handling for 3C-based experiments</a></li>
        <li> <a href="./assets/material/Presentations/Day1/20211004_05_From_raw_data_to_Hi-C_contact_matrices.pdf">From raw data to Hi-C contact matrices</a></li>
       </ul>
     </td>
     <td>
    </td>
   </tr>
    <tr>
     <td><strong>Day 2</strong></td>
     <td>
       <ul>
        <li> <a href="./assets/material/Presentations/Day2/20211005_01_Chromatin_and_3Cs.pdf">Chromatin structure and 3C data</a></li>
        <li> <a href="./assets/material/Presentations/Day2/20211005_02_TADbit.pdf">Integrative modeling applied to chromatin with TADbit</a></li>
        <li> <a href="./assets/material/Presentations/Day2/20211005_03_Hi-C_contact_matrices_filtering.pdf">Hi-C contact matrices: filtering</a></li>
        <li> <a href="./assets/material/Presentations/Day2/20211005_04_Applications(I)_TAD_hormone.pdf">Biological applications I: TAD response to hormone treatment)</a></li>
        <li> <a href="./assets/material/Presentations/Day2/20211005_05_Applications(II)_SOX2Dynamics.pdf">Biological applications II: SOX2 gene activation dynamics)</a></li>
       </ul>
     </td>
     <td>
       <ul>
       </ul>
    </td>
   </tr>
   <tr>
     <td><strong>Day 3</strong></td>
     <td>
       <ul>
        <li> <a href="./assets/material/Presentations/Day3/20211006_01_Comparison_between_experiments.pdf">Comparison between experiments</a></li>
        <li> <a href="./assets/material/Presentations/Day3/20211006_03_Applications(III)_IMGR.pdf">Biological applications: III: IMGR, combining image and Hi-C data for modeling)</a></li>
       </ul>
     </td>
     <td>

    </td>

   </tr>

  </tbody>
</table>


---

### [Learning Objectives and Course Pre-requisites](pages/objectives_prerequisites.md) (link)

### [Instructors](pages/instructors.md) (link)

---

The source for this course webpage is [in github](https://github.com/GTPB/3DAROC20).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">3DAROC20</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
