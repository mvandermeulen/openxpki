# myapp

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

### Node.js

    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
    cd core/htdocs_source
    nvm install

### Ember CLI

    npm install -g ember-cli

## Installation

* `git clone <repository-url>` this repository
* `cd myapp`
* `npm install`

## Running / Development

To run the web UI locally you have to:

1. Start an OpenXPKI backend via Docker or Vagrant. It's expected to listen on localhost:8080
2. Now run the Ember based web UI with live reload (on code changes) via:
   `npm run serve` (this calls "ember serve ..." and proxies AJAX requests to localhost:8080)
3. Visit the web UI at [http://localhost:4200](http://localhost:4200).
4. Visit tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
