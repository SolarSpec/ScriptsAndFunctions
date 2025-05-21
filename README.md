<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/SolarSpec/TRPL_Photos">
    <img src="TRPL_Photos/logo.png" alt="SolarSpec" width="160" height="120">
  </a>

<h3 align="center">TRPL Fitting Tool</h3>

  <p align="center">
    A MATLAB application for Time-Resolved Photoluminescence (TRPL) data analysis and fitting
    <br />
    <a href="https://github.com/SolarSpec/TRPL_Photos"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SolarSpec/TRPL_Photos">View Demo</a>
    ·
    <a href="https://github.com/SolarSpec/TRPL_Photos/issues">Report Bug</a>
    ·
    <a href="https://github.com/SolarSpec/TRPL_Photos/issues">Request Feature</a>
  </p>
</div>

<!-- FEATURED SCREENSHOT -->
[![TRPL Fitting Tool Screenshot][product-screenshot]](https://solarspec.ok.ubc.ca/)

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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
# About The Project

This MATLAB application streamlines the process of analyzing Time-Resolved Photoluminescence (TRPL) data by providing a comprehensive tool for:
- Loading instrument response (IRF) and decay data
- Selecting fitting parameters
- Running multi-start deconvolution fits against various kinetic models
- Visualizing results
- Exporting both plots and numerical outputs

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [MATLAB](https://www.mathworks.com/products/matlab.html)
* [Parallel Computing Toolbox](https://www.mathworks.com/products/parallel-computing.html)
* [Optimization Toolbox](https://www.mathworks.com/products/optimization.html)
<!-- * [Image Processing Toolbox](https://www.mathworks.com/help/images/)
* [Curve Fitting Toolbox](https://www.mathworks.com/help/curvefit/) -->

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
# Getting Started

To begin using this app, follow these simple steps to ensure you have the necessary prerequisites and proper installation.

### Prerequisites

1. MATLAB (R2020b or newer recommended)  
2. Required MATLAB Toolboxes:  
   - Parallel Computing Toolbox  
   - Optimization Toolbox  
   - Statistics and Machine Learning Toolbox  

### Installation

1. Clone the repository  
   ```sh
   git clone https://github.com/SolarSpec/TRPL_Photos.git
