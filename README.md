<!-- VARS -->

[logo-url]: https://camo.githubusercontent.com/74c8681f6d4521903b63e79173a72f0b849243be/68747470733a2f2f692e696d6775722e636f6d2f73356c546465502e706e67
[web-badge]: https://img.shields.io/badge/WEB-6842C2?logo=typescript&logoColor=47248F&label=Proffy&labelColor=6842C2&style=for-the-badge
[backend-badge]: https://img.shields.io/badge/BACKEND-04D361?logo=Node.js&logoColor=03A14A&label=Proffy&labelColor=04D361&style=for-the-badge
[mobile-badge]: https://img.shields.io/badge/MOBILE-494949?logo=react&logoColor=161616&label=Proffy&labelColor=494949&style=for-the-badge

<!-- VARS -->

<div align="center">

# ![Proffy][logo-url]

### Online learning platform to connect students and teachers.

[![web][web-badge]](web)
[![backend][backend-badge]](server)
[![mobile][mobile-badge]](mobile)

![](.github/imgs/landing.svg)

</div>

# 🌱 Project objective
---

O Proffy nasceu de uma iniciativa de educadores para a comunidade de desenvolvedores, como forma de proporcionar a criação de um MVP com a stack NodeJS, React e React Native ([saiba mais](https://nextlevelweek.com/)). Esse projeto consiste em uma plataforma que liga alunos a professores particulares de diversas matérias, utilizando um sistema de crud com arquitetura de rest api no backend e com frontend's web e mobile.

---

## 🚀 Technologies

Technologies used to develop this application

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/pt-br/)
- [Knex](http://knexjs.org/)
- [SQLite](https://www.sqlite.org/)
- [React Router DOM](https://reacttraining.com/react-router/)
<!-- - [React Navigation](https://reactnavigation.org/) -->
<!-- - [React Icons](https://react-icons.netlify.com/#/) -->

## 💻 Getting started

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [Expo](https://expo.io/)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/VictorKengoo/Proffy-NLW2
$ cd Proffy-NLW2
```

**Follow the steps below**

### Backend

```bash
# Starting from the project root folder, go to server folder
$ cd server

# Install the dependencies
$ yarn

# Use the script to run the migrations
$ yarn knex:migrate

# To finish, run the api service
$ yarn dev

# Well done, project is started!
```

### Web

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to frontend web folder
$ cd web

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the client
$ yarn start
```

### Mobile

<!-- _Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to mobile folder
$ cd mobile

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the expo service and scan the QR code with Expo Client
$ yarn start
``` -->

<p align="center">
  Under development<br />
  <img src="https://i.pinimg.com/originals/ae/51/e1/ae51e1395e87cc72c6021df5445cc5f8.gif" alt="Loading" align="center" height="300">
</p>

## 🤔 How to contribute

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork VictorKengoo/Proffy-NLW2
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone your-fork-url 
$ cd proffy

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


<div align="center">

<table>
  <tr align="center">
    <td>Coded By</td><td>Instrutor</td>
  </tr>
  <tr align="center">
    <td>
      <a href="https://github.com/VictorKengoo">
        <img src="https://avatars2.githubusercontent.com/u/55894232?s=460&u=988d76189e00f291454c792d105a7147b0b23ee7&v=4" width 
        ="100" />
      </a>
    </td>
    <td>
      <a href="https://github.com/diego3g">
        <img src="https://avatars2.githubusercontent.com/u/2254731?v=4" width 
        ="100" />
      </a>
    </td>
  </tr>
</table>

</div>

<h4 align=center>Made with 💜 by <a href="https://www.linkedin.com/in/victor-kodama-257496160">Victor Kodama</a></h4>

