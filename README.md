# heroku-buildpack-racket

This is a modified version of Alexis King's Racket buildpack for
Heroku tailored to [koyo] applications.

## Setup

    $ heroku buildpacks:Set https://github.com/Bogdanp/heroku-buildpack-racket
    $ heroku config:set RACKET_APP_NAME=your-app-name
    $ heroku config:set RACKET_VERSION=7.6

## Configuration

`Procfile`:

``` sh
web: /app/run
```

[koyo]: https://koyoweb.org
