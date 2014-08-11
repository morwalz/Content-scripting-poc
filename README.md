Prerequisites (Window Environment)
SourceTreeApp (Git client)
Git bash (command line client) - Choose the option which will update the system variable/ PATH entry of window environment.
Ruby - Use window installer
Python - Make sure that python version is less than 3.0. Recommended version is 2.7.6. Also update path entry to point the installation directory.
NodeJS
Microsoft Express Visual Studio 2012 - This is required to setup c/c++ compilation environment and update the .NET env. It will internally be used by npm modules required for generating CRX file.
Compass installation - Run the following command in git bash console
 $ gem update --system
 $ gem install compass
NPM global installation - Run the following command in git bash console
 $ npm -g install grunt
 $ npm -g install grunt-cli
 $ npm -g install bower
 $ npm -g install coffee
 $ npm install -g requirejs
Setting up project
Clone the git repo directly in window drive. (Avoid nested path, that may create problem in next step)
Navigate to project directory and run the following command for project setup. It will download multiple node modules and dependencies.
$ npm install
Now you can run the following commands
// project building command
$ grunt

find dist folder and upload to chrome and test on google site. u will see red background.

find file to contentscript.coffeee to make change script to be injected in google.
