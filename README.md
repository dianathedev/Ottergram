## Ottergram

<p> Web application that displays images using various techniques.
This application is written in Javascript and uses HTML and CSS </p>

## Installation and Execution
### Prerequisites

* Atom text editor (Any Editor)
    <p> Install at > https://atom.io/ </p>

* Atom Plug-ins (Optional)
   <p> Open Atom and navigate to its Settings screen. On a Mac, this is done by choosing Atom → Preferences... On Windows, you can access it via File → Settings or using the keyboard shortcut Ctrl-. On the lefthand side of the Settings   screen, click + Install. Install emmet,atom-beautify, autocomplete-paths, api-docs, linter, linter-csslint, linter-htmlhint and linter-eslint. </p>

* Google Chrome Browser
    <p> For latest version > www.google.com/chrome/browser/desktop </p>

* Install `npm` Packages:
<p> Open your terminal and enter the following command </p>

    > npm install -g browser-sync

### Running the application:
**Navigate to Project folder in the terminal-**

	> cd Ottergram

**Open another terminal and use following commands**

	> cd Ottergram
	> browser-sync start --server --browser "Google Chrome"--files "stylesheets/*.css, *.html"

**Web server will be up and running on your local machine at -**

	> http://localhost:3000
