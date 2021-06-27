# MajesticBS4_AdminTemplate
Introduction
Majestic Admin is a responsive HTML template that is based on the CSS framework Bootstrap 4 and it is built with Sass. Sass compiler makes it easier to code and customize. If you are unfamiliar with Bootstrap or Sass, visit their website and read through the documentation. All of Bootstrap components have been modified to fit the style of Majestic Admin and provide a consistent look throughout the template.

Before you start working with the template, we suggest you go through the pages that are bundled with the theme. Most of the template example pages contain quick tips on how to create or use a component which can be really helpful when you need to create something on the fly.

Note: We are trying our best to document how to use the template. If you think that something is missing from the documentation, please do not hesitate to tell us about it. If you have any questions or issues regarding this theme please email us at support@bootstrapdash.com
Getting started
You can directly use the compiled and ready-to-use the version of the template. But in case you plan to customize the template extensively the template allows you to do so.

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations:

Majestic/
├── template/
      ├── css/
      ├── fonts/
      ├── images/
      ├── js/
      ├── pages/
      ├── partials/
      ├── index.html
      ├── scss/
      ├── vendors/
      ├── gulpfile.js
      ├── package.json                           
      ├── documentation/
├── CHANGELOG.md
Note: The root folder denoted further in this documentation refers to the 'template' folder inside the downloaded folder

We have bundled up the vendor files needed for demo purpose into a folder 'vendors', you may not need all those vendors or may need to add more vendors in your application. If you want to make any change in the vendor package files, you can either change the src path for related tasks in the file gulpfile.js and run the task bundleVendors to rebuild the vendor files or manually edit the vendor folder.

Installation
You need to install package files/Dependencies for this project if you want to customize it. To do this, you must have node and npm installed in your computer.

Installation guide of the node can be found here. As npm comes bundled with a node, a separate installation of npm is not needed.

If you have installed them, just go to the root folder and run the following command in your command prompt or terminal (for the mac users).

npm install
This will install the dev dependencies in the local node_modules folder in your root directory.

Then you will need to install Gulp. We use the Gulp task manager for the development processes. Gulp will watch for changes to the SCSS files and automatically compile the files to CSS.

Getting started with Gulp is pretty simple. The Gulp site is a great place to get information on installing Gulp if you need more information. You need to first install Gulp-cli in your machine using the below command.

npm install -g gulp-cli
This installs Gulp-cli globally to your machine. The other thing that Gulp requires, which, is really what does all the work, is the gulpfile.js. In this file, you set up all of your tasks that you will run.

Don't worry. We have this file already created for you!

To run this project in development mode enter the following command below. This will start the file watch by gulp and whenever a file is modified, the SCSS files will be compiled to create the CSS file.

gulp serve
It is important to run gulp serve command from the directory where the gulpfile.js is located.
