# Heroku Buildpack for webpack

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for web applications that use webpack.

## Usage

1. Use the [multi buildpack](https://github.com/ddollar/heroku-buildpack-multi):

   ```bash
   $ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi
   ```

2. Configure your `.buildpacks` file:

   ```
   https://github.com/heroku/heroku-buildpack-nodejs
   https://github.com/jerrysu/heroku-buildpack-webpack
   ```
