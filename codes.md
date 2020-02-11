## My Code
I don't have a lot of publicly available code, my jobs so far have had fairly strict restrictions around open source code.

### Github repos

#### [automfa](https://github.com/figadore/automfa)
A small but fun **go** project I worked on recently. It basically makes my laptop another device to use for multifactor authentication, since it has more physical and technical protection than my phone, this makes it more convenient to log into sites with MFA (e.g. `automfa github` on the command line prints out a 6 digit code). It uses the host OS keychain (or similar) to store the secrets.

#### [Express Skeleton (old)](https://github.com/shinymayhem/express-skeleton-app)
Node.js server preconfigured for use as a REST API. Includes Drone CI config, bunyan logging, error handling, etc

### NPM Modules (old)
#### [hypermedia-validator](https://www.npmjs.com/package/hypermedia-validator)

Validate JSON data against a schema or subschema

#### [more](https://www.npmjs.com/~shinymayhem)

### Docker images (old)

#### [Node.js](https://hub.docker.com/r/shinydocker/node/)
Node.js server with some sane defaults and `onbuild` capabilities

#### [Protractor](https://hub.docker.com/r/shinydocker/protractor/)
Headless karma/protractor/selenium testing, great for CI builds

#### [JSON Schema Generator](https://hub.docker.com/r/shinydocker/schema-generator/)
PRMD schema generator. Convert .yaml schemas into prmd style json schemas for REST APIs

#### [more](https://hub.docker.com/r/shinydocker/)

