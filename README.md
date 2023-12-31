# MERN Social App

## Description

A MERN Social App:
Features: Frontend and Backend Authentication (jwt)
User Features:

- Update Profile, Create, edit and delete post, like and unlike, comment, follow and unfollow user, photo snapshot and video, message, and saved post.

## Clone this Repo

```
$ git clone https://github.com/oreoseenoevil/mern-app-social.git
$ cd mern-app-social
```

## Setup

### Prerequisites
```
$ node.js 16.x
```

```
$ copy env.example .env
```

## Configure or Add your MONGODB URI, API & SECRET

```
  * MONGO_URI & ACCESS_TOKEN_SECRET & REFRESH_TOKEN_SECRET => configuration
  * PORT & BASE_SERVER_URL & BASE_API_URL & BASE_CLIENT_URL
  * CLOUD_NAME & CLOUD_API_KEY & CLOUD_API_SECRET => cloudinary configuration
```

## Install

Some basic Git commands are:

```
$ npm install
```

## Run the application for development

```
$ npm start
```

## Heroku Deployment

```
> Move devDependencies to dependencies
> Create a Procfile in the root directory of your application with the following command **web: npm run start:production**
```

## Languages & tools

- [Node](https://nodejs.org/en/)

- [Express](https://expressjs.com/)

- [Mongoose](https://mongoosejs.com/)

- [React](https://reactjs.org/)

- [Webpack](https://webpack.js.org/)

### Code Formatter

- Add a `.vscode` directory
- Create a file `settings.json` inside `.vscode`
- Install Prettier - Code formatter in VSCode
- Add the following snippet:

```json
{
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "files.eol": "\n",
  "prettier.jsxSingleQuote": true,
  // Enable this once you're on the client folder/react
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```
