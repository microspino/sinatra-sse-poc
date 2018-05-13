# Sinatra SSE Proof of Concept

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/tbuehlmann/sinatra-sse-poc)

## Installation

```sh
$ bundle install
```

## Running the Application

```sh
$ bundle exec puma config.ru
```

Then visit http://localhost:9292/.

NOTE:
It seems that sending SIGQUIT (via `Ctrl-\`) is needed to kill the PUMA process.
