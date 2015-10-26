ToothLogger
===========

# Running
Prepare configuration. Get your Coinbase key from coinbase.com/account/integrations

 $ cp .env.dummy .env

## Run locally
### Install dependencies
$ npm install

### Run server locally
$ foreman start

## Run at heroku
  * $ git push production-heroku master:master
  * $ heroku config:push

# Using guard-livereload
Detailed instructions about installing guard-livereload can be found here: https://github.com/guard/guard-livereload
To activate guard-livereload:
  * start server from livereload directory:

    $ bundle exec guard --watchdir ../
  * enable LiveReload extension in Chrome by pressing button
