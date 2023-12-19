# stay-fit

Stay-fit is a web application project developed in React, MaterialUI, and uses RapidAPI to provide a platform that facilitates the search and exploration of physical exercises based on the name and body part you want to train.

## Demo

![Stay-fit Demo](https://gitlab.com/olooeez/stay-fit/-/raw/main/img/demo.png)

You can find a live demo by clicking [here](https://stay-fit-reactjs.netlify.app).

## Prerequisites

Before you begin, make sure you have the following requirements installed on your machine:

1. **Node.js**: Node.js is a platform that allows the execution of JavaScript code on the server. You can download Node.js from the [official website](https://nodejs.org/) and follow the installation instructions for your operating system.

2. **NPM**: NPM is the package manager for Node.js. It is installed along with Node.js and is necessary for installing project dependencies.

## Installation and Development

### Step 1: Clone the repository

Clone this repository to the desired folder on your machine:

```bash
git clone https://gitlab.com/olooeez/stay-fit.git
```

### Step 2: Install dependencies

Navigate to the project directory and install the dependencies using NPM:

```
cd stay-fit
npm install
```

### Step 3: Configure RapidAPI

Stay-fit uses RapidAPI to get exercise details. Make sure you have an account on RapidAPI and obtain the necessary API key to make requests. You need to configure this key in the .env file at the root of the project as follows:

```
REACT_APP_RAPID_API_KEY=YourRapidAPIKey
```

### Step 4: Run the application

After configuring the RapidAPI key, you can start the application locally with the following command:

```
npm start
```

The application will be available in your browser at [localhost:3000](http://localhost:3000).

## Contributing

If you wish to contribute to this project, feel free to open a merge request. We are open to all forms of contribution!

## License

This project is licensed under the [Apache 2.0 License](https://gitlab.com/olooeez/stay-fit/-/blob/main/LICENSE). Refer to the LICENSE file for more details.
