
{
  "name": "hospitalrun",
  "version": "0.9.1",
  "description": "Ember front end for HospitalRun",
  "homepage": "http://hospitalrun.io",
  "directories": {
    "doc": "doc",
    "test": "tests"
  },
  "scripts": {
    "build": "./script/build",
    "start": "./script/server",
    "test": "./script/test"
  },
  "repository": {
    "type": "git",
    "url": "git@github.com:HospitalRun/hospitalrun-frontend"
  },
  "engines": {
    "node": ">= 0.10.0"
  },
  "author": "John Kleinschmidt",
  "contributors": [
    "Joel Worrall",
    "Joel Glovier"
  ],
  "license": "GPL-3.0",
  "devDependencies": {
    "body-parser": "^1.14.2",
    "broccoli-asset-rev": "^2.4.1",
    "broccoli-export-text": "0.0.2",
    "broccoli-funnel": "^1.0.1",
    "broccoli-manifest": "0.0.7",
    "broccoli-merge-trees": "^1.0.0",
    "broccoli-serviceworker": "0.0.9",
    "ember-ajax": "0.7.1",
    "ember-cli": "^2.4.1",
    "ember-cli-active-link-wrapper": "0.0.4",
    "ember-cli-app-version": "^1.0.0",
    "ember-cli-babel": "^5.1.5",
    "ember-cli-dependency-checker": "^1.2.0",
    "ember-cli-deprecation-workflow": "0.1.6",
    "ember-cli-fake-server": "0.2.4",
    "ember-cli-htmlbars": "^1.0.1",
    "ember-cli-htmlbars-inline-precompile": "^0.3.1",
    "ember-cli-inject-live-reload": "^1.3.1",
    "ember-cli-qunit": "^1.2.4",
    "ember-cli-release": "1.0.0-beta.1",
    "ember-cli-sass": "^5.2.1",
    "ember-cli-sri": "^2.1.0",
    "ember-cli-uglify": "^1.2.0",
    "ember-data": "^2.4.0",
    "ember-disable-proxy-controllers": "^1.0.1",
    "ember-export-application-global": "^1.0.4",
    "ember-i18n": "4.2.0",
    "ember-load-initializers": "^0.5.0",
    "ember-pouch": "^3.1.0",
    "ember-rapid-forms": "1.0.0-beta4",
    "ember-resolver": "^2.0.3",
    "ember-select-list": "0.9.5",
    "ember-simple-auth": "^1.1.0-beta.3",
    "ember-suave": "1.2.3",
    "ember-truth-helpers": "1.2.0",
    "ember-validations": "2.0.0-alpha.4",
    "express": "^4.8.5",
    "glob": "^7.0.0",
    "hospitalrun-dblisteners": "0.9.1",
    "hospitalrun-server-routes": "0.9.1",
    "loader.js": "^4.0.0",
    "nano": "6.2.0",
    "request": "2.69.0"
  },
  "dependencies": {
    "ember-radio-buttons": "^4.0.1"
  },
  "ember-addon": {
    "paths": [
      "lib/pouch-fixtures"
    ]
  }
}
