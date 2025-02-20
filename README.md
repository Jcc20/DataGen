<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
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
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">DataGen</h3>

  <p align="center">
    A JSON and XML dataset generator, featuring a Domain Specific Language (DSL) that allows for automatic creation of RESTful APIs on the generated datasets. 
    <br />
    <a href="https://github.com/wurzy/DataGen/tree/main/backend">Back-End</a>
    ·
    <a href="https://github.com/wurzy/DataGen/tree/main/frontend">Front-End</a>
    ·
    <a href="https://github.com/wurzy/DataGen/tree/main/strapi">Strapi</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

**DataGen** is a versatile and powerful tool that allows for quick prototyping and testing of software applications, since currently too few solutions offer both the complexity and scalability necessary to generate adequate datasets in order to feed a data API or a more complex APP, enabling their testing with appropriate data volume and complexity.

**DataGen**’s core is a Domain Specific Language (DSL) that was created to specify datasets. This language suffered several updates: repeating fields (with no limit), fuzzy fields (statistically generated), lists, high order functions over lists, custom made transformation functions. The final result is a diversified algebra that allows the generation of very complex datasets coping with very convoluted requirements. Throughout the paper, several examples of the possibilities will be given. 

After generating a dataset, DataGen gives the user the possibility to generate a RESTFul data API with it, creating a running prototype. 

### Built With

The front-end of the application is built mainly using:
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [Vue](https://vuejs.org/)

The back-end is using the following frameworks and tools:
* [MongoDB](https://www.mongodb.com/)
* [Node.js](https://nodejs.org/en/)
* [Strapi](https://strapi.io/)



<!-- GETTING STARTED -->
## Getting Started

The installation process of the application is relatively simple, assuming you meet the requirements.

### Prerequisites

* docker
* docker-compose

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/wurzy/DataGen.git
   ```
2. Navigate to the repository
3. Create the service and the containers
   ```sh
   docker-compose up -d
   ```
4. Open http://localhost:12080/ (default port on the docker-compose file)
5. (Recommended) Create an admin account on the website
    1. Register a new account using the UI
    2. On the container 'mongo', open the mongo shell and enter the collection 'users' from the database 'LEI2021'
    3. Change the 'nivel' field from 'user' to 'admin' on the created account
    4. Apply the changes
6. The application is now ready to use


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contacts

* Filipa Santos - [LinkedIn](https://www.linkedin.com/in/filipa-santos-00111b1b5/) - [GitHub](https://github.com/fliper6)
* Hugo Cardoso - [LinkedIn](https://www.linkedin.com/in/hugo-cardoso-b868a474/) - [GitHub](https://github.com/Abjiri)
* João Cunha - [LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-cunha-6aab35215/) - [GitHub](https://github.com/Jcc20)
* Válter Carvalho - [LinkedIn](https://www.linkedin.com/in/valterfpcarvalho/) - [GitHub](https://github.com/wurzy)

And the supervisor of the project:

* José Ramalho - [LinkedIn](https://pt.linkedin.com/in/josé-carlos-ramalho-ab5535a) - [GitHub](https://github.com/jcramalho)

Project Link: [https://github.com/wurzy/DataGen](https://github.com/wurzy/DataGen)

Official University of Minho Repository Entry: [http://repositorium.sdum.uminho.pt/handle/1822/73506](http://repositorium.sdum.uminho.pt/handle/1822/73506)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/wurzy/DataGen/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/wurzy/DataGen/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/wurzy/DataGen/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/wurzy/DataGen/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/wurzy/DataGen/blob/main/LICENSE
