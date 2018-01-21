### Notebook
This is collection of entries that I will slowly add to save and give myself a brief summary of useful technology related things. It will vary from syntax, tips, to a checklist and more! 

*If you ever find this helpful, please give it a :star:!* :thumbsup:

---

### Table of Contents
1. Parts of setting up a website
2. Git 
3. How does the internet work
4. Cloud Hosting
5. CMS (Content Management System)
6. Docker, Jenkins
7. Discrete Math

### Web Development in 2018 Guide
****
##### Deployment Tools
- FTP Client
- SSH Tools: used to interat with your server

##### Cloud Storage
- Google Drive, Dropbox to have access to your server code at any moment in time, which is also a really convenient to have.

##### Technologies
**(Remember it is important to learn the in's and out's of a language before jumping into a framework)**

* HTML/CSS
	* being able to build responsive layouts
	* master or learn about Flex box, and the CSS Grid system; Learn to align elements properly without using a framework.
	* CSS Media Queries
* Basic Vanilla JavaScript
	* basic JavaScript with no framework is important
	* Data Types, Functions, Conditions, Loops, Operators, etc.
	* AJAX/FETCH API/JSON** (used to make http requests and used for asynchronous JavaScript).

* Deploying a Basic Website
	* **Shared Hosting ** - such as InMotion, Hostgator, etc
	* Learn the **Basics of cPanel(the most popular hosting control panel)** - creating email accounts, FTP accounts, etc
	* Upload a site with FTP(File Transfer Protocol) - FileZilla
		- FTP is slow but easy to use
		- Later on learn how to SSH into your server and use SCP and all that stuff
	* **Register a Domain name and learn about DNS / Name Servers**
	
----------------
At this point, you will be able to be a web designer, or basic front end developer

-  you can build simple websites and UIs
-  PSD/AI -> HTML/CSS
-  Add some dynamic UI with JavaScript
-  Can choose to be a freelancer or a very entry level position

##### Next Steps
1. Look at UI Frameworks (HTML, CSS frameworks)
	- Twitter Bootstrap 4: the most general framework and most popular
	- Materialize CSS: primarily a great UI/UX framework
	- Bulma: Easy to learn syntax; similar to bootstrap, with no JS
	- Zurb Foundation: is an alternative to Bootstrap
	- Skeleton CSS is more of a boilerplate: a VERY light boilerplate: good for prototyping; when you're just building out the functionality.
	
##### Front-End JavaScript Frameworks [Choose One]
1. **React** - (technically a library) is the most popular framework right now for startups, it is super fast and super light, uses a state manager called Redux, uses JSX to render HTML instead of using templates.
2. **Angular** - is popular in bigger enterprises, and is usually more full featured and bloated, and includes a lot more in the core framework, uses state manager called NgRx similar to Redux.
3. **Vue.js** -  is the most straightforward framework to learn, syntax is clear, uses a state manager called Vuex
4. **Aurelia** - is super light, feels a lot similar vanilla JavaScript (writing classes is like writing regular JS), have the option to use ESNext (the latest features of ECMAScript or TypeScript)
5. **Ember** - is a much steeper learning curve framework, but full-featured

##### Side Technologies To Learn
- GIT (Version Control)
- Basic Command Line (Folder naviagtion, file creation, etc, npm package manager)
- APIS / REST (Learn how REST APIs work)
	- how it works: make HTTP calls to the back-end API either doing it with JS FETCH API or doing it through a framework like Angular, HTTP Library
- HTTP / SSL
	- different types of HTTP requests you can make: GET, POST, PUT, PATCH, DELETE
	- SSL Security and HTTPS
- CSS Preprocessors
	- **Sass** or Less: preprocessors allows you to use vars and fcn inside of your CSS (logic and stuff).
- Webpack & Babel
	- Webpack is a module loader that allows you to use NPM modules on the client side, also presets to integrate Babel which is a JS compiler.
	- Babel is used to take newer features of JS from newer standards such as ES6 and ES7 and compile them down to older versions like ES5.
	
##### Server-Side Technologies [Choose One]
1. **Node.js** - it is a runtime technology that uses JavaScript on the server; it is popular, fast, scalable, powerful, asynchronous, runs on a server instead of a browser environment, you get NPM, and can install endless packages to avhiceve endless kind of functionality you want
2. **Python** - very popular and is used for rapid development, and you can create things very quickly, which also includes great integration with just about everything.
3. **PHP** - practical, and easy to deploy to shared hosting accounts: Wordpress & Laravel.
4. **Ruby** - ruby on rails is an MVC framework that provides rapid development, with a strong community, but fell off a little bit in recent years.
5. ** C# & ASP.NET**

##### Databases [Choose One]
1. **Mongo.DB** is an incredible NOSQL Database which is Schema-less as far as the data layer goes; very scalable, very quick, it is non-relational, suggested for Node.js; pairs perfectly with Node.js.
2. **MySQL** is a traditional relational database that uses tables and rows; it is popular and can be used with virtually any language. Good with Python, PHP, Ruby on Rails or even Node.js.
3. **PostgreSQL** is a bit harder than MySQL  but also similar but very powerful; more feature full
4. **SQL Server** is the Microsoft's Implementation of SQL database
5. **Oracle** is heavily used in enterprise world; relational database
6. **Firebase** is a real-time cloud database maintained by Google; can also be used as a hosting platform (angular or React)

##### Server-Side Frameworks [Choose One]
1. JavaScript - **Express** is the most popular, Hapi.js, Adonis a hardcore MVC Framework, Loopback, Swagger (last two are newer frameworks built for creating REST APIs and back-end services for full stack applications)
2. Python - **Django** high level framework that does a lot for you and Flask is low level is free to do whatever you want, Web2py, Pylons
3. PHP - PHP, Symfony, CodeIgniter is an easy to use MVC framework, Yii2.
4. Ruby - Ruby on Rails, Sinatra, Nitro
5. C# - .NET framework ASP.NET MVC which is a good MVC

#####CMS or Content Management Systems
1. Wordpress
2. Drupal
3. Joomla [ PHP ]
- These are great for clients
- Thousands of plugins/addons/themes
- Fast development and very convenient
- can be limiting

#####Dev Ops & Deploying Applications
1. Dedicated Servers / VPS
2. **Suggested** Cloud Hosting - Digital Ocean, Heroku, Amazon Web Services (last two built for crreating dynamic applications written in languages such as Ruby, and Python, and Node).
3. Cloud Storage - Amazon S3, especially if you are using Heroku which doesn't allow local file uploads
4. Working with SSH and secure sockets, secure way to connect to your server to make updates and maintenane
5. Server maintence and Software updates

(Don't have to master all this, usually taken care of in the resst of the team)

####Useful Side Note To Learn to Be Exposed To

##### Mobile Applications [Choose One]
- React Native
- NativeScript: uses Angular or pure JS
- Ionic
- PhoneGap / Cordova
- Xamarin: natives applications with C#

---------
You know you are a full stack developer when...

- you can create a simple to advanced web applications [ from front to back! ]
- create a secure REST API that can handle request, and send back responses, and fetch data from the database
- Deploy and maintain applications, 
- Administer databases: going in, adding and removing data, and optimizing



### Coming Soon
![alt text](https://content-static.upwork.com/blog/uploads/sites/3/2015/05/27170038/Software-stack-reworked.png "Software Stack")

- Front End
	* Semantic HTML
	* CSS Box Model
	* CSS Preprocessors
	* CSS Media Queries
	* Bootstrap or other similar frameworks like Materialize etc..
	
-  Javascript
	* understanding and working with DOM
	* What is JSON and how to manipulate it
	* Functional composition, inheritance, closures, event delegation, scope, higher-order functions
	* Asynchronous control flow, promises, callbacks
	* Modular code
		- Webpack, browsify
		- build tools: gulp
	* Popular Frameworks: React, AngularJS
	
	
- Backend
	* Node, Ruby, Python, Java, PHP
	* **Database Operation**
	* **user auth** - application logic
	
##### Databases/Web Storage
	Relational Data (SQL - understand benefits)
	NOSql databases (Mongo)
	Connect databases with chosen back-end language (Node + Mongo)
	Understand benefits in-memory data stores

##### Redis or memcached
	Web storage

- Mean
	* **M**ongoDB
	* **E**xpress
	* **A**ngularJS or Ember.js (MEEN)
	* **N**odeJS
- Django Stack
	* Python
	* Django
	* Apache
	* MySQL
- LAMP
	* **L**inux
	* **A**pache
	* **M**ySQL
	* **P**HP (interchangeable with Python or Perl)
(Variations: WAMP, LAPP, MAMP, XAMPP)
	
###### Bitnami-Hosted Stacks
- Ruby
	* Ruby
	* Ruby on Rails
	* RVM (Ruby VM)
	* MySQL
	* Apache
	* PHP

- Bitnami DevPack
	* PHP
	* Django
	* Ruby on Rails
	* Java
	* MySQL, PostgreSQL
	* Apache Tomcat
	
*Other Misc Front end*

1. Python/Go
2. HTML/CSS
3. Framework: React, AngularJS, Backbone.js
4. Jinja, Mustache
5. Linux
6. Source Control (Git)
7. Databases (MySQL, Redis, Mongo, Cassandra, ElasticSearch)
8. Messaging Systems (NSQ, Kafka, RabbitMQ)
9. Continuous Integration (Jenkins)
10. Service Oriented Architecture
11. AWS, GCP
12. Infrastructure Tools (Docker, ECS, Terraform)
13. Monitoring/ Instrumentation (Nagios, DataDog, StatsD)
14. Front end (React, Redux, T3.js, Sass)

###### Discrete Math
- Probability Theory
- Boolean Algebra
- Logic
- Permutations/Combinations
- Induction
- Finite State Machines
- Relations and Functions
- Ring Structures
- Recursion
- Algorithm Complexity

###### Technologies and stuffs
- Redux
- React
- React Native
- Linux, different types (Linuxjourney.com)
- Ping, hacking, ip address and etc.

###### Web Security
- Basic PHP usage/MySQL usage
- Security Introduction
- Fundamental Security Principles
- Connecting to a Database (Dynamic Content with PHP and MySQL)
- Social Engineering
	- Attack: URL Manipulation
	- Attack: Social Engineering
	- Semantic Versioning
	- Common Vulnerabilities and Exposures
	- Assignments: Using PHP with relational database tables
- Securing Input and Output
- Input/Output Attacks
- Footprinting and Forgery
- Session Hijacking and Fixation
- Encryption and User Authentication
- User Authentication Attacks
- The Secure Web
- Securing Servers
- Assessment and Monitoring


###### Topics in Web Development/Design
- HTML and CSS
- create dynamic pages using Javascript and the DOM (Document Object Model)
- write web applications that use server side data stores such as databases
- use design elements such as color, font, and images to promote usability
- write and test a web application and its components through unit and system tests

###### Topics in Software Engineering
- knowledge of Agile software development
- Automated Testing Techniques
- Continuous Integration and Continuous Deployment Techniques
- Collaborative Planning and Estimating
- Collaborative Implementation Techniques
- Agile Software Architecture Techniques
- Working effectively on an Agile team
- Design and Build large systems in iterative increments
- business responsibilities of the software engineer
- empirical software engineering practices
- industrial software engineering practices


	
