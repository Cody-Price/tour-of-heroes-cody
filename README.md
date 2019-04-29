# Tour of Heroes

Tour of Heroes is an Angular 7 application that allows the user to add/delete/edit various heroes from a heroes database while providing dynamic routing to aforementioned heroes.

This project was my first Angular project that I have ever written as part of the Angular 7 CLI tutorial. I assigned myself this project in order to expand my programming vocabulary.

### Demo

![toh-anim](https://user-images.githubusercontent.com/40974490/56928660-c38ccf00-6a94-11e9-9cfa-16cd3f52e9d4.gif)

### Prerequisites

This application asumes that you have the following installed on your machine:

- [node](https://www.npmjs.com/get-npm)
- [npm](https://www.npmjs.com/get-npm)
- [Angular CLI](https://github.com/angular/angular-cli)

### Setup

1. Fork this repository by clicking on the "Fork" button on the top-right of this page.

2. Open your terminal and navigate to the working directory (for instructions on how to navigate through your terminal see [here](https://ccrma.stanford.edu/guides/planetccrma/terminal.html)) you want your new directory to be located, and enter the following command:
`git clone https://github.com/YOUR_GITHUB_USERNAME_HERE/tour-of-heroes-cody`

3. Get into your new local copy of the Fetch directory:
`cd tour-of-heroes-cody`

4. And then add an `upstream` remote that points to the main repo:
`git remote add upstream https://github.com/Cody-Price/tour-of-heroes-cody`

5. Pull in the latest version of master from upstream (ie: the main repo):
`git pull upstream master`

7. Install dependencies:
`npm install`

### To run as Developer

1. Navigate into the VeterInformant directory and enter the following command:
`ng serve`

This will open up your default browser and run the application on localhost:4200

### Testing

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

This application is not yet in the testing phase, however if you would like to contribute, please see the <a href="#contributing">Contributing</a> section.

### Deployment

This application is not yet in the deployment phase, however if you would like to contribute, please see the <a href="#contributing">Contributing</a> section.

### Built With

- [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.
- [Angular](https://angular.io/) - Framework

<p id="contributing"></p>

### Contributing

1. Comment on a given issue you would like to undertake.

2. Checkout a new branch on your local machine (based on `upstream/master`)

3. Utilize rebase work flow (for Rebase workflow questions please reference at: `https://git-scm.com/docs/git-rebase`)

4. Push up changes to your forked repo branch and make necessary PR into forked repo's master

5. Request the Pull Request to the original repo following the PR template

6. Include a brief commit message that details the changes you have made

### Authors

- [Cody Price](https://github.com/cody-price) - Reimplementation and study
- [Angular](https://angular.io/) - Logic & Design

### License

This project requires no license

### Acknowledgments

I would like to thank the Charter Communications (Denver) Dev Team for inspiring me to learn and build on the Angular knowledge they were kind enough to help teach me. I'll keep the ball rolling!
