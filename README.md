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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project was created for easy implementation of Red Teaming infraestructure for tiendanube.

### Built With

* [Traefik]()
* [GoPhish]()
* [Covenant]()
* [Metasploit]()
* [Docker Compose]()


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
3. Please ensure that file "gophish.db" inside gophishVolumes directory have write permission to everyone:

4. Run following command to start the new infraestructure:
   ```sh
   ./start.sh
   ```


