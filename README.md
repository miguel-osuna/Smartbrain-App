# Smartbrain-App

## :book: Description

Front-End application for Multiple Face Detection created with Create React App.

### :dart: Features

- SPA created with Create React App
- Styled with Tachyons and Particles.js
- Clarifai API

### :high_brightness: Visuals

![](img/smartbrain_example.png)

## :bulb: Getting Started

Follow the instructions below to get a copy of the project, whether it's for development or testing purposes.

### :clipboard: Prerequisites

You'll need Git and Node.js (which comes with npm) installed on your computer

```
node@v12.13.0 or higher
npm@6.13.1 or higher
git@2.17.1 or higher
```

### :computer: Installation

```
# Clone this repository
$ git clone https://github.com/miguel-osuna/Smartbrain-App

# Go into the repository from the terminal
$ cd Smartbrain-App

# Remove current origin repository
$ git remote remove origin
```

Create a .env with the content of .env_sample, replacing your client's url with the value in caps.

```
REACT_APP_HOME_PAGE =
localhost:3000
```

Create React App will be installed under _react-scripts_ when all dependencies are installed

```
# Install project dependencies
$ npm install

# Start and watch the project
$ npm start
```

_Once your server has started, go to `http://localhost:3000/` and you will see the website running on a Development Server._

## :rocket: Deployment

Once you are ready to deploy your project, read the [following tutorial](https://create-react-app.dev/docs/deployment/) to choose your hosting

Don't forget to replace the .env variables with your hosting url

```
REACT_APP_HOME_PAGE = https://app_name.hostingservice.com
```

## :wrench: Built With

- [React](https://reactjs.org/) - Front-End JavaScript library
- [Heroku](https://heroku.com/) - Hosting Platform

## :performing_arts: Authors

- **Miguel Osuna** - https://github.com/miguel-osuna

## :ledger: License

This project is licensed under the MIT License - see the LICENSE.md file for details.
