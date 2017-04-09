# Week Nine

## Topic Outline

### Day 1

1. Basic custom directives
  * Purpose and basic setup and usage
  * Using as an attribute, element, or annotation (`restrict`)
  * Using scope and passthrough
1. More on directives
  * Linking functionality for UI interaction
  * Using `transclude` to wrap content (modals)

Homework: Repos with directive

### Day 2

1. Custom Filters
  * Purpose and basic usage
  * Adding options
  * Using from a controller

Homework: Popular repos

### Day 3

1. Review Node.js concepts
  * Modules (export & require)
  * Revealing module pattern
  * Using core modules (`fs`)
  * `process` object
  * Dependencies and semver
  * Choosing a module (dependency)
1. Node web servers
  * Using basic `$http` (but don't)
  * Express setup
  * Request and Response objects
  * Express routes with external `Router`

Homework: Job board server (no database)

### Day 4

1. Node web server review
1. Middleware (and error middleware)
  * Adding a request logger
  * Adding auth middleware
1. Using a database with Node
  * Mongo basics
  * Connecting to MongoDB
  * Disconnecting on SIGINT
  * Mongoose schemas & models
  * CRUD with Mongoose (`save`, `find`/`findOne`, `save`, `remove`)
  * `find()` -> query, then do `query.exec()` to get a Promise
  * Why `exec()` ? Because: `Movie.find({ name: /blood/i }).limit(10).sort({ year: -1 }).exec()`
  * Queries: `{ name: /john/i, age: { $gte: 18 }`
  * Regex (_if time_): `new RegExp()` to use strings

Homework: Job board (back end only)
