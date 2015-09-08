# Meteor packages we need
Basic packages needed to start a nice project

**Remember** to remove [insecure](https://atmospherejs.com/meteor/insecure) and [autopublish](https://atmospherejs.com/meteor/autopublish) packages.

## CSS
- [fourseven:scss](https://atmospherejs.com/fourseven/scss): Compiles Sass files with node-sass and it has options to control the load order of Sass files and use Autoprefixer on the generated CSS.
- [twbs:bootstrap](https://atmospherejs.com/twbs/bootstrap): Twitter Bootstrap
- [fortawesome:fontawesome](https://atmospherejs.com/fortawesome/fontawesome): FontAwesome

## Collections
- [aldeed:collection2](https://atmospherejs.com/aldeed/collection2): Allows to attach a schema to a Mongo.Collection. Automatically validates against that schema when inserting and updating from client or server code.
- [reywood:publish-composite](https://atmospherejs.com/reywood/publish-composite): Flexible way to publish a set of related documents from various collections using a reactive join. This makes it easy to publish a whole tree of documents at once. The published collections are reactive and will update when additions/changes/deletions are made.
- [dburles:collection-helpers](https://atmospherejs.com/dburles/collection-helpers): Transform collections with helpers
- [matb33:collection-hooks](https://atmospherejs.com/matb33/collection-hooks): Extends Mongo.Collection with before/after hooks for insert/update/remove/find/findOne
- [meteorhacks:aggregate](https://atmospherejs.com/meteorhacks/aggregate): Proper MongoDB aggregations support *(server side, not reactive)*

## Email
- [email](https://atmospherejs.com/meteor/email)

## Files
- [cfs:standard-packages](https://atmospherejs.com/cfs/standard-packages): File manipulation

## Forms
- [aldeed:autoform](https://atmospherejs.com/aldeed/autoform): Adds UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation, better with **collection2** *(lot of inputs plugins for autoform available (file upload, autocomplete, selects, maps, etc.))*

## Global
- [stevezhu:lodash](https://atmospherejs.com/stevezhu/lodash): Lodash *(remember to `_ = lodash;` to override underscore)*
- [reactive-var](https://atmospherejs.com/meteor/reactive-var): Creates a reactive data source
- [tracker](https://atmospherejs.com/meteor/tracker) : Creates reactive computation
- [session](https://atmospherejs.com/meteor/session) : Session variable

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
- [jalik:roles](https://atmospherejs.com/jalik/roles): Fast and flexible way to control what users can do in the application
