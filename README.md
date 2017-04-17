# HelloWorldApp Challenge

## Application

HelloWorldApp is a simple Ruby web app, which stores access log in MySQL database.

### Configuration

All application configuration is stored in environment variables. Check out `.env.example` for available options.

You may set the environment variables when launching the app or store them in `.env` file.

### Running app

Use `rackup` command to configure server, host, port etc. thin and puma are included in Gemfile.

```sh
bundle exec rackup -s thin -E production -o 0.0.0.0 -p 3000
```
# challenge-Austin
