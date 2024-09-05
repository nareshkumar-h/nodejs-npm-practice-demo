#### Publish a nodejs libary

#### Initialize Repository
* npm init
* npm init -y ( which accepts default values)

Note: It will create a package.json

#### Install Dependency

* npm install bootstrap
* npm i bootstrap

* Note: It will create a node_modules folder and then downloads bootstrap from npmjs.com

#### Remove Dependency
* npm remove bootstrap

#### Install Development Dependency
* npm install typescript -D

* Note: -D refers Development

#### Install Dependency in Global
* npm install @angular/cli -g

* Note: -g refers global

#### Publish your npm library ( Optional )

* Prerequisite: 
  * You need create an account in npmjs.com
  * You need to login in your PC ( npm login)


* package.json
  * name: @username/libraryname
  * version: 1.0.0 ( major.minor.patch)

* npm publish --access=public

* Note: publicly available



* npm publish --access=public