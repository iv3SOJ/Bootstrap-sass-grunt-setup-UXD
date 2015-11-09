# Bootstrap-sass-grunt-setup-UXD
### Quicklink

---

click here to go to [Bootstrap-sass grunt setup - UXD Documentation](http://iv3soj.github.io/Bootstrap-sass-grunt-setup-UXD/)

## Project Setup


* Download Zip file
* Set path where will you create project folder 
* Rename project folder 
* Navigate your project folder directory inside the Command Prompt or Git Bash. ex.(`cd C:\Users\Name\MyProject`)

## Bower Installation

Type this in your command prompt or Git Bash then Enter.

`bower install bootstrap-sass --save`

## Configuration

Open config.json using notepad

Change the value of "location" to the directory of your project.

ex. `{ "location" : "C:\\Users\\Me\\MyProject" }`

*use double back slashes (\\\\) to escape the backslash string*

## Grunt Setup

Next, we need to install grunt and all the required modules / plugins that we need.

## Option A:

`npm install grunt`

`npm install matchdep --save-dev`

`npm install grunt-contrib-copy --save-dev`

`npm install grunt-contrib-uglify --save-dev`

`npm install grunt-contrib-watch --save-dev`

`npm install grunt-open --save-dev`

`npm install grunt-express --save-dev`

`npm install grunt-parallel --save-dev`

`npm install grunt-rev --save-dev`

`npm install grunt-sass --save-dev`

## Option B:

Double click **dependencyInstaller.bat**

*This file will install all the required dependencies for this setup* 


## Viewing Your Project

To view your project, just open your command prompt

`WINDOW + R`, type `cmd`

Locate your project folder

example: `C:\Users\Me\MyProject`

and type `grunt`