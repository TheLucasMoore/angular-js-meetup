# Denver AngularJS Meetup Notes

(KeystoneJS - a javascript CMS)

twctv.com - built with backboneJS

## Angular CLI by @Geoffilippi

Angular 1.5 Component Router is a backport of Angular 2 router

Angular CLI runs on Ember CLI
Ember is used by many rubyists

## Angular 2 Code Generators:
- Applications
   - Generate a new app
   - $ ng new PROJECT_NAME
   - $ cd PROJECT_NAME
   - $ ng serve -> angular aware lite server (johnpapa/liteserver)

- Components
  - $ ng generate component my-new-component-name
  - import into root component
  - create a directive array
- Directives
- Routes
  - $ ng generate route my-new-route
  - not entirely wired up yet, however.
  - + is to denote a lazy-loading route
  - Components Generate with the Route! So don't -g the component alone. It will be generated with the route.
- Unit Tests
- Services
  $ ng generate service my-new-service-name

# Getting Started
- $ npm install -g angular-cli
- $ ng --help

## TOOLS

Built in CLI tools.

- Build (instead of Yeoman) 
  - $ ng build
- Unit Tests, Protractor Tests 
  - $ ng test
  - these tests are in PROJECT_NAME.component.spec.ts
- Deployment
- Lint - verified against John Papa style guide
  - $ ng-lint passes or it doesn't
- Type Definitions
- Code Formatting (can break the linter)
- CSS Preprocessing
- End to End Testing 
  - $ ng e2e
  - in e2e/app.po.ts -> Protractor Tests for browser tests

# To upgrade
$ npm uninstall, clean cache and then run:

$ npm install -g angular-cli@latest

$ ng init (this will tell you what you must change to upgrade angular. This is a bleeding edge feature. A few days old.)

# Application Filestructure
./src/app
  // set of component typescripts

# Bootstrapping
Done in main.ts. Boostraps the main component.

# Configs
root - Angular-CLI.json points to all the configs

