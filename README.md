<h1 align="center">
  <img src="https://res.cloudinary.com/eliasgcf/image/upload/v1590249783/fastfeet/logo_erpvwm.svg" alt="Logo" width="250px">
</h1>

<h3 align="center">
  Express Application for FastFeet project
</h3>

<p align="center">
  A fast way to manage delivery companies!
</p>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/EliasGcf/fastfeet-api?color=%237D40E7">

  <a href="https://www.linkedin.com/in/eliasgcf/" target="_blank" rel="noopener noreferrer">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-elias%20gabriel-%237D40E7">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/EliasGcf/fastfeet-api?color=%237D40E7">

  <a href="https://github.com/EliasGcf/fastfeet-api/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/EliasGcf/fastfeet-api?color=%237D40E7">
  </a>

  <a href="https://github.com/EliasGcf/fastfeet-api/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/EliasGcf/fastfeet-api?color=%237D40E7">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/EliasGcf/fastfeet-api?color=%237D40E7">
</p>

<p align="center">
  <a href="#-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

<p id="insomniaButton" align="center">
  <a href="https://insomnia.rest/run/?label=FastFeet%20API%20-%20EliasGcf&uri=https%3A%2F%2Fraw.githubusercontent.com%2FEliasGcf%2Ffastfeet-api%2Fmaster%2FInsomnia.json" target="_blank">
    <img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia">
  </a>
</p>

## 🚚 About the project

With this API is possible to manage users, recipients, delivery man and everything what is needed for the delivery flow.

To confirm the delivery was finished, the delivery man must send a recipient signature photo. This is one of the application business rules.

To see the **web client**, click here: [FastFeet Web](https://github.com/EliasGcf/fastfeet-web)<br />
To see the **mobile client**, click here: [FastFeet Mobile](https://github.com/EliasGcf/fastfeet-mobile)

## 🚀 Technologies

Technologies that I used to develop this api

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Sequelize](https://sequelize.org/)
- [Mongoose](https://mongoosejs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/products/docker-desktop)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Multer](https://github.com/expressjs/multer)
- [Nodemailer](https://nodemailer.com/about/)
- [Handlebars](https://handlebarsjs.com/)
- [JWT-token](https://jwt.io/)
- [Bee-Queue](https://github.com/bee-queue/bee-queue)
- [Yup](https://github.com/jquense/yup)
- [Date-fns](https://date-fns.org/)
- [Nodemon](https://nodemon.io/)
- [Sucrase](https://github.com/alangpierce/sucrase)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

## 💻 Getting started

Import the `Insomnia.json` on Insomnia App or click on [Run in Insomnia](#insomniaButton) button

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [Docker](https://www.docker.com/products/docker-desktop) and [Docker Compose](https://docs.docker.com/compose/install/)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/EliasGcf/fastfeet-api.git && cd fastfeet-api
```

**Follow the steps below**

```bash
# Install the dependencies
$ yarn

# Make a copy of '.env.example' to '.env'
# and set with YOUR environment variables.
$ cp .env.example .env

# Start the services with docker-compose
$ docker-compose up -d

# Once the services are running, run the migrations
$ yarn sequelize db:migrate

# Run the seed to create the 'admin-user'
$ yarn sequelize db:seed --seed 20200212180839-admin-user.js

# Well done, project is started!
```

## 🤔 How to contribute

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork EliasGcf/fastfeet-api
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone your-fork-url && cd fastfeet-api

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💜 by Elias Gabriel 👋 [See my linkedin](https://www.linkedin.com/in/eliasgcf/)
