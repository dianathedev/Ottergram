## Overview

<p> Web application that allows students to vote on how likely it is that a given topic will show up on the next test.
This application is written in Javascript and uses JQuery and AJAX </p>

## Installation and Execution
### Prerequisites

* Node.js
    <p> For latest version download from https://nodejs.org/en/download/ </p>

* Atom text editor (Any Editor)
    <p> Install at > https://atom.io/ </p>

* Atom Plug-ins (Optional)
   <p> Open Atom and navigate to its Settings screen. On a Mac, this is done by choosing Atom → Preferences... On Windows, you can access it via File → Settings or using the keyboard shortcut Ctrl-. On the lefthand side of the Settings   screen, click + Install. Install emmet,atom-beautify, autocomplete-paths, api-docs, linter, linter-csslint, linter-htmlhint and linter-eslint. </p>

* Google Chrome Browser
    <p> For latest version > www.google.com/chrome/browser/desktop </p>

* Install `npm` Packages:
<p> Open your terminal and enter the following command </p>

    > npm install -g json-server
    > npm install -g browser-sync

### Running the application:
**Navigate to Project folder in the terminal-**

	> cd Ottergram
**Type in the following command- to start the json server**

	> json-server --port=3002 --watch db.json
**Open another terminal and use following commands**

	> cd Ottergram
	> browser-sync start --server --files "*.html, stylesheets/*.css, scripts/*.js"

**Web server will be up and running on your local machine at -**

	> http://localhost:3000

## Technical Details
#### Purpose:
Students can vote on how likely it is that a given topic will show up on the next test.

##### Functionality:
* Users can register with their school email_id and create a own password
* Once students registered, they can login to like or dislike a particular topic.
