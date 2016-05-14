# Trying out Vapor (Swift 3) 

This sample project uses Vapor 0.8.1 with Swift 3 - DEVELOPMENT-SNAPSHOT-2016-05-03-a   
Successfully deployed to Heroku running at   
http://swiftvapor.thelivingapps.com/hello



References
- Vapor: https://github.com/qutheory/vapor/
- Nice tutorial: https://medium.com/@LogMaestro/server-side-swift-c965b7ebe6e7#.mdvsphls6

# Deploying to Heroku

* Create Heroku App
* Set buildpack: $ heroku buildpacks:set https://github.com/kinwo/heroku-buildpack-swift  
Note: There is a bug in the original https://github.com/kylef/heroku-buildpack-swift.git when copying dynamic libraries causing build to fail in Heroku
* Push changes to Heroku for build and Deploying
