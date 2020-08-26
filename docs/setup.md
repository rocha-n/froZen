# Setting this project up

This part describes what has been done, in a step by step manner, to have this project ready to develop on.

## Pre-requisites

### Install node.js
Just go to the website, download the latest binary and install it

### Installing angular-cli
Use the `npm` program, that comes with node.js
`> npm install -g @angular/cli`

### Setting up a code versionning tool
For this project, I used GitHub.
Once the repo created on the website, I cloned it locally
TODO: Clarify the difference between clone and fork in this context

### Creating a folder for the project
Now, just create a folder for the project using the `ng` command.
`> ng new <projectName>`

For the sake of clarity, I decided not to use Angular routing, and chose CSS stylesheets.

### Launching the project
Now, to be sure that everything went right, just move to the project folder, and launch it locally
```
> cd <projectName>
> ng serve
```

If all went well, you should now see the project page

### Setting up the IDE
For this project, I used VSCode.
Just download and install it.
Once it's done, open it and install the Angular extension.
To do that, go to `View -> Extensions` and select `Angular Essentials`

