# RESTful-APIs

## What is REST?

REST is an acronym for Representational State Transfer. It is web standards architecture and HTTP Protocol. The REST architectural style describes six constraints that were originally communicated by Roy Fielding in his doctoral dissertation and defines the basis of RESTful-style as:

<ul>
  <li>Uniform Interface</li>
  <li>Stateless</li>
  <li>Cacheable</li>
  <li>Client-Server</li>
  <li>Layered System</li>
  <li>Code on Demand (optional)</li>
</ul>


RESTful applications use HTTP requests to perform Create, Read, Update and Delete operations.



## Tools required:

<ol>
  <li>Node.js</li>
  <li>MongoDB</li>
  <li>Text editor(Preferrable Visual Studio)</li>
  <li>Postman</li>
</ol>

## Kick starting

We are working on creating REST API's. Let's work on creating RESTful todo List API.

## Pre-requisites

NodeJs and MongoDB should be installed in the system.

Version installed in the system can be tested out using the following commands:
```js
  npm -v
  mongo --version
```


## Run

```js
  type command 'mongod' in the terminal
  'npm run start' in another terminal
```

## Open Postman in the system

<ol>
  <li><b>GET</b> -  http://localhost:3000/tasks, initially you will see '[]' empty array.</li>
  <li><b>POST</b> - http://localhost:3000/tasks and select '<b>x-www-form-urlencoded</b>' and enter '<b>name</b>' as key and 'My first todo list'     as value.</li>
  <li><b>GET</b> -  http://localhost:3000/tasks, initially you will see the list added in the 2nd step.</li>
  <li><b>GET</b> -  http://localhost:3000/tasks/:id, Provides an individual task present in the complete list.</li>
</ol>
