# Ember-CLI-Opinionated

*The Enhanced Ember Application Blueprint*

This addon is the Quick Start guide to the best tools the Ember community has to offer! Ember-CLI-Opinionated takes on 
common decisions you need to make to get the most out of your app and gives you an answer. The following questions 
are all answered by this addon:

1. *SCSS* vs LESS vs CSS?
2. How can we get code coverage?
3. How do we put styles in our pods?
4. How can we track app performance?
5. What's the best way to do date parsing in Ember?
6. How can we implement feature flags?

...and more!

All you have to do is sit back, relax, and let Ember-CLI-Opinionated do all the hard work for you. When we're done,
your app will be even better than a barebones Ember app (which is already pretty sweet!); it'll be a lean, mean,
code-generating machine. Watch your productivity increase and your architecture meetings decrease, all at the same time!

## Installation

The following command will install this addon and run the included blueprint to give you maximum awesomeness:

`ember install ember-cli-opinionated`

Subsequent updates to this addon can be pulled in by updating the version of this package and running the following:

`ember g ember-cli-opinionated`

This will execute the included blueprint, setting up your app for the win!

Once you have installed this package, you will need to go through some minor setup to begin utilizing the included
addons. Your app should be fully operational in the meantime, but the addons won't be usable until setup is completed.
Please refer to the sections below and the individual READMEs for information on each addon's setup (where applicable).

## Compatibility

Each of the included addons has its own compatibility with different versions of Ember, Ember-CLI, and so on. We
recommend checking the individual repositories for more information to make sure your app is compatible with the latest
versions of each project. The intent of this addon is to enhance a brand-new app generated with Ember-CLI, but
that doesn't mean you can't juice up your existing application, either!

As of now, Ember 1.13+ should be supported without issues. Earlier versions of Ember may also be supported, 
but have not been explicitly tested. If you are on 1.12-, please test and let us know if there are issues.

## What's Inside The Box?

Ember-CLI-Opinionated packs a number of essential addons to use in your Ember application. Below you will find each
dependency listed along with a short description and a link to the main repositories. Any further dependencies
installed by the addons' blueprints will be listed below the section header. Additionally, the amount of
extra setup needed to begin using the addon is judged for you. Our rating system is as follows:

_No Setup_ - You can begin using this addon immediately without any additional configuration necessary.
_Trivial Setup_ - You may have to add 1-2 easy lines of code to complete setup.
_Minor Setup_ - A bit of configuration is required (usually in `config/environment.js`), but the process is 
straightforward and explained well in their README.
_Major Setup_ - A significant amount of work is needed to begin using this addon. Our goal is not to include
any projects that would receive this rating, as it is counter-intuitive to the quick-start nature of this project.

### [ember-cli-blanket](http://jhawk.co/ember-cli-blanket)
_Minor Setup_

_Additional Install: [`blanket`](http://jhawk.co/blanket-js)_

Wraps Blanket.js to provide code coverage for Ember apps. Easy integration with 
[`ember-cli-pretender`](http://jhawk.co/ember-cli-pretender) or [`ember-cli-mirage`](http://jhawk.co/ember-cli-mirage).
The [README](https://github.com/sglanzer/ember-cli-blanket/blob/master/README.md) has details on configuration of the addon.

### [ember-cli-sass-pods](http://jhawk.co/ember-cli-sass-pods)
_Trivial Setup_

_Additional Install: [`ember-cli-sass`](http://jhawk.co/ember-cli-sass)_

Enables usage of SCSS styles in pod directories. Also includes generators for these files!

### [ember-cpm](http://jhawk.co/ember-cpm)
_No Setup_

_Additional Install: N/A_

Provides Computed Property Macros, including 
[Composable Macros](https://github.com/cibernox/ember-cpm/blob/master/README.md#composable-computed-property-macros)!

### [ember-feature-flags](http://jhawk.co/ember-feature-flags)
_Minor Setup_

_Additional Install: N/A_

Provides an injected `features` property to your routes, controllers, and components. 

The [README](https://github.com/kategengler/ember-feature-flags/blob/master/README.md) details the easy ENV config.

### [ember-metrics](http://jhawk.co/ember-metrics)
_Minor Setup_

_Additional Install: N/A_

Allows you to send data to multiple analytics integrations without re-implementing new API.

Check out the [README](https://github.com/poteto/ember-metrics/blob/develop/README.md) for information on how to 
set up the instrumentation to your favorite analytics reporting tool.

### [ember-moment](http://jhawk.co/ember-moment)
_No Setup_

_Additional Install: [`moment`](http://jhawk.co/moment-js)_

Provides template helpers and computed property macros for date parsing, as well as 
including `moment.js` as an ES6 module import.

### [ember-responsive](http://jhawk.co/ember-responsive)
_No Setup_

_Additional Install: N/A_

Uses responsive media queries to inject screen layout information throughout Ember applications.
Needs Polyfill for [compatibility](http://caniuse.com/#feat=matchmedia) with IE 8/9 or Opera Mini.

### [ember-suave](http://jhawk.co/ember-suave)
_No Setup_

_Additional Install: N/A_

Enforce code styles using [`JSCS`](http://jhawk.co/js-cs). Defaults to the 
DockYard [JavaScript](https://github.com/dockyard/styleguides/blob/master/javascript.md) and 
[Ember](https://github.com/dockyard/styleguides/blob/master/ember.md) Style Guides, but rules are configurable.

## Contributing

[CONTRIBUTING.md](https://github.com/elwayman02/ember-cli-opinionated/blob/master/CONTRIBUTING.md) details how to contribute to this project.

### Installation

* `git clone` this repository
* `npm install`
* `bower install`

### Running

* `ember s` or `ember server`
* Visit your app at http://localhost:4200.

### Running Tests

* `npm test`
