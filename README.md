<h1 align="center">
    <a href="https://github.com/ODGodinho">
        <img
            src="https://raw.githubusercontent.com/ODGodinho/Stanley-TheTemplate/main/public/images/Stanley.jpg"
            alt="Stanley Imagem" width="500"
        />
    </a>
    <br />
    Stanley The Template For Typescript By Dragons Gamers.
    <br />
</h1>

<h4 align="center">Template Stanley for Typescript ๐ฆ</h4>

<p align="center">

[![Stargazers](https://img.shields.io/github/stars/ODGodinho/Stanley-TheTemplate-Typescript?color=F430A4)](https://github.com/ODGodinho/Stanley-TheTemplate-Typescript/stargazers)
[![Made by ODGodinho](https://img.shields.io/badge/made%20by-ODGodinho-%2304A361)](https://www.linkedin.com/in/victor-alves-odgodinho/)
[![Forks](https://img.shields.io/github/forks/ODGodinho/Stanley-TheTemplate-Typescript?color=CD4D34)](https://github.com/ODGodinho/Stanley-TheTemplate-Typescript/network/members)
![Repository size](https://img.shields.io/github/repo-size/ODGodinho/Stanley-TheTemplate-Typescript)
[![GitHub last commit](https://img.shields.io/github/last-commit/ODGodinho/Stanley-TheTemplate-Typescript)](https://github.com/ODGodinho/Stanley-TheTemplate-Typescript/commits/master)
[![License](https://img.shields.io/badge/license-MIT-brightgreen)](https://opensource.org/licenses/MIT)

</p>

# Table of Contents

- [๐ Benefits](#-benefits)
- [๐ Libraries](#-libraries)
- [๐ Dependencies](#-dependencies)
- [โฉ Get Started](#-get-started)
  - [๐ Use Template](#-use-template)
  - [๐ Configure Github Token](#-configure-github-token)
    - [๐ Create Github Token](#-create-github-token)
    - [๐ Create project Environment](#-create-project-environment)
  - [๐ป Prepare to develop](#-prepare-to-develop)
  - [๐ Start Project](#-start-project)
  - [๐จ Build and Run](#-build-and-run)
  - [๐งช Teste Code](#-teste-code)

---

## ๐ Benefits

- ๐ Speed start new project or package using typescript
- ๐จ Over 300 rules for pattern, possible errors and errors in Linter
- ๐ Code quality guaranteed
- ๐ข AutoReview when opening a pull-request/merge
    ![AutoReview Comment example](https://user-images.githubusercontent.com/3797062/97085944-87233a80-165b-11eb-94a8-0a47d5e24905.png)
- ๐งช Automatic Test when opening pull-request/merge

## ๐ Libraries

- [Node.js 16](https://nodejs.org/?n=dragonsgamers)
- [Typescript](https://www.typescriptlang.org/?n=dragonsgamers)
- [Eslint](https://eslint.org/?n=dragonsgamers)
- [ODG-Linter-JS](https://github.com/ODGodinho/ODG-Linter-Js?n=dragonsgamers)
- [EditorConfig](https://editorconfig.org/?n=dragonsgamers)
- [ReviewDog](https://github.com/reviewdog/action-eslint)

## ๐ Dependencies

- [Node.js](https://nodejs.org) 16 or later
- [Yarn](https://yarnpkg.com/) Optional/Recommended
- [ODG TsConfig](https://github.com/ODGodinho/tsconfig) Last Version

## โฉ Get Started

---

### ๐ Use Template

Click in use this template button and clone your template project

![Use Template](https://raw.githubusercontent.com/ODGodinho/Stanley-TheTemplate/main/public/images/UseTemplate.png)

### ๐ Configure Github Token

#### ๐ Create Github Token

Before create new GITHUB_TOKEN in

- <https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token>

#### ๐ Create project Environment

- On GitHub.com, navigate to the main page of the repository.
- Under your repository name, click `โ๏ธ Settings`.
![Github Setting images example](https://docs.github.com/assets/cb-27528/images/help/repository/repo-actions-settings.png)
- In the "Security" section of the sidebar, select `โณ๏ธ Secrets`, then click Actions.
- Click New repository secret.
- Type a name with: **GH_TOKEN**
- Enter with your access secret token `ghp_Dsfde....`
- Click Add secret.

### ๐ป Prepare To Develop

Copy `.env.example` to `.env` and add the values according to your needs.

### ๐ Start Project

First install dependencies with the following command

```bash
yarn install
# or
npm install
```

## ๐จ Build and Run

To build the project, you can use the following command

> if you change files, you need to run `yarn build` and `yarn start` again

```bash
yarn build && yarn start
# or
yarn dev
```

## ๐งช Teste Code

To Test execute this command

```bash
yarn test
# or
yarn test:watch
```
