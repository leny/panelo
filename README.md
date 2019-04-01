# panelo

> A CLI-dashboard for your npm packages

* * *

> ☝️ **NOTE:** this package is a rewrite of an old package of mine, [tablodbò](https://www.npmjs.com/package/tablodbo)

* * *

## How it works ?

For each npm package of the given user, **tablodbò** will outputs these informations : name, version, ESM compatibility, build status (on Travis), dependencies update status, dev dependencies update status, last month's downloads on npm, npm stars and dependents packages amount.

## Usage

### Installation

Thus its discouraged, you can install the package globally with the following command:

	npm install -g panelo
	
#### Usage

Simply run the following command:

	panelo [YOUR_NPM_NICKNAME]
	
### With `npx`

Using panelo with npx is really easy:

	npx panelo [YOU_NPM_NICKNAME]
	
* * *

## License
Copyright (c) 2019 Leny  
Licensed under the MIT license.
