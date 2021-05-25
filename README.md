 [![MIT License][license-shield]][license-url]
  [![LinkedIn][linkedin-shield]][linkedin-url]

<br />

  
  <h3 align="center">Semiconductor Industry Evaluation & Queuing Model Paper </h3>
  
<p align="center">
  <a href="https://github.com/jtourkis/Semi-Conductor-Industry">
    <img src="christian-wiediger-c3ZWXOv1Ndc-unsplash.jpg" alt="AB" width="300" height="300" style="border:5px solid black">
  </a>
  <p align="center">
   Photo by <a href="https://unsplash.com/@christianw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Christian Wiediger</a> on <a href="https://unsplash.com/s/photos/semiconductor?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
  <b>Goal:</b> This project explores the use of a queuing model to approximate semiconductor production capacity.
    <br />
    <a href="https://github.com/jtourkis/Semi-Conductor-Industry"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jtourkis/Semi-Conductor-Industry">View Demo</a>
    ·
    <a href="https://github.com/jtourkis/Semi-Conductor-Industry/issues">Report Bug</a>
    ·
    <a href="https://github.com/jtourkis/Semi-Conductor-Industry/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

As demand for semiconductors grows and production capacity becomes increasingly strained, this project considers how a queueing model might be used to guide capacity growth discussions and estimate potential impacts of adding different forms of production capacity. The proposed model uses a poisson distribution to estimate daily orders and order probabilities from actual demand to estimate likely order type. It then uses daily machine capacity estimates to process orders while tracking machine idle time, missed orders, wait time, and revenue. 

### Built With

* [Python](https://www.python.org) / [Jupyter Notebook](https://jupyter.org)
* [Numpy](https://numpy.org) 

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

List of required packages.

* pandas

* plotly

* seaborn

* matplotlib.pyplot


### Installation
 
1. Clone the repo

```sh
git clone https://github.com/jtourkis/Semi-Conductor-Industry.git
```
2. Install packages
```sh
pip install package
```


<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap
Using the available data, we will attempt to answer 4 questions.
1) Overview of the semiconductor industry opportunities and challenges. 

2) Create python production queuing model to approximate different production quantities based on capacity. 

3) Evaluate queuing model. 


See the [open issues](https://github.com/github_username/repo/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

Note: The intial README Template was distributed under the MIT License. Copyright (c) 2018 Othneil Drew. [LICENSE](https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt)  for more information. 



<!-- CONTACT -->
## Contact

James Tourkistas - jmtourkistas@suffolk.edu

Project Link: [https://github.com/jtourkis/Semi-Conductor-Industry](https://github.com/jtourkis/Semi-Conductor-Industry)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md) 
* [Harvard Extension School AM115 Mathematical Modeling](https://online-learning.harvard.edu/course/mathematical-modeling?delta=0)
* [See Paper Citations](https://github.com/jtourkis/Semi-Conductor-Industry/blob/main/Math%20Modeling%20Semi%20Conductor%20Paper.pdf)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/jtourkis/MBTA-Ridership-Model/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/james-tourkistas-7127ba167/
[product-screenshot]: images/screenshot.png
