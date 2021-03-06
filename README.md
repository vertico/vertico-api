<p align="left">
   <img src="docs/images/logo.png" width="450"/>
</p>

> This is the Elixir and Phoenix backend API for the Shikoba Platform

[![Languages](https://img.shields.io/github/languages/count/vejovoce/shikoba-api?color=%23000&style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/vejovoce/shikoba-api?color=000&style=flat-square)](https://github.com/vejovoce/shikoba-api/stargazers)
[![Forks](https://img.shields.io/github/forks/vejovoce/shikoba-api?color=%23000&style=flat-square)](https://github.com/vejovoce/shikoba-api/network/members)
[![Contributors](https://img.shields.io/github/contributors/vejovoce/shikoba-api?color=000&style=flat-square)](https://github.com/vejovoce/shikoba-api/graphs/contributors)

## Installation

### Requirements

You will need to install the following:

- [Elixir](http://elixir-lang.org/install.html)
- [PostgreSQL](https://www.postgresql.org/download/)

### Clone this repository

You'll want to [clone this repository](https://help.github.com/articles/cloning-a-repository/) with `git clone git@github.com:vejovove/shikoba-api.git`. If you plan on contributing, you'll want to fork it too!

## To start your Phoenix server:

  * Install dependencies with `cd backend/ && mix deps.get` and `cd frontend/ && yarn install`
  * Configure database credentials: `cp backend/config/dev.secret.example.exs backend/config/dev.secret.exs`
  * Create and migrate your database with `cd backend/ && mix ecto.setup`
  * Start Phoenix endpoint with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

## Contributing

All contributions are more than welcome! PRs without tests won't be accepted.

Please, follow the [guidelines](https://github.com/jungsoft/elixir-style-guide)
