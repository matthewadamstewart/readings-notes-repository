# Readings-Notes-Repository

## Class 06 notes for my Readings in Code Fellows 301 Course

[Back To Main](https://matthewadamstewart.github.io/readings-notes-repository/)


### 

#### Node.js

* > "Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine."
* > "Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library."
* Long story short: It allows you to run Javascript without a browser, in your terminal for instance or as a server
* comes with npm
* has great support for modern Javascript
* ```npm -v``` to check npm version
* uses package.json file which is made via initializing npm within the project
* **THIS IS IMPORTANT** it allows you to run Javascript on a Server
* [Click to view diagram](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2012/10/1516152673node_event_loop.png)
* I/O calls should be avoided due to CPU intensive operation
* Get around by handing off to worker thread
* Suited for App that require real time interaction
* advantages: Speed, Scalability, speaks JSON, and uses Javascript, and all in a single methodology