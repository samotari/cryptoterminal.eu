# cryptoterminal.eu

This repository contains the source files and build scripts for the [CryptoTerminal website](https://samotari.github.io/cryptoterminal.eu/).

* [Requirements](#requirements)
* [Getting Started](#getting-started)
* [How to Update the Website](#how-to-update-the-website)


## Requirements

The following is a list of requirements needed to contribute to this project.

* [nodejs](https://nodejs.org/) - For Linux and Mac install node via [nvm](https://github.com/creationix/nvm).
* [make](https://www.gnu.org/software/make/)


## Getting Started

Before continuing, be sure to download and install the project [requirements](#requirements).

Get the code:
```bash
git clone git@github.com:samotari/cryptoterminal.eu.git
```

Install dependencies:
```bash
cd cryptoterminal.eu
npm install
```

To build and serve the homepage locally:
```bash
npm run build && npm run server
```
Then open your browser to [localhost:3000](http://localhost:3000).


## How to Update the Website

The homepage is hosted via [GitHub pages](https://pages.github.com/). The [docs directory](https://github.com/samotari/cryptoterminal.eu/tree/master/docs) in this repository contains the web files that are served to visitors of cryptoterminal.eu.

To create a new commit of the latest build:
```bash
npm run commit
```
* Write a message that summarizes the changes made.
* Open a pull-request to the upstream master branch.
* Once merged, the changes should be visible within a few minutes.


## License

This project is licensed under the [GNU Affero General Public License v3 (AGPL-3.0)](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-(agpl-3.0)).
