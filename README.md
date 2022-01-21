<div id="top"></div>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MahmoudMTaha/YoloV4-Weapons-Detection">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">YoloV4 weapons Detection</h3>

  <p align="center">
    <h5>automatic weapon detection software using a convolutional neural network (CNN) based on pre-trained You Only Look Once (YOLO) model.</h5>
    <h5> The software detect three types of weapons : knives, pistols and rifles </h5>
    <h5> deployed locally using Flask  </h5>
    <br />
    <a href="https://drive.google.com/file/d/1TrwTL-a7DqVCJxuAkmjCt1IDG5c_JLHN/view?usp=sharing"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://www.youtube.com/watch?v=zmNJViugLeo">View Demo</a>

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
<!--     </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li> -->
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://youtu.be/zmNJViugLeo)

The first and supreme goal of science is to serve man-kind, and since the 
security and safety of man-kind is one of the first and most important 
priorities, we worked on “Weapon Dectection Sysyem” depending on artificial 
intelligence and deep learning technologies can detect weapons such as: 
pistols, knifes and rifles then sending alert mails with the detected weapon 
for the authorized department such as: police department, security man, ... 
etc.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [YoloV4](https://arxiv.org/abs/2004.10934)
* [Darknet](https://github.com/pjreddie/darknet)
* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [FFmpeg](https://www.ffmpeg.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple steps.

### Prerequisites
To be able to run the system you have to install the following Prerequisites

* Windows
* Github (Desktop/Bash)
* [OpenCV](https://opencv.org/releases/)
* [Visual Studio community 2019](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community)
* [CMake GUI: Windows win64-x64](https://cmake.org/download/)
* [Cuda](https://developer.nvidia.com/cuda-downloads)
* [cuDNN](https://developer.nvidia.com/cudnn)

* Darknet
  ```sh
  git clone https://github.com/AlexeyAB/darknet
  ```
* [FFmpeg](https://www.ffmpeg.org/)
* Flask
   ```sh
  pip install Flask
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/MahmoudMTaha/YoloV4-Weapons-Detection.git
   ```
2. Install Darknet [Tutorial](https://medium.com/geekculture/yolov4-darknet-installation-and-usage-on-your-system-windows-linux-8dec2cea6e81) in a new folder "darknet-master"
3. delete "data" and "cfg" folders from darknet-master
4. copy "data" and "cfg" folders from the cloned darknet folder to "darknet-master"
5. rename darknet.py in "darknet-master" to darknet2.py
6. copy "yolov4-custom_best.weights" from the cloned darknet folder to "darknet-master"
7. delete the cloned darknet folder
8. rename "darknet-master" to darknet and move it to the project folder
9. edit Yolo_Test_and_Deployment.ipynb by putting sender email and password
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>

 -->

<!-- ROADMAP
## Roadmap

- [] Feature 1
- [] Feature 2
- [] Feature 3
    - [] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

 -->

<!-- CONTRIBUTING
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>
 -->


<!-- LICENSE
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>
 -->


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
This is The Graduation Project of the Information Technology institute [ITI](https://www.iti.gov.eg/iti/hom) AI program Powered by EPITA
### Team
* Ahmed Magdy - [@Linkedin](https://www.linkedin.com/in/ahmedmagdy9696/)
* Reham ElTagoury - [@Linkedin](https://www.linkedin.com/in/reham-eltagoury-496804167/) 
* Nayrouz Al-Gamaal - [@Linkedin](https://www.linkedin.com/in/nayrouz-al-gamaal-29156b167/) 
* Mahmoud Taha - [@Linkedin](https://www.linkedin.com/in/mahmoud-taha/) - Mahmoudtaha613@gmail.com
* Wssam Hassan - [@Linkedin](https://www.linkedin.com/in/wssam-hassan/) 

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/1.jpeg
