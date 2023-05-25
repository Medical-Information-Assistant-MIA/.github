<a name="readme-top"></a>

<div align="center">
	

# Medical Information Assistant(MIA)

</div>
<div align="center">
  <!-- <a href="https://github.com/pantry-wizard/pantry_wizard_be">
    <img src="LOGO_URL_HERE" alt="Logo" width="582" height="404">
  </a> -->
<h3 align="center"></h3>

  <div align="center">
    <!-- ADD APP DESCRIPTION ****************** -->
    <br>
    <p> Medical Information Assistant (MIA) is a service oriented application that allows users to document their personal medical information in a customizable and intuitive way. 
    </p>
    <br />
    <!-- <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a> -->
    <!-- <br /> -->
    <!-- <br /> -->
    <!-- <a href="https://github.com/github_username/repo_name">View Demo</a> -->
    <!-- · -->
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
        <li><a href="#installation">Installation</a></li>
        <li><a href="#testing-with-rspec">Testing With RSpec</a></li>
      </ul>
    </li>
    <li><a href="#available-endpoints">Available Endpoints</a></li>
    <li><a href="#goals">Goals</a></li>
    <!-- <li><a href="#usage">Usage</a></li> -->
    <!-- <li><a href="#roadmap">Roadmap</a></li> -->
    <!-- <li><a href="#contributing">Contributing</a></li> -->
    <!-- <li><a href="#license">License</a></li> -->
    <!-- <li><a href="#contact">Contact</a></li> -->
    <!-- <li><a href="#acknowledgments">Acknowledgments</a></li> -->
  </ol>
</details>


<br>

<!-- ABOUT THE PROJECT -->
## About The Project
<br>

<!-- ADD PROJECT DESCRIPTION -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Built With:
### Backend:

[![Ruby]][Ruby-url] **3.1.1**
[![Rails]][Rails-url] **7.0.4**
[![Postgresql]][Postgresql-url] **1.1**
[![GraphQL]][GraphQL-url]
[![GraphiQL]][GraphiQL-url]


### Testing:


[![Faker]][Faker-url]
[![Factory Bot]][Factory Bot-url]
[![RSpec]][RSpec-url]
[![Shoulda-Matchers]][Shoulda-Matchers-url]
[![SimpleCov]][SimpleCov-url]


### Development Tools:

[![Heroku]][Heroku-url]
[![Faraday]][Faraday-url]
[![RuboCop]][RuboCop-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

<!-- This is a Ruby on Rails application which establishes API endpoints to be called in the <a href="UPDATE LINK"> `MIA-FE` </a> repository. To run the application locally, both front-end and back-end repositories will need to be cloned and set up fully with required gems and environment variables. -->

<br>

### Installation

1. Clone the repo:
   ```bash
   git clone git@github.com:Medical-Information-Assistant-MIA/MIA-BE.git
   ```

2. Install gems:
   ```bash
   bundle install
   ```

3. To establish the database, run:
   ```bash
   rails db:create
   ```

4. Since this is the back-end repository, a database migration is also necessary, run:
   ```bash
   rails db:migrate
   ```

<!-- ADD THIS NEXT STEP ONCE AN EXTERNAL API IS INCORPORATED -->
<!-- 6. Add your API key to the application.yml file
    ```bash
    API_KEY = xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    ```
<br> -->

  Inspect the `/db/schema.rb` and compare to the 'Schema' section below to ensure this migration has been done successfully.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<br>


### Testing with RSpec

Once `MIA-BE` is correctly installed, run tests locally to ensure the repository works as intended.

<br>

  To test the entire RSpec suite, run:
   ```bash
   bundle exec rspec
   ```

<br>

All tests should be passing if the installation was successful. 

If any tests are not passing, please report which tests are not passing <a href="PLEASE UPDATE LINK">Here</a>. We will issue an update/fix as soon as possible.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<br>


## __Available Endpoints__

Current endpoint documentation exists in the Postman Mock Server below.
https://documenter.getpostman.com/view/27373334/2s93kxc6FD

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## __Goals__

MIA was crafted to satisfy the requirements for The Turing Mod 4 **Capstone Project**. 

See the official project requirements [here](https://mod4.turing.edu/projects/capstone/).

<br>

### __Learning Goals__
<ul>
  <li>Use an agile process to turn well defined requirements into deployed and production ready software. </li>
  <li>Gain experience dividing applications into components and domains of responsibilities to facilitate multi-developer teams. Service oriented architecture concepts and patterns are highly encouraged. </li>
  <li>Explore and implement new concepts, patterns, or libraries that have not been explicitly taught while at Turing. </li>
  <li>Practice an advanced, professional git workflow including a Pull Request Review.</li>
  <li>Gain experience using continuous integration tools to build and automate the deployment of features. </li>
  <li>Build applications that execute in development, test, CI, and production environments. </li>
  <li>Add additional querying options for more user friendly trend data representation. </li>
  <li>Utilize caching for optimization. </li>
  <li>Focus on communication between front-end and back-end teams in order to complete and deploy features that have been outlined by the project spec. </li>
</ul>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### __Future Goals__
<ul>
  <li> Add user authentication / authoriazation. </li>
  <li> Utilize caching for optimization.</li>
  <li> Containerize the application via docker.</li>
  <li> Add additional querying options for more user friendly trend data representation.</li>
  <li> Add a microservice that consumes an exerternal API for medication information. </li>
  <li> Deploy the application to another service such as Amazon or Digital Ocean. </li>
</ul>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<br>

## __Database Schema__

<img src=images/schema.png alt="Database Schema">

<br>

## __Back End Team__
<table>
<!-- Update picture links -->
  <!-- <tr>
    <td><img src="https://avatars.githubusercontent.com/u/116330317?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/88596340?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/104170346?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/71752551?s=120&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/117066950?s=120&v=4"></td>
  </tr> -->
  <tr>
    <td>Brad Dunlap</td>
    <td>Chris Crane</td>
    <td>Kara Jones-Hofmann</td>
    <td>Matt Enyeart</td>
    <td>Tori Enyart</td>
    <td>Sophie LaBelle</td>
    <td>Amber Shipley</td>
    <td>Kass Daniello</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/brad-dunlap">GitHub</a><br>
      <a href="https://www.linkedin.com/in/dunlap-brad/">LinkedIn</a> 
    </td>
    <td>
      <a href="https://github.com/GreenGogh47">GitHub</a><br>
      <a href="https://www.linkedin.com/in/chris-crane-16106814/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/KaraJoHo">GitHub</a><br>
      <a href="https://www.linkedin.com/in/81012911-91208/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/menyeart">GitHub</a><br>
      <a href="https://www.linkedin.com/in/matt-enyeart/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/torienyart">GitHub</a><br>
      <a href="https://www.linkedin.com/in/victoria-enyart-595052155/">LinkedIn</a>
    </td> 
    <td>
      <a href="https://github.com/sophielabelle">GitHub</a><br>
      <a href="https://www.linkedin.com/in/victoria-enyart-595052155/">LinkedIn</a>
    </td> 
    <td>
      <a href="https://github.com/espressoGoddess">GitHub</a><br>
      <a href="">LinkedIn</a>
    </td> 
    <td>
      <a href="https://github.com/Zertroz">GitHub</a><br>
      <a href="https://www.linkedin.com/in/victoria-enyart-595052155/">LinkedIn</a>
    </td> 
   
    
  </tr>
</table>


<!-- PROJECT MANAGER -->
## Project Manager

* Brian Zanti
<!-- Project Mentor -->
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Project Mentor

* Daniel Starling

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments



# [Mia (Medical Information Assisstant)](https://mia-fe.vercel.app/)

## Abstract:
[//]: <>

Mia simplifies your healthcare journey by consolidating all your vital medical information in one place. Keep track of conditions, medications, doctors, and health events effortlessly. Access a centralized doctor directory. Maintain a personal health log to record important events and notes. Take control of your health with Mia.

## Built With: 
[//]: <>

TypeScript, React, Graphql. Tested with Cypress.

## Contributors:
[//]: <>

[Sophie Labelle](https://github.com/sophielabelle) \
[Kass Daniello](https://github.com/Zertroz) \
[Amber Shipley](https://github.com/espressoGoddess) 

[//]: <>



## Live demo:
[//]: <>

Application is deployed live at: [Vercel](https://mia-fe.vercel.app/)


## Context:
[//]: <>

This project was the final capstone project during Turing, combining a front end team with a backend. The backend repo can be found [here](https://github.com/Medical-Information-Assistant-MIA/MIA-BE)

## Learning Goals:
[//]: <>

- Familiarize ourselves with TypeScript
- Employ GraphQL
- Work directly with a backend team
- 

## Future Feature Ideas:
[//]: <>

- Edit function
- Adding additional information to existing conditions
- Live list of medications to choose from
