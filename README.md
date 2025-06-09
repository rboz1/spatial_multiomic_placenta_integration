<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
  <h3 align="center">Spatial Multiomic Integration in Human Placenta</h3>

  <p align="center">
    A comprehensive workflow for spatial multiomic integration of the human placenta.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project



<p align="right">(<a href="#readme-top">back to top</a>)</p>

This project provides a comprehensive workflow for spatial multiomic integration of the human placenta. It includes preprocessing, clustering, annotation, cell-cell communication analysis, pseudotime trajectory inference, and integration of spatial transcriptomics data to visualize cell type distributions in the placenta.

### Built With

- R 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
* R (version 4.0 or higher)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/rboz1/spatial_multiomic_placenta_integration.git
   
2. Install required R packages (run inside R)
   ```sh
   install.packages(c("Seurat", "ggplot2", "dplyr", "tidyr", "patchwork"))
   BiocManager::install(c("monocle3", "org.Hs.eg.db", "garnett", "CellChat", "DoubletFinder"))

<!-- CONTACT -->
## Contact

Rachel - rbozadjian@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: www.linkedin.com/in/rachel-bozadjian-203999109

