<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://animewatchedlist.netlify.app">
    <img src="images/logo.svg" alt="Logo" width="300" height="300">
  </a>

  <h3 align="center">Fanime</h3>

  <p align="center">
    Keep track of the anime you are watching and have watched.
    <br />
    <a href="https://github.com/marleneharms/fanime"><strong>Explore the docs »</strong></a>
    <br />
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://animewatchedlist.netlify.app)

Sometimes you lose the track of your favorite anime and you don't know where to look.  Or you just want to know what's on your list.  That's why I created this project. Here you can save your anime list and keep track of what you've watched and what you haven't.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

Most of this technologies are new to me and that is excavtly why I choosed them. 

- [Bulma](https://bulma.io)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)
- [Express.js](https://expressjs.com/)
- [JWT](https://jwt.io/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Node.js](https://nodejs.org/)
- [React.js](https://reactjs.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

This project is mainly composed of Node and React so make sure you have those installed.
Also you need two .env one in the backend root and the other one in the front root. 

### Prerequisites

This is a node project, so you need to have node installed.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

Below are the commands you can use to install the application.

1. Clone the repo
   ```sh
   git clone https://github.com/marleneharms/fanime.git
   cd fanime
   ```
2. Install NPM packages involved in backend
   ```sh
   cd auth
   npm install
   ```
2. Install NPM packages involved in frontend
   ```sh
   cd auth-front
   npm install
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage
Below are the commands you can use to get your app up and running.
Make sure to have the backend .env file in the following format:

  ```sh
     DB_CONNECT= "mongodb connection string"
     TOKEN_SECRET= "secret string"
     REFRESH_TOKEN_SECRET= "secret string"
  ```
And in the frontend .env file:
  ```sh
     REACT_APP_API_URL=  "api url"
  ```

1. First run api
   ```sh
    cd ./auth
    npm run dev
   ```
2. Run frontend
   ```sh
   cd ./auth-front
   npm start
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Add login
- [x] Add register
- [x] Add anime cards
- [x] Add form to add anime
- [ ] Add anime api to search anime
- [ ] Add feat to share your anime list
- [ ] Add feat to rate anime 

See the [open issues](https://github.com/marleneharms/fanime/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->

## Contact

Marlene R. Harms -  marlene_harms@gmail.com

Project Link: [https://github.com/marleneharms/fanime](https://github.com/marleneharms/fanime)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/marleneharms/fanime.svg?style=for-the-badge
[contributors-url]: https://github.com/marleneharms/fanime/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/marleneharms/fanime.svg?style=for-the-badge
[forks-url]: https://github.com/marleneharms/fanime/network/members
[stars-shield]: https://img.shields.io/github/stars/marleneharms/fanime.svg?style=for-the-badge
[stars-url]: https://github.com/marleneharms/fanime/stargazers
[issues-shield]: https://img.shields.io/github/issues/marleneharms/fanime.svg?style=for-the-badge
[issues-url]: https://github.com/marleneharms/fanime/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/marlene-harms
[product-screenshot]: images/project-demo.png
