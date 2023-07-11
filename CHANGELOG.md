<a name="readme-top"></a>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Computer Vision Challenge--G36</h3>

  <p align="center">
    Our program can perform 3D reconstruction on the input series of pictures, and can also measure the distance and size of the reconstructed images. We utilized the 3D reconstruction by the global sfm algorithm.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#Matlab toolbox">Matlab toolbox</a></li>
    <li><a href="#GUI application">GUI application</a></li>
    <li><a href="#Global sfm">Global sfm</a></li>
    <li><a href="#contributing">Contributing</a></li>    
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description`

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Matlab toolbox -->
## Matlab toolbox

1. Symbolic Math Toolbox
2. Image Proccessing Toolbox
3. Computer Vision Toolbox

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GUI application -->
## GUI application

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Global sfm -->
## Global sfm

Global sfm can obtain all camera poses and scene point structures at one time. It usually obtains the poses of all cameras first, and then obtains the scene points through triangulation.

The camera pose solution is also divided into two steps: the first step is to solve the global rotation, and the second step is to solve the global translation vector according to the global rotation. The solution of global rotation is the core key issue of camera pose estimation.

The global sfm only needs to perform Bundle Adjustment once at the end, so it is more efficient, but its robustness is poor, and it is easy to be affected by outlier and cause reconstruction failure

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Dong Liu, Zebin Jiang, Bingfeng Li, Zhaokun Yan

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge

