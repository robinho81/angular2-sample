# angular2-sample 
A repository containing a **very cut down** example of an angular2 project that uses webpack. 

The repository was created using the angular-cli and following the angular2 pages on webpack.

The purpose of this repository was to demonstrate some fundamental concepts when running angular2 and webpack. For the purposes of simplicity, I removed tests and end to end tests. I would **not recommend** running a real project without proper unit testing and end to end testing!

## Instructions

Notes: This assumes that you have Node and NPM installed. 

### Building
* Clone the repository
* Install webpack globally using the command: npm install -g webpack
* cd to the repository directory 
* restore npm packages
* run webpack to build the bundles

### Running
To run the application you just need to host it in a web server.

I recommend using http-server from npm
* Install http-server using the command: npm install -g http-server
* Host the wwwroot directory: http-server /wwwroot
* Go to the URL localhost:8080

