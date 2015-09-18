# Heroku-ready Rails bootstrap

  - [x] use the [Postgres][pg-default-db] database
  - [x] inherit [relevant/generic `.gitignore` rules from Github's default Rails one][gitignore-gh]
  - [x] be explicit about [which Ruby version][explicit-rb-ver] we’re using
  - [x] separate gems into [Rails omakase vs project specific][omakase-specific]
  - [x] use the [`rails_12factor`][rails-12factor] gem

  [pg-default-db]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/blob/e81e121/Gemfile#L7
  [gitignore-gh]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/blob/e81e121/.gitignore#L15-L21
  [explicit-rb-ver]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/commit/1ade082
  [omakase-specific]: https://github.com/mariusbutuc/heroku-ready-rails-bootstrap/commit/fa2c391
  [rails-12factor]: https://github.com/heroku/rails_12factor
