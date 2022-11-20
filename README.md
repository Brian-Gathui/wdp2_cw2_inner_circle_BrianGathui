# Inner Circle - Web Platform Development 2 Coursework 1 Submission


Coursework 1 - Scenario 2:
_____________________________
A concierge company business owners want to organize the list of their collaborators and partners in the industry. 
Moreover, they also want to have a record of services that their collaborators are providing and any activities they work together.

Your task is to design and implement a web-based business planner for concierge owners and their collaborators. 

The application should allow the following:

     (1)  Users who are not logged in to see the About Us  
          page with the details of the concierge company.

     (2)  Collaborators should be able to login and 
          perform the following:
          (a)  Add the name and category of their business
               (Real Estate, Education, and Wellness).
          (b)  Add, remove, and modify the services they 
               are offering.
          (c)  There should be at least three     
               collaborators that are categorized in Real Estate, Education, and Wellness. 

     (3)  Business owners should be able to login and     
          perform the following:
          (a)  define their plan schedule with the    
               collaborators on a weekly basis including the capability of recording their agenda/outcome.
          (b)  A breakdown of the plans for a week. There 
               should be at least 2 or 3 agenda per category: (real estate, education, wellness)
          (c)  Weekly plans can be defined several weeks 
               ahead.
          (d)  There should be at least three     
               collaborators that are categorized in Real Estate, Education, and Wellness. 

NOTE: 
The application should be developed using Node.js and Node Express. The application should NOT require other systems, such as databases, to be installed on the running computer. You can either use NeDB in embedded mode or a cloud-based data storage service, such as Mongo Atlas. Any application features not specified here can be designed by you. If your application extends the specification you should highlight the additional features in your report.


Coursework 1 Description:
_____________________________

(1)  Recorded video approximately 10-15 mins in length demonstrating  
     the implementation of the following web application core functionality using node.js, express framework, and a database (data storage solutions) based on the following points: (70%)

     (a)  Client-server communication (20%)
     (b)  Data persistence (15%)
     (c)  Integration of application data (15%)
     (d)  Model-View-Controller pattern implementation (20%)


NOTE:
The purpose of this part is to demonstrate elements of the technology stack including some of the learning outcome of this module before proceeding to develop the application required for Coursework 2. For this demonstration, you should choose a scenario and data related to the topic of the coursework. You cannot use the code developed in the weekly labs.

(2)  Recorded video approximately 10-15 mins in length demonstrating  
     the implementation of the following web application core functionality using node.js, 
     express framework, and a database (data storage solutions) based on the following points: (70%)
     
     (a)  identification of all the user groups expected to access the 
          site and the tasks they will perform while using the site 
     (b)  structure charts, wireframes, use cases, and sample visuals 
          showing the ‘look and feel’ of the site, etc.
     

Technologies Used:
_____________________________

NodeJs:
     Node.js is an ope source, cross-platform  software development technology that is 
     used by some of the biggest players in global business, from Netflix and PayPal to LinkedIn, to build fast, high-quality 
     applications. NodeJs is used for running web applications outside the client’s browser. More specifically, running 
     server-side programming, and primarily deployed for non-blocking, event-driven servers, such as traditional web sites and 
     back-end API services, but was originally designed with real-time, push-based architectures in mind.

     Source: https://www.netguru.com/glossary/node-js 

MongoDB:
     MongoDB is an open-source document database built on a horizontal scale-out 
     architecture that uses a flexible schema for storing data. Founded in 2007, MongoDB has a worldwide following in the developer community.
     Instead of storing data in tables of rows or columns like SQL databases, each record 
     in a MongoDB database is a document described in BSON, a binary representation 
     of the data. Applications can then retrieve this information in a JSON format.

     Source: https://www.mongodb.com/why-use-mongodb

MongoDB Atlas:
     Database-as-a-Service (DBaaS) is a service that allows you to set up, deploy, and 
     scale a database without worrying about on-premise physical hardware, software 
     updates, and the details of configuring for performance. With DBaaS, a cloud 
     provider does all that for you—and gets you up and running right away.
     MongoDB Atlas is a fully-managed cloud database that handles all the complexity 
     of deploying, managing, and healing your deployments on the cloud service provider 
     of your choice (AWS , Azure, and GCP). MongoDB Atlas is the best way to deploy, 
     run, and scale MongoDB in the cloud. With Atlas, you’ll have a MongoDB database 
     running with just a few clicks, and in just a few minutes.

     Source: https://www.mongodb.com/basics/mongodb-atlas-tutorial 

Node Js Dependencies Used:
_____________________________

Express Framework:
     Express is a minimal and flexible Node.js web application framework that provides a 
     robust set of features for web and mobile applications.
     With a myriad of HTTP utility methods and middleware at your disposal, creating a robust API is quick and easy.
     Express provides a thin layer of fundamental web application features, without obscuring Node.js features that you know and love.

     Source: https://expressjs.com

Ejs:
     EJS (Embedded JavaScript Templating) is one of the most popular template engines for JavaScript. As the name suggests, it lets us embed JavaScript code in a template language that is then used to generate HTML.

     Source: https://blog.logrocket.com/how-to-use-ejs-template-node-js-application/
     More Information: https://ejs.co 

express-async-errors: 
     Express-Async-Errors library is an amazing way to catch errors at runtime without using try/catch blocks in your async functions.

     Source: https://devsdash.com/tutorials/express-async-errors
     More Informtation:  https://www.npmjs.com/package/express-async-errors


express-ejs-layouts:
     Layout support for ejs in express

     Source: https://www.npmjs.com/package/express-ejs-layouts?activeTab=readme

body-parser:
     Express body-parser is an npm module used to process data sent in an HTTP request body. It provides four express middleware for parsing JSON, Text, URL-encoded, and raw data sets over an HTTP request body. Before the target controller receives an incoming request, these middleware routines handle it.

     Node.js body parsing middleware.
     Parse incoming request bodies in a middleware before your handlers, available under the req.body property.

     Source: https://www.simplilearn.com/tutorials/nodejs-tutorial/body-parser-in-express-js
     More Information: https://www.npmjs.com/package/body-parser
 
cors:
     CORS stands for Cross-Origin Resource Sharing. It allows us to relax the 
     security applied to an API. This is done by bypassing the 
     Access-Control-Allow-Origin headers, which specify which origins can access the API.

     In other words, CORS is a browser security feature that restricts cross-origin HTTP 
     requests with other servers and specifies which domains access your resources.

     Source: https://www.section.io/engineering-education/how-to-use-cors-in-nodejs-with-express/
     More Information: https://expressjs.com/en/resources/middleware/cors.html

joi@13.1.0:
     The most powerful schema description language and data validator 
     for JavaScript.

     Source: https://www.npmjs.com/package/joi
     More Information: https://joi.dev



joi-objectid@2.0.0:
     joi-objectid validates that the value is an alphanumeric string of 24 characters in length.

     Source: https://www.npmjs.com/package/joi-objectid
mongoose:
     Mongoose is a Node.js-based Object Data Modeling (ODM) library for MongoDB. It is 
     akin to an Object Relational Mapper (ORM) such as SQLAlchemy
     for traditional SQL databases. The problem that Mongoose aims to solve is allowing 
     developers to enforce a specific schema at the application layer. In addition to enforcing a schema, Mongoose also offers a 
     variety of hooks, model validation, and other features aimed at making it easier to work with MongoDB.

     Source: https://www.mongodb.com/developer/languages/javascript/mongoose-versus-nodejs-driver/
     More Information: https://mongoosejs.com/docs/ , https://www.npmjs.com/package/mongoose

path:
     The node:path module provides utilities for working with file and directory paths. It can be accessed using:

     const path = require('node:path');

     Source: https://nodejs.org/api/path.html 
     More Information: https://codeforgeek.com/nodejs-path-module/

winston@3.8.2:
     winston is designed to be a simple and universal logging library with support for 
     multiple transports. A transport is essentially a storage device for your 
     logs. Each winston logger can have multiple transports (see: Transports) 
     configured at different levels (see: Logging levels). For example, one may want 
     error logs to be stored in a persistent remote location (like a database), but all 
     logs output to the console or a local file.
     
     winston aims to decouple parts of the logging process to make it more flexible 
     and extensible. Attention is given to supporting flexibility in log formatting 
     (see: Formats) & levels (see: Using custom logging levels), and ensuring those APIs 
     decoupled from the implementation of transport logging (i.e. how the logs are 
     stored / indexed, see: Adding Custom Transports) to the API that they exposed 
     to the programmer.

     Source: https://www.npmjs.com/package/winston

bcrypt: 
     A library to help you hash passwords.

     Source:  
     More Information: https://codahale.com/how-to-safely-store-a-password/


