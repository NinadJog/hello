# Hello

Simple Hello World web application in Elixir and Phoenix.

After installing it and running the Phoenix server, enter [`http://localhost:4000/hello/world`](http://localhost:4000/hello/world) from your browser, and it will display 'Hello World!'

If you replace 'world' by some other string, such as your name, it will say Hello followed by that string.

Application implementation is from the book 'Programming Phoenix' by Chris McCord, Bruce Tate, and Jose Valim.

## Starting Phoenix Server

Before entering the above link in the browser, start the Phoenix server as follows.

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Install Node.js dependencies with `npm install` inside the `assets` directory
  * Start Phoenix endpoint with `mix phx.server`

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
