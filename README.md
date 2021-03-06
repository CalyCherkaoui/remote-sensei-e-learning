# Remote Sensei | MVP for e-learning platform
## About the project
In this project, I built an online learning platform.
[Link to the deployed App]()

### Main features:
 - Secure authentication system
 - Admin panel
 - It allows the user to create a curiculum with a numbers of lessons.
 - It displays lists of lessons and curriculum ordered by priority and popularity.

## Built with
  <a href="https://www.ruby-lang.org/en/documentation/"><img width="10%" src="https://www.vectorlogo.zone/logos/ruby/ruby-ar21.svg" alt="Ruby"></a>
  <a href="https://guides.rubyonrails.org/"><img width="50px" src="https://guides.rubyonrails.org/images/favicon.ico" alt="Rails"></a>
  <a href="https://www.postgresql.org/"><img width="100px" src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg" alt="postgresql"></a>
  <a href="#"><img width="10%" src="https://www.vectorlogo.zone/logos/heroku/heroku-ar21.svg"></a>
  <a href="https://github.com/"><img width="5%" src="https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp" alt="GitHub"></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img width="5%" src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" alt="Javascript"></a>
  <a href="#"><img width="30px" src="https://cdn.svgporn.com/logos/html-5.svg"></a>
  <a href="#"><img width="30px" src="https://cdn.svgporn.com/logos/css-3.svg"></a>
  <br>

## Table of content
- [About the project](#about-the-project)
- [Built with](#built-with)
- [App live demo](#app-live-demo)
- [Dependencies](#dependencies)
- [Linting tools](#linting-tools)
- [Getting started](#getting-started-in-development)
- [Automated tests](#automated-tests)
- [Author](#author)
- [Contributing](#-Contributing)
- [Acknowledgments](#acknowledgments)
- [License](#license)



## App live demo

[Check here the link to the deployed App ]()

## Dependencies
The main dependencies used in this web application:

<table>
  <tr>
    <th>Dependency</th>
    <th>for</th>
    <th>Development</th>
    <th>Test</th>
    <th>Production</th>
  </tr>
  <tr>
    <td>Rails</td>
    <td>Ruby based server-side web application framework</td>
    <td>??????</td>
    <td>??????</td>
    <td>??????</td>
  </tr>
  <tr>
    <td>Postgresql</td>
    <td>Database</td>
    <td>??????</td>
    <td>??????</td>
    <td>??????</td>
  </tr>
  <tr>
    <td>rspec-rails</td>
    <td>A testing framework for Rails</td>
    <td></td>
    <td>??????</td>
    <td></td>
  </tr>
  <tr>
    <td>factory_bot_rails</td>
    <td>A fixtures replacement</td>
    <td></td>
    <td>??????</td>
    <td></td>
  </tr>
  <tr>
    <td>shoulda-matchers</td>
    <td>Simple One-Liner Tests for Rails</td>
    <td></td>
    <td>??????</td>
    <td></td>
  </tr>
  <tr>
    <td>database_cleaner</td>
    <td>Strategies for cleaning databases in testing</td>
    <td></td>
    <td>??????</td>
    <td></td>
  </tr>
  <tr>
    <td>faker</td>
    <td>Generates fake data for testing</td>
    <td></td>
    <td>??????</td>
    <td></td>
  </tr>
  <tr>
    <td>devise</td>
    <td>Flexible authentication solution for Rails based on Warden</td>
    <td>??????</td>
    <td>??????</td>
    <td>??????</td>
  </tr>
  <tr>
    <td>rack-cors</td>
    <td>Support for Cross-Origin Resource Sharing for Rack compatible web apps</td>
    <td>??????</td>
    <td></td>
    <td>??????</td>
  </tr>
  <td>Cancancan</td>
    <td>Rails helper for authorisation management</td>
    <td>??????</td>
    <td></td>
    <td>??????</td>
  </tr>
</table>

## Linting tools
<table>
  <tr>
    <th>Linter</th>
    <th>Use</th>
    <th>Files</th>
  </tr>
  <tr>
    <td>Rubocop</td>
    <td>Linting Ruby files</td>
    <td>.rb</td>
  </tr>
</table>

## Getting started in development

### Clone the repository:

To get a local copy of the repository, please run the following commands on your terminal:

```
$ git clone git@github.com:CalyCherkaoui/remote-sensei-e-learning.git
$ cd 
$ git branch feature
$ git checkout feature

```

### Prerequisites:

Ruby: 3.1.1
Rails: 7

Run your Postgresql service in your terminal:

```
$ sudo service postgresql restart
```
### Setup:

Install gem dependencies:
```
$ bundle install
```

Setup the database:
```
$ rails db:create
$ rails db:migrate
$ rails db:seed
```

### Usage:

Run Rails server:
```
$ rails s
```
In the browser, open ``http://localhost:3001``


To lint Ruby code:
```
$  rubocop -A
```

To run the tests:
```
$  bundle exec rpsec
```
## Automated tests

### Unit tests series:

<br>
<img width="700px" height="auto" src="./public/screenshots/unit-test1.png">
<br>

### Request tests series:

<br>
<img width="700px" height="auto" src="./public/screenshots/request-test1.png">
<br>

## Author
???? **Houda Cherkaoui**

- Github: [@CalyCherkaoui](https://github.com/CalyCherkaoui)
- Twitter: [@Houda59579688](https://twitter.com/Houda59579688)
- Linkedin: [Houda-Cherkaoui](https://www.linkedin.com/in/houda-cherkaoui-64106395/)
## Contributing
Contributions, issues, and feature requests are welcome!
## Show your support
Give a ?????? if you like this project!
## Acknowledgments
- Hat tip to [stackoverflow](https://stackoverflow.com) comunity.
- Hat tip to [Microverse](https://www.microverse.org/) TSE for Code Review.
- Hat tip to anyone whose code was used
- [deployement tuto](https://mgleon08.github.io/blog/2018/07/22/deploying-rails-nuxt-jwt-to-production-with-heroku/)
## ???? License
All source code is available jointly under the MIT License.
See [MIT licence](./LICENSE) for details.
