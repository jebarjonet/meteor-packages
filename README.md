# Meteor packages we need
Basic packages needed to start a nice project

**Remember** to remove [insecure](https://atmospherejs.com/meteor/insecure) and [autopublish](https://atmospherejs.com/meteor/autopublish) packages.

## Table of contents
- **[Quick copy](#quick-copy)**
- [Global](#global)
- [CSS](#css)
- [Collections](#collections)
- [Emails](#emails)
- [Files](#files)
- [Forms](#forms)
- [Mobile](#mobile)
- [Routes](#routes)
- [SEO](#seo)
- [Streaming](#streaming)
- [Templates](#templates)
- [Users](#users)

## Quick copy
To get some of those packages in a single copy/paste. Remove unnecessary ones :
```
meteor remove insecure autopublish
```
Then add those ones :
```
meteor add stevezhu:lodash reactive-var tracker session raix:handlebar-helpers fourseven:scss aldeed:collection2 reywood:publish-composite dburles:collection-helpers matb33:collection-hooks email aldeed:autoform iron:router multiply:iron-router-progress zimme:active-route zimme:iron-router-auth aldeed:template-extension accounts-base accounts-password
```

## Global
- [meteorhacks:npm](https://atmospherejs.com/meteorhacks/npm): Use npm modules with your Meteor App
- [percolate:synced-cron](https://atmospherejs.com/percolate/synced-cron): Allows you to define and run scheduled jobs across multiple servers
- [stevezhu:lodash](https://atmospherejs.com/stevezhu/lodash): Lodash *(remember to add `_ = lodash;` to override underscore)*
- [reactive-var](https://atmospherejs.com/meteor/reactive-var): Creates reactive data source
- [tracker](https://atmospherejs.com/meteor/tracker): Creates reactive computation
- [session](https://atmospherejs.com/meteor/session): Session variable
- [momentjs:moment](https://atmospherejs.com/momentjs/moment) Moment.js (official): parse, validate, manipulate, and display dates
- [raix:handlebar-helpers](https://atmospherejs.com/raix/handlebar-helpers): Handlebar helpers *(as $last and $index for #each)*
- [digilord:faker](https://atmospherejs.com/digilord/faker): Faker.js packaged for Meteor. Generate massive amounts of fake data

## CSS
- [fourseven:scss](https://atmospherejs.com/fourseven/scss): Compiles Sass files with node-sass and it has options to control the load order of Sass files and use Autoprefixer on the generated CSS.
- [twbs:bootstrap](https://atmospherejs.com/twbs/bootstrap): Twitter Bootstrap
- [fortawesome:fontawesome](https://atmospherejs.com/fortawesome/fontawesome): FontAwesome

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

## Forms
- [aldeed:autoform](https://atmospherejs.com/aldeed/autoform): Adds UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation, better with **collection2** *(lot of inputs plugins for autoform available (file upload, autocomplete, selects, maps, etc.))*

## Mobile
- [gadicohen:reactive-window](https://atmospherejs.com/gadicohen/reactive-window): Reactive functions for window properties; width, scroll, etc.
- [mystor:device-detection](https://atmospherejs.com/mystor/device-detection): Client-Side Device Type Detection & Template Switching with Optional Meteor-Router Support
- [ccorcos:swipe](https://atmospherejs.com/ccorcos/swipe): A package for creating apps that swipe between pages

## Routes
- [iron:router](https://atmospherejs.com/iron/router): Router
- [multiply:iron-router-progress](https://atmospherejs.com/multiply/iron-router-progress): Add progress bar on the top of the screen
- [zimme:active-route](https://atmospherejs.com/zimme/active-route): Active route helpers
- [zimme:iron-router-auth](https://atmospherejs.com/zimme/iron-router-auth): Authentication and authorization for iron:router

## SEO
- [manuelschoebel:ms-seo](https://atmospherejs.com/manuelschoebel/ms-seo): SEO helper

## Streaming
- [yuukan:streamy](https://atmospherejs.com/yuukan/streamy): Used for classic socket communication without needing a database (example : a chat)

## Templates
- [aldeed:template-extension](https://atmospherejs.com/aldeed/template-extension): Template hooks + inheritance and copy of template events/helpers

## Users
- [accounts-base](https://atmospherejs.com/meteor/accounts-base) || [accounts-ui](https://atmospherejs.com/meteor/accounts-ui)
- [accounts-password](https://atmospherejs.com/meteor/accounts-password) / [accounts-facebook](https://atmospherejs.com/meteor/accounts-facebook) / [accounts-google](https://atmospherejs.com/meteor/accounts-google) / *etc.*
- [alanning:roles](https://atmospherejs.com/alanning/roles): Role-based authorization
- [tmeasday:presence](https://atmospherejs.com/tmeasday/presence): Help track users' presence *(Visitors counter)*
- [mizzao:user-status](https://atmospherejs.com/mizzao/user-status): User connection and idle state tracking
