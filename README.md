# AppKit
A Bootstrap and Vue.js based component library to facilitate rapid web application development


- - - -


## Installation

Install via NPM
``` bash
npm install git+ssh://DanTheCoder@bitbucket.org/helpcommerce/appkit.git --save-dev
```


Add the following to the vuejs *app.js* file (entry point)
``` javascript
import AppKit from 'appkit';
Vue.use(AppKit);
```

Add the following to the main *app.scss* file
``` scss
@import '~appkit/style/base';
```

- - - -


## Dependencies
Add the following dependencies to the package.json file
``` bash
"axios": "^0.18",
"bootstrap": "^4.2.1",
"vue": "^2.5.17",
"vue-router": "^3.0.1",
"vee-validate": "^2.1.0-beta.8",
```


**NB:** See each components source code or readme file on how to use it.


- - - -


## Development Setup

Clone the repo to a local folder
``` bash
git clone git@bitbucket.org:helpcommerce/appkit.git
```


Install dependencies
``` bash
npm install
```


Build for development: The built files will be outputted outside the current source folder, to a Laravel project that already has the package install (configure in package.json *--dest* as needed).
``` bash
npm run build:dev
```


Same as above, however, it will watch for changes and update them instantly.
``` bash
npm run build:watch
```


Build for production: files will be saved it ./dist folder
``` bash
npm run build:pro
```



- - - -



## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.