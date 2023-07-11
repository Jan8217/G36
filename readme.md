<a name="readme-top"></a>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Computer Vision Challenge--G36</h3>

  <p align="center">
    The description file for the 36 groups in the Challenge of Tum's 2023 computer Vision lecture
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#matlab-toolbox">Matlab toolbox</a></li>
    <li><a href="#gUI-application">GUI application</a></li>
    <li><a href="#global-sfm">Global SFM</a></li>
    <li><a href="#contributing">Contributing</a></li>    
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Our program can perform 3D reconstruction on the input series of pictures, and can also measure the distance and size of the reconstructed images. We utilized the 3D reconstruction by the global sfm algorithm.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Matlab toolbox -->
## Matlab toolbox

1. Image Proccessing Toolbox
2. Computer Vision Toolbox

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GUI application -->
## GUI application

![GUI of G36](https://github.com/Jan8217/G36/blob/master/images/G36_GUI.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Global SFM -->
## Global SFM

Global sfm can obtain all camera poses and scene point structures at one time. It usually obtains the poses of all cameras first, and then obtains the scene points through triangulation.

The camera pose solution is also divided into two steps: the first step is to solve the global rotation, and the second step is to solve the global translation vector according to the global rotation. The solution of global rotation is the core key issue of camera pose estimation.

The global sfm only needs to perform Bundle Adjustment once at the end, so it is more efficient, but its robustness is poor, and it is easy to be affected by outlier and cause reconstruction failure

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Dong Liu, Zebin Jiang, Bingfeng Li, Zhaokun Yan

<p align="right">(<a href="#readme-top">back to top</a>)</p>
