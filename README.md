# L06 Practice Hands On

# Directions
For your Lesson 6 Practice Hands-On, you are going to be practicing creating a module, moving files, and changing file paths. You will be working with the below starter-project. Please download it before continuing. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

Setup
Start off by downloading the starter project and unzipping it. The starter project will be in a folder named angular-L6-handson.

Starter Project

After unzipping, move the starter project folder to the FEFAngular folder located inside the FullStackWeb folder and rename it from angular-L6-handson to L06HandsOn.

Open up your terminal/command prompt.

Run the following to navigate to your Desktop

cd Desktop
Next, navigate to the FullStackWeb directory in your terminal.

cd FullStackWeb
Then, navigate to the FEFAngular directory in your terminal.

cd FEFAngular
Navigate into the L06HandsOn directory:

cd L06HandsOn
Now that you are in the L06HandsOn directory, run the following:

npm install
Next, run the following:

npm install typescript@2.8 --save-dev
Requirements
Step 1
Create a new module using the Angular CLI called message-form.
Try to use the shortcuts of g and m when using the Angular CLI.
Change the file structure. Move the message-form folder and its files into the message-form module.
The message-form folder should live within a components folder.
Change the import statement to correctly import the Message model within the MessageForm component.
Import the MessageFormComponent into the MessageFormModule.
Add the MessageFormComponent to the necessary arrays within the MessageFormModule.
Add the necessary FormsModule references within the MessageFormModule.
Import the MessageFormModule into the AppModule correctly.
Within the AppModule, add and remove the necessary values from the declarations and imports arrays to reflect the use of the MessageFormModule.
You will need to remove the references to the MessageFormComponent.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
