# Laravel alternatives in NodeJS

These are alternative packages/frameworks in NodeJS that cover some of the primary features in Laravel.
This is by no means a comprehensive list of Laravel features (or a comprehensive list of NodeJS alternatives).

Depending on your perspective, this list either shows how it's possible to switch from Laravel to NodeJS or shows why you'd want to stay with Laravel :smiley:

<hr>

Full stack framework alternatives: [Nest](https://github.com/nestjs/nest), [Adonis](https://github.com/adonisjs/adonis-framework)

<hr>

Package alternatives:

Laravel (or Symfony) Feature | NodeJS Alternative
-----------------------------|-------------------
Request routing/handling | [express](https://github.com/expressjs/express/), [koa](https://github.com/koajs/koa)
Authentication | [passport](https://github.com/jaredhanson/passport), [bcrypt](https://github.com/kelektiv/node.bcrypt.js), [bcryptjs](https://github.com/dcodeIO/bcrypt.js)
Configuration | [dotenv](https://github.com/motdotla/dotenv), [node-convict](https://github.com/mozilla/node-convict)
Dependency injection | [Do I need dependency injection in NodeJS? (Stack Overflow)](https://stackoverflow.com/questions/9250851/do-i-need-dependency-injection-in-nodejs-or-how-to-deal-with)
ORM | [TypeORM](https://github.com/typeorm/typeorm), [Sequelize](https://github.com/sequelize/sequelize), [Objection](https://github.com/Vincit/objection.js/)
DB migrations | (Simple migrations can be run automatically with Sequelize or Objection)<br>[Sequelize CLI](https://github.com/sequelize/cli), [graphql-migrate](https://github.com/Akryum/graphql-migrate), [knex](https://github.com/tgriesser/knex)
Collections | ES functions, [lodash](https://github.com/lodash/lodash)
Logging | [winston](https://github.com/winstonjs/winston), [debug](https://github.com/visionmedia/debug)
Queues | Redis-based: [Bee Queue](https://github.com/bee-queue/bee-queue), [kue](https://github.com/Automattic/kue)<br>Other: [better-queue](https://github.com/diamondio/better-queue), [node-rethinkdb-job-queue](https://github.com/grantcarthew/node-rethinkdb-job-queue)
Caching | [node-cache](https://github.com/mpneuried/nodecache)
Blade (HTML templating) | [nunjucks](https://github.com/mozilla/nunjucks), [hbs](https://github.com/pillarjs/hbs), etc.
Mail | [nodemailer](https://github.com/nodemailer/nodemailer)
Unit tests | [mocha](https://github.com/mochajs/mocha) + [chai](https://github.com/chaijs/chai)
Dusk (browser tests) | [puppeteer](https://github.com/GoogleChrome/puppeteer)
Artisan commands | [Inquirer](https://github.com/SBoudrias/Inquirer.js) for interactive commands
Task scheduling | [cron](https://github.com/kelektiv/node-cron)
Input validation | [graphql-constraint-directive](https://github.com/confuser/graphql-constraint-directive) ([example](https://blog.apollographql.com/graphql-validation-using-directives-4908fd5c1055))
GraphQL: [Lighthouse](https://github.com/nuwave/lighthouse), [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql) | [Apollo Server](https://github.com/apollographql/apollo-server), [graphql-yoga](https://github.com/prisma/graphql-yoga)<br>[objection-graphql](https://github.com/Vincit/objection-graphql)
