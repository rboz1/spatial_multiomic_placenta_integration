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
  <h3 align="center">Spatial + scRNA-seq Integration in Human Placenta</h3>

  <p align="center">
    A comprehensive workflow for scRNA-seq analysis with spatial transcriptomics integration in human placenta.
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

This project provides a comprehensive workflow for spatial + scRNA-seq integration of the human placenta. It includes preprocessing, clustering, annotation, cell-cell communication analysis, pseudotime trajectory inference, and integration of spatial transcriptomics data to visualize cell type distributions in the placenta.

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
   git clone https://github.com/rboz1/placenta_multimodal_transcriptomics.git
   
2. Install required R packages (run inside R)
   ```sh
   install.packages(c("Seurat", "ggplot2", "dplyr", "tidyr", "patchwork"))
   BiocManager::install(c("monocle3", "org.Hs.eg.db", "garnett", "CellChat", "DoubletFinder"))

## Usage
![garnett_type_umap](https://github.com/user-attachments/assets/e5ea6346-3666-4a1a-b58b-dcea5a94b31e)
<img width="896" alt="cellchat" src="https://github.com/user-attachments/assets/5db7d666-bf06-46d9-9301-fe2bb661546a" />
<img width="669" alt="Screenshot 2025-06-09 at 10 27 23 AM" src="https://github.com/user-attachments/assets/de641710-21dc-4e27-a00d-ff5636c17da4" />


<!-- CONTACT -->
## Contact

Rachel - rbozadjian@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: www.linkedin.com/in/rachel-bozadjian-203999109

