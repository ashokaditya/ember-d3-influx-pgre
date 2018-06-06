# ember-d3-influx-pgre
Everything is javascript in both apps so a thorough understanding is a must. Additionally, there’s considerable amounts of html and css in the client app as it runs on the browser. Also best to understand all web technologies and how they solve each specific problem.

## Javascript
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) - best book to cover all basic and advanced stuff. I recommend doing all the exercises. Best to think on how to solve a problem on a abstract level. Then write it down as comments, before writing actual code that implements that logic
* [JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/javascript) - My source of truth for Javascript language API. Very well structured and constantly updated. Best not to use deprecated functions and features. Watch out for :thumbsdown: icons beside methods and properties.
* Modules
* Promises
* Timers
* Objects
* Scope
* ES6

### Babel/compile modern JS into browser compatible js
* [Babel](https://babeljs.io/)
* You can see all the various ways for setting up babel be it IDEs, frameworks or build systems [here](https://babeljs.io/docs/setup/)

## Web Technologies
* [Web technology for developers | MDN](https://developer.mozilla.org/en-US/docs/Web)

## Web Sockets
* [Introducing WebSockets: Bringing Sockets to the Web - HTML5 Rocks](https://www.html5rocks.com/en/tutorials/websockets/basics/#toc-usecases)
* [WebSockets - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)

## CSP
* [Content Security Policy CSP Reference & Examples](https://content-security-policy.com)

## npm 
* [npm Documentation](https://docs.npmjs.com)
* Especially, how to use npm to manage dependencies
* structure of package.json

## Bower  
* [Bower — a package manager for the web](https://bower.io/)

## Testing and TDD/BDD
* Unit, Integration, Acceptance Testing
* Read Testable Javascript by
* [Behavior-driven Development - Semaphore](https://semaphoreci.com/community/tutorials/behavior-driven-development)
* [BDD vs TDD: A Behavior-Driven Development Example | Toptal](https://www.toptal.com/freelance/your-boss-won-t-appreciate-tdd-try-bdd)
* [Behavior-Driven Development](http://www.codemag.com/article/0805061)

## Continuous Integration and Delivery
* To start with read [Continuous Integration vs. Continuous Delivery vs. Continuous Deployment - Stack Overflow](https://stackoverflow.com/questions/28608015/continuous-integration-vs-continuous-delivery-vs-continuous-deployment#28628086)
* Best to read and understand [An Introduction to Continuous Integration, Delivery, and Deployment | DigitalOcean](https://www.digitalocean.com/community/tutorials/an-introduction-to-continuous-integration-delivery-and-deployment)
* and [Continuous integration vs. continuous delivery vs. continuous deployment |](https://www.atlassian.com/continuous-delivery/ci-vs-ci-vs-cd)
* Semaphore CI
* Travis CI

## Git
* Get thorough with git workflow on command line.
* Git guis are great but they’ll mess with your workflow if you don’t know or understand what commands are running behind them.
* Most GUIs do not show the commands running in the backgound, or allow conflict resolution for merges.
* Hence, it is best to use git on cli when you're a beginner.
* Best place to learn and understand [Learn Git- Git tutorials, workflows and commands | Atlassian Git Tutorial](https://www.atlassian.com/git)
  * Click on get started and read through the documents.
  * Most things will make sense only if you’ve had experience in source management and understand what problems a certain workflow solves. 
- - - -
## Server App/DDOS Api
### Node JS 
* [Index | Node.js v8.11.2 Documentation](https://nodejs.org/dist/latest-v8.x/docs/api/)
* [Introductory and intermediate concepts with videos](https://node.university/courses/107814/lectures/1590275)

### Express JS
* [Installing Express](https://expressjs.com/en/starter/installing.html)
* Also read all the links on the main navigation of the site. This is all you need to know.
* Additionally, one can search for specific concepts and problems on stackoverflow.

### json api
[JSON API — A specification for building APIs in JSON](http://jsonapi.org/)
The frontend app uses JSONAPI serializer to serialize and deserialize data.

### PM2/Process Managers
* [PM2 - Cluster Mode](http://pm2.keymetrics.io/docs/usage/cluster-mode/) - Advanced Node.js production process manager with a built-in load balancer.

### PostGre SQL /RDBMS
* Ver 9.6 docs [PostgreSQL: Documentation: 9.6: PostgreSQL 9.6.9 Documentation](https://www.postgresql.org/docs/9.6/static/index.html)

### InfluxDB / Time Series DBs
* [InfluxDB 1.5 documentation | InfluxData Documentation](https://docs.influxdata.com/influxdb/v1.5/)
  
- - - -
## Client App/Gossamer
### EmberJS
* [Ember.js - Homepage](https://emberjs.com)
* Ember js comes with a CLI called Ember cli that eases dev workflow. I would recommend using it in your workflow. Important things to learn:
* [Core Concepts](https://guides.emberjs.com/release/getting-started/core-concepts/) - best to understand and memorize this diagram, which tells you the overall abstraction of how requests and data flow in and out of ember apps.
* Ember Run Loop
* Ember Data
* Ember Testing

### Handlebars
Ember uses [Handlebars Templating](https://handlebarsjs.com/) for templates but doesn't provide a detailed documentation for it.

### D3js
[D3.js - Data-Driven Documents](https://d3js.org)
[Gallery · d3/d3 Wiki · GitHub](https://github.com/d3/d3/wiki/Gallery)

### Semantic UI
* [Semantic UI](https://semantic-ui.com)
* [GitHub - Semantic-Org/Semantic-UI-Ember: Official Semantic UI Integration for Ember](https://github.com/Semantic-Org/Semantic-UI-Ember)

### Browserfify 
* [Browserify](http://browserify.org) lets you require(‘modules’) in the browser by bundling up all of your dependencies.
* If you don’t know what require(‘modules’) is then go read [Modules :: Eloquent JavaScript](http://eloquentjavascript.net/10_modules.html)


### Web Authentication
* [Web Authentication: An API for accessing Public Key Credentials Level 1](https://www.w3.org/TR/webauthn/)

### Authentication using Jason Web Tokens
* [JSON Web Token Introduction - jwt.io](https://jwt.io/introduction/)
* [JSON Web Tokens - jwt.io](https://jwt.io)
* [Authenticate a Node.js API with JSON Web Tokens ― Scotch](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens)
