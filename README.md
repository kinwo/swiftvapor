# Deploying to Heroku

* Create Heroku App
* Set buildpack: $ heroku buildpacks:set https://github.com/kinwo/heroku-buildpack-swift
Note: There is a bug in the original https://github.com/kylef/heroku-buildpack-swift.git when copying dynamic libraries causing build to fail in Heroku
* Push changes to Heroku for build and Deploying
