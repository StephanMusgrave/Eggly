# Testing framework for Lystable

## Unit Tests

### Directory: tests/unit

## End to End Tests

### Directory: tests/e2e

| Protractor:  | Protractor is an end-to-end test framework for AngularJS applications. Protractor is a Node.jsprogram built on top of WebDriverJS. Protractor runs tests against your application running in a real browser, interacting with it as a user would. |
|--|--|
|  | http://angular.github.io/protractor/#/ |
| $ sudo npm install -g protractor | This will install two command line tools, protractor and webdriver-manager. Try running protractor --version to make sure it's working. |
| $  sudo webdriver-manager update | The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries |
| $  webdriver-manager start | This will start up a Selenium Server and will output a bunch of info logs. Your Protractor test will send requests to this server to control a local browser. You can see information about the status of the server at:  http://localhost:4444/wd/hub. |
|  | create spec file eg  todo-spec.js and the configuration file eg conf.js |
| $ protractor conf.js | in a separate window.  You should see a Chrome browser window open up and navigate to the todo list in the AngularJS page, then close itself (this should be very fast!). The test output should be 1 test, 2 assertions, 0 failures. Congratulations, you've run your first Protractor test! |


## Features tests

### Directory: tests/features






| Karma:                         | http://karma-runner.github.io/0.12/intro/installation.html |
|--------------------------------|------------------------------------------------------------|
|  | Karma just launches a HTTP server, and generates the test runner HTML file. So for testing purposes you can use pretty much anything you like |                                              |
| $ npm install karma --save-dev  | Install Karma                                              |
| $ npm install karma-jasmine karma-chrome-launcher --save-dev  | This will install karma, karma-jasmine and karma-chrome-launcher packages into node_modules in your current working directory and also save these as devDependencies in package.json, so that any other developer working on the project will only have to do npm install in order to get all these dependencies installed. |
| $ sudo npm install -g karma-cli  | Typing ./node_modules/karma/bin/karma start sucks and so you might find it useful to install karma-cli globally.  Then you can run Karma simply by karma from anywhere and it will always run the local version. |
| $  karma start  | http://localhost:9876/ |


| Jasmine:  | http://jasmine.github.io/2.1/introduction.html |
|--|--|
| Using Jasmine with Python: | http://jasmine.github.io/2.1/python_egg.html |
| $ pip install jasmine | You can install Jasmine using pip or by adding it to yourrequirements.txt. |
| $  jasmine-install | Initialise a project for Jasmine by creating a spec directory and configuration yaml |
| $  jasmine | http://localhost:8888/ |

|  |  |
|  |  |










[protractor]: https://github.com/angular/protractor
[jasmine]: http://pivotal.github.com/jasmine/
[karma]: http://karma-runner.github.io

|  |  |
|--|--|
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |



