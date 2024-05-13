# WebdriverIO Tests for Telnyx.com dockerised

This repository contains docker.yml file, which runs the tests based on webdriver.io framework using docker image, from the Docker Hub. You can observe this tests executing on github actions after push request.  

Also there is a Dockerfile in this repository, which you can pull to your system and run the project with tests locally.  


## Getting Started

Follow these instructions to set up the project locally. These steps will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need Node.js and npm installed on your computer. If you do not have these installed, follow the instructions from the [Node.js official website](https://nodejs.org/).


### Check Node.js installation
node --version

### Check npm installation
npm --version

### Installation  

Clone the repository to your local machine:
```
git clone https://github.com/kiteamismorethansport/wdio_telnyx.com_tests_dockerised.git  
cd wdio_telnyx.com_tests_dockerised.git  
```
Install the necessary packages:
```
npm install
```

### To run tests locally build docker image from Dockerfile, and run it.  

First make sure, that you have docker desktop installed and running.

Command to build docker image:
```  
docker build -t webdriverio-tests .  
```
Command to run and execute tests, using docker image locally: 
``` 
docker run --rm webdriverio-tests
```

### To run tests on a github actions you need to create repository, and to push this cloned project to your newly created repository. Github actions will start the flow, and the tests will be running.