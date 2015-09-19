# Heroku-ready Rails bootstrap

## Heroku specific
  - [x] use the [Postgres][pg-default-db] database
  - [x] use the [`rails_12factor`][rails-12factor] gem
  - [x] use `puma`, [the recommend webserver][puma-for-server]

## Make my developer life easier
  - [x] inherit [relevant/generic `.gitignore` rules from Github's default Rails one][gitignore-gh]
  - [x] be explicit about [which Ruby version][explicit-rb-ver] we’re using
  - [x] separate gems into [Rails omakase vs project specific][omakase-specific]
  - [x] use [`quiet_assets`][quiet-assets] to turn off the Rails asset pipeline log in development
  - [x] make development more REPL, with `pry-rails`

  [pg-default-db]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/blob/e81e121/Gemfile#L7
  [gitignore-gh]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/blob/e81e121/.gitignore#L15-L21
  [explicit-rb-ver]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/commit/1ade082
  [omakase-specific]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/commit/fa2c391
  [rails-12factor]: https://github.com/heroku/rails_12factor
  [puma-for-server]: https://devcenter.heroku.com/articles/getting-started-with-rails4#webserver
  [quiet-assets]: https://github.com/evrone/quiet_assets
