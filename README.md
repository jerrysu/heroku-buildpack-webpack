# Heroku Buildpack for webpack

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for web applications that use webpack.

## Usage

To use the buildpack:

1. Configure your `.buildpacks` file:

   ```
   https://github.com/heroku/heroku-buildpack-nodejs
   https://github.com/jerrysu/heroku-buildpack-webpack
   ```

2. Set the buildpack on heroku

  ```bash
  $ heroku buildpacks:set https://github.com/jerrysu/heroku-buildpack-webpack
  ```

3. Set ```WEBPACK_CONF_PATH``` variable in heroku to your webpack config path for example `webpack.config.js` or `config/webpack/production.config.js`

4. Deploy to Heroku.

