LoopBack SDK Builder FOR REACT 

this fork is trying to fix bugs of @mean-expert/loopback-sdk-builder for react ... 
==================
to create react sdk 

````
$ ./node_modules/.bin/lb-sdk server/server.js /path/to/client/sdk -l react -i disabled -t false

````

The [@mean-expert/loopback-sdk-builder](https://www.npmjs.com/package/@mean-expert/loopback-sdk-builder) is a community driven module forked from the official `loopback-sdk-angular` and refactored to support [Angular 2+](http://angular.io).

The [LoopBack SDK Builder](https://www.npmjs.com/package/@mean-expert/loopback-sdk-builder) will explore your [LoopBack Application](http://loopback.io) and will automatically build everything you need to start writing your [Angular 2 Applications](http://angular.io) right away. From Interfaces and Models to API Services and Real-time communications.

`NOTE: This sdk builder is not compatible with LoopBack 4.`

# Installation

````sh
$ cd to/loopback/project
$ npm install --save-dev @mean-expert/loopback-sdk-builder
````

# Documentation

[LINK TO WIKI DOCUMENTATION](https://github.com/mean-expert-official/loopback-sdk-builder/wiki)

# Contribute
Most of the PRs fixing any reported issue or adding a new functionality are being accepted.

Use the development branch to create a new branch from. If adding new features a new unit test will be expected, though most of the patches nowadays are small fixes or tweaks that usually won't require a new test.

