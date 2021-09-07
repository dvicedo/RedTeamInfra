<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/dvicedo/RedTeamInfra">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Infraestructura Red Team</h3>

  <p align="center">
    Red Teaming infraestructure for tiendanube.
    <br />
    <a href="https://github.com/dvicedo/RedTeamInfra"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project was created for easy implementation of Red Teaming infraestructure for tiendanube.

### Built With

* [Traefik]()
* [GoPhish]()
* [Covenant]()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

It's necessary to have docker-compose and docker enviroment previously installed. 
* docker
  ```sh
  docker --version
  ```
* docker-compose
  ```sh
  docker-compose --version
  ```


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/dvicedo/RedTeamInfra.git
   ```
2. Go to edgy-c2 folder and run following command to build the covenant image:
   ```sh
   ./buildCovenant.sh
   ```
3. Edit .env file setting with your local IP, example:
   ```sh
   C2EXTIP=192.168.1.4
   ```
4. Run following command to start the new infraestructure:
   ```sh
   ./start.sh
   ```





<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/dvicedo/RedTeamInfra/issues) for a list of proposed features (and known issues).




<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/dvicedo/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/dvicedo/RedTeamInfra/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dvicedo/repo.svg?style=for-the-badge
[forks-url]: https://github.com/dvicedo/RedTeamInfra/network/members
[stars-shield]: https://img.shields.io/github/stars/dvicedo/repo.svg?style=for-the-badge
[stars-url]: https://github.com/dvicedo/RedTeamInfra/stargazers
[issues-shield]: https://img.shields.io/github/issues/dvicedo/repo.svg?style=for-the-badge
[issues-url]: https://github.com/dvicedo/RedTeamInfra/issues
[license-shield]: https://img.shields.io/github/license/dvicedo/repo.svg?style=for-the-badge
[license-url]: https://github.com/dvicedo/RedTeamInfra/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/dvicedo
