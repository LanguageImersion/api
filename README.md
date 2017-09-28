Scaffolding Controller, Controller Test, and Updates Route Config
> yo express-rest-api:controller

Scaffolding Service and Service Test
> yo express-rest-api:service

Scaffolding Repository and Repository Test
> yo express-rest-api:repository

Application NPM Commands
// installs everything that is required to run your new application
> npm run install-local
// runs application
> npm start
// runs application in debug mode
> npm run debug
// runs mocha tests
> npm test
// runs istanbul code coverage
> npm run test-coverage
Application Folder Structure Example
package.json
server.js
\app
\..\config
\..\settings
\..\..\settings-config.js
\..\route.config.json
\..\route-config.js
\..\worker-config.js
 
\..\controllers
\..\..\v1
\..\..\..\users
\..\..\..\..\users-controller.js
 
\..\services
\..\..\users
\..\..\..\user-service.js
 
\..\repositories
\..\..\users
\..\..\..\user-repository.js
\test
\..\spec
\..\mocha.opts
\..\tests.initialize.js
 
\..\..\controllers
\..\..\..\v1
\..\..\..\..\users
\..\..\..\..\..\users-controller.tests.js
 
\..\..\services
\..\..\..\users
\..\..\..\..\user-service.tests.js
 
\..\..\repositories
\..\..\..\users
\..\..\..\..\user-repository.tests.js