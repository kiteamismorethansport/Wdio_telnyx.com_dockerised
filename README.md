# WebdriverIO Tests for Telnyx.com with Allure Reporting

This repository contains docker.yml file which runs docker image from the Docker Hub with webdriver.io tests for telnyx.com website on github actions.

## Getting Started

Follow these instructions to set up the project locally. These steps will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need Node.js and npm installed on your computer. If you do not have these installed, follow the instructions from the [Node.js official website](https://nodejs.org/).

```bash
# Check Node.js installation
node --version

# Check npm installation
npm --version
Installation
Clone the repository to your local machine:

bash
git clone https://github.com/kiteamismorethansport/wdio_telnyx.com_tests_dockerised.git
cd wdio_telnyx.com_tests_dockerised.git
Install the necessary packages:

bash
npm install

### To run tests on a github actions you need to create repository, and to push this project to your newly created repository. Github actions will start the flow, and the tests will be running.