# cordova-vue-template
> Quick starter template for developing cordova applications using vue's powerful single file components.

## Getting Started
### Prerequisites
- [nodejs](https://nodejs.org/en/)
- cordova: `npm install -g cordova`
- browserify: `npm install -g browserify`

### Install
- Clone: `git clone https://github.com/elopezga/cordova-vue-template.git`
        
- Install depencencies: 
``` bash
cd cordova-vue-template
npm install
```
- Add platform: `cordova platform add browser`
- Build: `npm run-script build-dev`
- Run: `cordova run browser`

### Live Reload
With live reload you can save changing to your source code and a build will automatically trigger. The http server will display these changes after a page reload.

- Enable live reloading
`npm run-script dev-live`

Note: `dev-live` serves the www folder within the cordova project. Hence, cordova-specific functionality (including `cordova.js`) will not load. At the present, `dev-live` should be used only for developing vue-specific functionality.