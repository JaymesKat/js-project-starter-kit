# js-project-starter-kit
This project demonstrates how to setup a development environment when working in javascript. Adapted from PluralSight Course: "Building a JavaScript Development Environment" by Cory House

## Editor Configurations
Development teams working on projects usually have agreed-upon coding conventions they follow.. Editor configuration provide a great way to keep consistency across different editors.

In this project, we have adopted the following conventions;
- end_of_line = lf
- insert_final_newline = true
- trim_trailing_whitespace = true 
- charset = utf-8
- indent_style = space
- indent_size = 2

For more information on this topic, visit this [link](https://editorconfig.org/)

## Package Management
In almost every project a team works on, they will make use of different packages for different purposes, this would necessitate the use of a package manager to handle all the project package dependencies, keeping track of all their versions within the package.json file

The most popular package manager is `npm`, which we use on this project

To add `npm`, install the `node` available [here](https://nodejs.org/en/)

## Setting up a Development Server
Working with JavaScript, in the majority of cases will require that you work with a browser which will display the changes you make to your application. For this reason, you would need a web server. Setting up a web server can also help you share your work across a team.

Options available include;
- http-server [link](https://www.npmjs.com/package/http-server)
- live-server  [link](https://www.npmjs.com/package/live-server)
- express [link](https://expressjs.com/)
- browser-sync [link](https://browsersync.io/)
and more;

For this environment, we are using `express` 

- Install express by running `npm install -g express` in your terminal
