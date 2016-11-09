# Heroku Buildpack for additional build steps

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for web applications that have additional build steps specified in package.json.

## Usage

1. Configure as your second buildpack:

   ```bash
   $ heroku buildpacks:add --index 2 https://github.com/tweettypography/heroku-buildpack-webpack
   ```

2. Deploy to Heroku.
