# Meteor packages we need
Basic packages needed to start a nice project

**Remember** to remove [insecure](https://atmospherejs.com/meteor/insecure) and [autopublish](https://atmospherejs.com/meteor/autopublish) packages.

## Table of contents
- **[Quick copy](#quick-copy)**
- [Global](#global)
- [API](#api)
- [CSS](#css)
- [Collections](#collections)
- [Emails](#emails)
- [Files](#files)
- [Forms](#forms)
- [Methods](#methods)
- [Mobile](#mobile)
- [Router](#router)
- [SEO](#seo)
- [Streaming](#streaming)
- [Templates](#templates)
- [Users](#users)
- [UX](#user-experience)

## Quick copy
To get some of those packages in a single copy/paste. Remove unnecessary ones :
```
meteor remove insecure autopublish
```
Then add those ones :
```
meteor add stevezhu:lodash reactive-var tracker session momentjs:moment fourseven:scss twbs:bootstrap fortawesome:fontawesome aldeed:collection2 dburles:collection-helpers matb33:collection-hooks ongoworks:security aldeed:autoform mdg:validated-method kadira:flow-router kadira:blaze-layout arillo:flow-router-helpers settinghead:auto-nprogress zimme:active-route manuel:viewmodel aldeed:template-extension raix:handlebar-helpers juliancwirko:s-alert
```

## Global
- [stevezhu:lodash](https://atmospherejs.com/stevezhu/lodash): Lodash *(remember to add `_ = lodash;` to override underscore)*
- [reactive-var](https://atmospherejs.com/meteor/reactive-var): Creates reactive data source
- [tracker](https://atmospherejs.com/meteor/tracker): Creates reactive computation
- [session](https://atmospherejs.com/meteor/session): Session variable
- [momentjs:moment](https://atmospherejs.com/momentjs/moment) Moment.js (official): parse, validate, manipulate, and display dates
- [digilord:faker](https://atmospherejs.com/digilord/faker): Faker.js packaged for Meteor. Generate massive amounts of fake data
- [meteorhacks:npm](https://atmospherejs.com/meteorhacks/npm): Use npm modules with your Meteor App
- [percolate:synced-cron](https://atmospherejs.com/percolate/synced-cron): Allows you to define and run scheduled jobs across multiple servers

## API
- [nimble:restivus](https://atmospherejs.com/nimble/restivus): Create authenticated REST APIs in Meteor 0.9+ via HTTP/HTTPS. Setup CRUD endpoints for Collections.

## CSS
- [fourseven:scss](https://atmospherejs.com/fourseven/scss): Compiles Sass files with node-sass and it has options to control the load order of Sass files and use Autoprefixer on the generated CSS.
- [twbs:bootstrap](https://atmospherejs.com/twbs/bootstrap): Twitter Bootstrap
- [fortawesome:fontawesome](https://atmospherejs.com/fortawesome/fontawesome): FontAwesome

*Note that Meteor already has a less compiler by default*

## Collections
- [aldeed:collection2](https://atmospherejs.com/aldeed/collection2): Allows to attach a schema to a Mongo.Collection. Automatically validates against that schema when inserting and updating from client or server code.
- [reywood:publish-composite](https://atmospherejs.com/reywood/publish-composite): Flexible way to publish a set of related documents from various collections using a reactive join. This makes it easy to publish a whole tree of documents at once. The published collections are reactive and will update when additions/changes/deletions are made.
- [dburles:collection-helpers](https://atmospherejs.com/dburles/collection-helpers): Transform collections with helpers
- [matb33:collection-hooks](https://atmospherejs.com/matb33/collection-hooks): Extends Mongo.Collection with before/after hooks for insert/update/remove/find/findOne
- [ongoworks:security](https://atmospherejs.com/ongoworks/security): Logical security for client-originated MongoDB collection operations
- [tmeasday:publish-counts](https://atmospherejs.com/tmeasday/publish-counts): Publish the count of a cursor, in real time
- [meteorhacks:aggregate](https://atmospherejs.com/meteorhacks/aggregate): Proper MongoDB aggregations support *(server side, not reactive)*

## Emails
- [email](https://atmospherejs.com/meteor/email)

## Files
- [cfs:standard-packages](https://atmospherejs.com/cfs/standard-packages): File manipulation
- [cfs:gridfs](https://atmospherejs.com/cfs/gridfs): GridFS storage adapter for CollectionFS (storing files in database)

## Forms
- [aldeed:autoform](https://atmospherejs.com/aldeed/autoform): Adds UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation, better with **collection2** *(lot of inputs plugins for autoform available (file upload, autocomplete, selects, maps, etc.))*
- [shinn:autoform-file](https://atmospherejs.com/shinn/autoform-file): File upload for AutoForm **(temporary package, fork of broken original one, you should clone/keep it as your app content)**

## Methods
- [mdg:validated-method](https://atmospherejs.com/mdg/validated-method): A simple wrapper for Meteor.methods

## Mobile
- [crosswalk](https://atmospherejs.com/meteor/crosswalk): Makes your Cordova application use the Crosswalk WebView instead of the System WebView on Android
- [chriswessels:hammer](https://atmospherejs.com/chriswessels/hammer): A smart-package for integrating with Hammer.js for multi-touch gesture support in your Templates
- [gadicohen:reactive-window](https://atmospherejs.com/gadicohen/reactive-window): Reactive functions for window properties; width, scroll, etc.
- [mystor:device-detection](https://atmospherejs.com/mystor/device-detection): Client-Side Device Type Detection & Template Switching with Optional Meteor-Router Support
- [ccorcos:swipe](https://atmospherejs.com/ccorcos/swipe): A package for creating apps that swipe between pages

## Router
- [kadira:flow-router](https://atmospherejs.com/kadira/flow-router): Carefully Designed Client Side Router for Meteor
- [kadira:blaze-layout](https://atmospherejs.com/kadira/blaze-layout): Layout Manager for Blaze (works well with FlowRouter)
- [arillo:flow-router-helpers](https://atmospherejs.com/arillo/flow-router-helpers): Template helpers for flow-router
- [settinghead:auto-nprogress](https://atmospherejs.com/settinghead/auto-nprogress): A Meteor package that automatically shows a NProgress.js bar during DDP data exchanges.
- [zimme:active-route](https://atmospherejs.com/zimme/active-route): Active route helpers

**Below Iron Router config instead of Flow Router** : probably not the best choice
- *[iron:router](https://atmospherejs.com/iron/router): Router*
- *[multiply:iron-router-progress](https://atmospherejs.com/multiply/iron-router-progress): Add progress bar on the top of the screen*
- *[zimme:iron-router-auth](https://atmospherejs.com/zimme/iron-router-auth): Authentication and authorization for iron:router*

## SEO
- [manuelschoebel:ms-seo](https://atmospherejs.com/manuelschoebel/ms-seo): SEO helper for **Iron Router**
- [tomwasd:flow-router-seo](https://atmospherejs.com/tomwasd/flow-router-seo): A simple way to set the title and meta tags for sites using **Flow Router**

## Streaming
- [yuukan:streamy](https://atmospherejs.com/yuukan/streamy): Used for classic socket communication without needing a database (example : a chat)

## Templates
- [aldeed:template-extension](https://atmospherejs.com/aldeed/template-extension): Template hooks + inheritance and copy of template events/helpers
- [raix:handlebar-helpers](https://atmospherejs.com/raix/handlebar-helpers): Handlebar helpers *(as $last and $index for #each)*

**Below View model instead of default Blaze** : probably not the best choice (has some bugs / incompatibility with other packages)
- [manuel:viewmodel](https://atmospherejs.com/manuel/viewmodel): MVVM, two-way data binding, and components for Meteor. Similar to Angular and Knockout.

## Users
- [accounts-base](https://atmospherejs.com/meteor/accounts-base) || [accounts-ui](https://atmospherejs.com/meteor/accounts-ui)
- [accounts-password](https://atmospherejs.com/meteor/accounts-password) / [accounts-facebook](https://atmospherejs.com/meteor/accounts-facebook) / [accounts-google](https://atmospherejs.com/meteor/accounts-google) / *etc.*
- [alanning:roles](https://atmospherejs.com/alanning/roles): Role-based authorization
- [tmeasday:presence](https://atmospherejs.com/tmeasday/presence): Help track users' presence *(Visitors counter)*
- [mizzao:user-status](https://atmospherejs.com/mizzao/user-status): User connection and idle state tracking

## User experience
- [juliancwirko:s-alert](https://atmospherejs.com/juliancwirko/s-alert): Simple and fancy notifications / alerts / errors for Meteor
