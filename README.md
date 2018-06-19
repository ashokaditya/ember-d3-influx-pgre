# ember-d3-influx-pgre
Everything is javascript in both apps so a thorough understanding is a must. Additionally, there’s considerable amounts of html and css in the client app as it runs on the browser. Also best to understand all web technologies and how they solve each specific problem. Please check out [DeiC Tech Stack](https://stackshare.io/deic/) on stackshare.io if you wish to see thw entire tech stack of the front-end and server-side apps.

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

## CORs
* [HTTP access control (CORS) - HTTP | MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)
* [enable cross-origin resource sharing](https://enable-cors.org/client.html)

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
* [A Gentle Intro to JS TDD: Part 1](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-intro/)
* [A Gentle Intro to JS TDD: Part 2](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-ajax/)
* [A Gentle Intro to JS TDD: Part 3](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-html-dom/)
* Read "Testable Javascript" by Mark Ethan Trostler
* [Behavior-driven Development - Semaphore](https://semaphoreci.com/community/tutorials/behavior-driven-development)
* [BDD vs TDD: A Behavior-Driven Development Example | Toptal](https://www.toptal.com/freelance/your-boss-won-t-appreciate-tdd-try-bdd)
* [Behavior-Driven Development](http://www.codemag.com/article/0805061)
* [Mocha](https://mochajs.org/#asynchronous-code)
* [Chai](http://www.chaijs.com)

## Continuous Integration and Delivery
* To start with read [Continuous Integration vs. Continuous Delivery vs. Continuous Deployment - Stack Overflow](https://stackoverflow.com/questions/28608015/continuous-integration-vs-continuous-delivery-vs-continuous-deployment#28628086)
* Best to read and understand [An Introduction to Continuous Integration, Delivery, and Deployment | DigitalOcean](https://www.digitalocean.com/community/tutorials/an-introduction-to-continuous-integration-delivery-and-deployment)
* and [Continuous integration vs. continuous delivery vs. continuous deployment |](https://www.atlassian.com/continuous-delivery/ci-vs-ci-vs-cd)
* [Semaphore CI](https://semaphoreci.com)
* [Travis CI](https://travis-ci.org)
* [PostgreSQL CI](https://github.com/petere/pgci)

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
* Additionally, one can search for specific concepts and problems on [stackoverflow](https://stackoverflow.com).

### json api
* The frontend app uses JSONAPI serializer to serialize and deserialize data.
* [JSON API — A specification for building APIs in JSON](http://jsonapi.org/)

### PM2/Process Managers
* [PM2 - Cluster Mode](http://pm2.keymetrics.io/docs/usage/cluster-mode/) - Advanced Node.js production process manager with a built-in load balancer.

### PostGre SQL /RDBMS
* Ver 9.6 docs [PostgreSQL: Documentation: 9.6: PostgreSQL 9.6.9 Documentation](https://www.postgresql.org/docs/9.6/static/index.html)
* You need to understand how sql works. Pretty much all the concepts of RDBMS plus performance tuning queries.

### InfluxDB / Time Series DBs
* [InfluxDB 1.5 documentation | InfluxData Documentation](https://docs.influxdata.com/influxdb/v1.5/)
  
- - - -
## Client App/Gossamer
### EmberJS
* [Ember.js - Homepage](https://emberjs.com)
* I would recommend using [Ember CLI](https://ember-cli.com) that eases dev workflow with Emberjs. Also, a lot about deployment, upgrading and common issues are listed at Ember CLI page.
* [Core Concepts](https://guides.emberjs.com/release/getting-started/core-concepts/) - best to understand and memorize this diagram, which tells you the overall abstraction of how requests and data flow in and out of ember apps.
* [Ember Run Loop](https://github.com/eoinkelly/ember-runloop-handbook)
* [Ember Data](https://guides.emberjs.com/release/models/)
* [Ember Testing](https://guides.emberjs.com/release/testing/)

### Handlebars
Ember uses [Handlebars Templating](https://handlebarsjs.com/) for templates but doesn't provide a detailed documentation for it.

### D3js
* [D3.js - Data-Driven Documents](https://d3js.org)
* [Gallery · d3/d3 Wiki · GitHub](https://github.com/d3/d3/wiki/Gallery)
* [How Selections Work](https://bost.ocks.org/mike/selection/)
* [D3 in Depth](http://d3indepth.com)

### Semantic UI
* [Semantic UI](https://semantic-ui.com)
* [GitHub - Semantic-Org/Semantic-UI-Ember: Official Semantic UI Integration for Ember](https://github.com/Semantic-Org/Semantic-UI-Ember)

### Browserify 
* [Browserify](http://browserify.org) lets you require(‘modules’) in the browser by bundling up all of your dependencies.
* If you don’t know what require(‘modules’) is then go read [Modules :: Eloquent JavaScript](http://eloquentjavascript.net/10_modules.html)

### Web Authentication
* [Web Authentication: An API for accessing Public Key Credentials Level 1](https://www.w3.org/TR/webauthn/)

### Authentication using Jason Web Tokens
* [JSON Web Token Introduction - jwt.io](https://jwt.io/introduction/)
* [JSON Web Tokens - jwt.io](https://jwt.io)
* [Example Authentication with JSON Web Token](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens)

## Best Practices
* [The 12-Factor App](https://12factor.net/config)
* [The Frontend Checklist](https://frontendchecklist.io)
* [NodeJS Best Practices](https://github.com/i0natan/nodebestpractices)

- - - -
## Tools/Utilities/Standards
Use the following tools for a easier developmen flow:

* [Postman Makes API Development Simple](https://www.getpostman.com/)
* [ESLint](https://eslint.org)
* [JSStandard](https://standardjs.com)
* [Less CSS](http://lesscss.org)
* [Scalable and Modular Architecture for CSS](https://smacss.com)

