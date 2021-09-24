![banner.png](./banner.png)
> Learn the Prerequisites

![](./1.png)
## **1 .JavaScript**

If you are a frontend developer looking to master some backend skills then you don't have to spend a huge amount of time learning JavaScript before getting started with building Node.js applications. But in case if you are a complete beginner who’s looking to master Node.js in the minimum possible time then you must learn the following concepts before you deep dive into the Node.js environment.

-   Arrow Functions
-   Types
-   Expressions
-   Functions
-   Lexical Structures
-   this
-   Loops and Scope
-   Arrays
-   Template Literals
-   Strict Mode
-   ES6/ES7
_In Node.js you will be handling a lot of asynchronous programming and for that, the following concepts are recommended to learn_
## 2. NPM

Node Package Manager is the world’s largest  **Software Registry**  with over 800,000 code packages. Using  **NPM**  the right way can help a lot as managing packages becomes pretty handy with  **NPM**  while we develop applications that require a number of dependencies.

**NPM consists of three distinct components:**

-   **The Command Line Interface (CLI):** It runs in the machine’s terminal environment and how most of the developer interact with NPM
-   **The Registry:** A large public database of JavaScript software and the meta-information.
-   **The Website:**  You can discover new packages, and manage other aspects of your npm experience.

NPM is used for managing multiple versions of code and code dependencies, run packages without downloading them **_(using npx)_**, and many more.

## 3. Node.js Basics

**Event Emitters:** They are objects in  **Node.js** that trigger events by sending a message to signal that an action was completed. We can also write our own code that listens to events from an event emitter.  _For example_, if you have done some frontend work, then you probably know how much interaction we need to handle in our applications, such as  **mouse clicks, keyboard button presses,**  and other mouse movements. Similarly, on the backend environment in Node.js, we can build a similar system using the events module, which offers  **EventEmitter**  class which we use to handle our events.
**Callbacks:** These are functions called when a task is completed, which prevents any kind of blocking while allowing the rest of the code to run in the meantime. As we have to work with a lot of asynchronous tasks in Node.js, we need them everywhere for making seamless and faster applications.
**Buffers:**  A class called Buffer in Node.js is designed to handle raw binary data. They correspond to some raw memory allocated outside  **V8**. Buffers are an array of integers that can’t be resized having a whole bunch of methods specifically for binary data. For example, the integers in buffer represent a byte with limited values from  **0**  to  **255**  inclusive, if you  **_console.log()_**  to print a Buffer instance, a chain of values in hexadecimal will be received.

**Module System:**  As a part of the Node.js ecosystem you will be using the Module for implementing complex functionality by just using the Modules provided by Node.js, these are JavaScript files that contain all the organized and complex features that anyone can reuse through the Node.js application.
# Development Skills

![](./2.png)


**Version Control Systems (Git, GitHub):** You don’t want to be in a situation where you mess up something in your code while having no idea how to revert it. Using VCS like  **Git**  you can manage large scale projects & if you are already pretty familiar with using VCS then make sure that you have strong fundamental of Version Control Systems.

**HTTP/HTTPS protocols:** A fundamental knowledge of how the data is transferred using the transfer protocols will make you a better Node.js developer, a good understanding of how HTTP and HTTPS work is something every backend developer should understand well enough. HTTPS uses an encryption protocol known as Transport Layer Security  **(TLS)**to encrypt communications. There is a lot to learn in the backend environment and it might get a little foggy for you if you had no idea how the web works, there are 4 request methods responsible for any basic communication on the web:

-   **GET:** Used to retrieve a representation of a resource
-   **POST:**  Used to create new resources
-   **PUT:** Used to update capabilities
-   **PATCH:**  Used to modify capabilities
-   **DELETE:**  Used to delete a resource identified by a URL
-   **OPTIONS:**  Request permitted communication option for a given URL or server

# Web Frameworks
![](./3.png)

**_Note:_** _All these web-frameworks are good to know, if you are building a personal project with Node.js then sticking with a single framework is recommeded, otherwise the learing path is quiet wide to cover._

**Express.js:**  Provides a very minimal interface and tools that are required to build our application, quite flexible to use, and comes with numerous modules available on  **npm**  which can be plugged directly into Express.

**Meteor.js:** A great go-to framework for making JavaScript applications, comes with built-in  **MongoDB**  handlers with support for  **GraphQL.**  When you run the “meteor create myapp” and run it, an  **HTML**/**JavaScript**  web page is provided with a MongoDB backend. You can use Meteor.js as an effective alternative in your list of frameworks that helps you cut the development time with ease of maintenance. Otherwise, I will recommend sticking with  **Express**  if you are building a simple web app.

**Sails.js:**  An  **MVC**  framework allows you to quickly build REST APIs, single-page apps, and real-time apps. If you are looking to master some serious skills then Sails.js is highly recommended as you get many benefits with it, such as real-time support with WebSockets and it uses the “convention over configuration” approach.

**Koa.js:**  If you are looking to build robust applications that are future proof and easy to maintain then Koa.js is a good choice. A  **Koa**  application is an object containing an array of some middleware functions that are later executed in a manner of stacks.

**Nest.js:**  Inspired by Angular and built with  **TypeScript**, uses Express.js under the hood which makes it compatible with most of Express middleware. You can build an efficient and scalable application with Nest.js as it provides a great modular structure for organizing code into separate modules.

# Database Management

While learning  **Node.js**  you will be working with a lot of backed stuff & if you are a beginner you should stick to MySQL or SQL at the start. As you will get clear and concise clarification of how we design backend systems, going beyond  **SQL**  or  **MySQL**  is case dependent as you work with new types of projects there are chances that you will need to learn other backend stuff.

**_Note:_** _Most of the time we work with_ **_Relational Databases._** _For example, we model data like_ **products, categories, tags,** _etc using tables. And a table contains columns and row as similar we have in a spreadsheet._

**SQL Server:** A relational database management system developed by Microsoft, it supports  **ANSI SQL**  (a standard SQL language). However, SQL comes with its own implementations.

**MySQL:**  Another great database management system that allows you to mage relational databases. Open-source backend software developed by Oracle, also with MySQL we get the flexibility of choices as we can change the source code according to the needs. MySQL is a pretty easy alternative as compared to  **Oracle Database** & **Microsoft SQL server.**

**PostgreSQL:**  Developed by a worldwide team of developers as it is open source. It runs on all major operating systems including Linux, UNIX & Windows. PostgreSQL supports a large part of the SQL standard while offering some great features such as  **Complex SQL queries, Foreign Keys, Trigger, Transactions, Multiversion concurrency control (MVCC), Streatimg Repllicartons, etc.**

-   **MariaDB:**  An improved version of MySQL that comes which various inbuilt powerful features, security, and performance improvements that you will not find in MySQL. There are several reasons why you should opt for MariaDB instead of MySQL for large-scale applications. For example, MariaDB has a larger connection pool supporting up to 200,000+ connections whereas MySQL has a smaller connection pool.  _In short,_ **_MariaDB_** _is faster than_ **_MySQL_**_._

## **Cloud Database Services**

**Azure CosmosDB:**  A database service that is globally distributed, you can manage your data remotely, using cloud databases gave you many advantages as scaling and managing big applications becomes a bit easy with the tool that you can use to scale and distribute, all provided by  **Microsoft Azure**. Also, it supports multiple data models using one backend, which means it can be used for the document, key-value, relational & graph models. As it doesn’t rely on any schemas you can call it a  **NoSQL**  database, but it does support query language with  **_ACID_**  transaction support.

**Amazon DynamoDB:**  As far as my knowledge  **Amazon DynamoDB**  is a great alternative if you already have some experience with SQL, it is a fully managed NoSQL database service providing faster and predictable performance with awesome scalability. You can create databases tables that can store and retrieve any amount of data and serve any level of request traffic

## 2. NoSQL Databases

**MongoDB:** A document-oriented NoSQL database specifically used for high volume data storage, as we have tables and rows in other relational databases, MongoDB uses collections and documents. A document consists of key-value pairs that are just basic unit of data in MongoDB & collection contains sets of documents and function which is the equivalent of relational databases tables

**Redis:** Using Redis we can work with databases, caching, and message broking. It uses data structures like **strings, hashes, lists, sets, bitmaps, hyperloglogs** & **geospatial indexes** to store data in the form of key-value pairs. If you are confused about where we use Redix, here is an example of that.

Let’s say in our application we have to deal with users who are authorized to take different actions within the application, each time we authenticate a user we have to derive their authorization for controlling acces in the applicaation.There is nothing buggy about this approach as we have good standards like  **JOSE**  while keeping our  **key material safe**, but if our application has more than a couple of authorisations, the same becomes very hard to scale. And instead of sendind the list of authorization to the user, we can store the user’s authorization in some form of database and provide the user a  **key-value**  (known as a token) which they have to send us for authorization.

## **Apache Cassandra**

A highly scalable with high-performance and distributed database designed to handle a large amount of data across many servers, with no single point of failure. Created at  **Facebook**  it differs from other relational database management systems. The distributed design is based on Amazon’s  **DynamoDB**  and the data model on  **Google’s BigTable**.

## **LiteDB**

A very lightweight & fast **.NET**  NoSQL embedded database,with serverless document store. You can use  _LiteDB_  in small Desktop applications and small web applications that use one database per account store for per user.

# Template Engines

Using template engines we can use static template files in our application, while at the runtime this  **_template engine_**  replaces the variables in a template file with actual values and then transforms the template into an  **HTML**  file sent to the client. Listed below are some of the popular template engines.

-   **Mustache.js**
-   **Handlebars**
-   **EJS**
# Real-Time Communication

## **Socket.io**

There is a lot when it comes to understanding real-time communication in Socket.IO if you are just getting started as a backend developer, the main logic behind real-time communication stands between the  **client**  and the  **server.**  It allows the flow of  **bi-directional**  data between the client & server, you can think of bi-directional data flow as the synchronous flow of data between two terminals to achieve the real-time communication behavior, these types of behavior are enabled when the client has Socket.IO in the browser along with the server integrated with Socket.IO package. And the data can be sent in the form of  **JSON**  requests.

# API Clients

## REST

Before REST, APIs were developed around a remote procedure call (RPC) and the APIs looked like some locally executed code. Many technologies tried to solve this problem using RPC-like stacks to hide the root problem and after that REST was introduced to build web-based APIs in a better way.

In REST the architecture is styled with simple HTTP calls to communicate instead of complex options like  **COBRA, COM+, RPC**. In REST the calls are messages based and rely on the  _HTTP_  standards to describe these messages. In the  **_Node.js_** ecosystem, you can go for the  **node-rest-client** and  **Axios**, both serve pretty good service for faster web applications.

## GraphQL

A great alternative to REST, GraphQL uses the APIs that prioritize giving clients exactly the data they request. A flexible and developer-friendly alternative, as you can deploy it even in an IDE known as  **GraphiQL.** You also get the advantages to add or deprecate fields without impacting existing **queries**  and build APIs with whatever method is preferred.

## Unit Testing Frameworks

> In Unit Testing, we test individual units/components in isolation where a unit can be the smallest testable part of code in an application. In  **Node.js**  one of the best Unit Testing frameworks are listed below:

-   **Jest:** A very popular testing framework known for its simplicity and developed by  **Facebook**. Among all the testing frameworks Jest has the best documentation with parallel testing support, which means that you can run each test in their own process to maximize performance.
-   **Mocha:** It serves the old standards of Unit Testing frameworks for Node applications and supports async operations like callbacks, promises with highly extensible and customizable assertions.
-   **Chai:** It can be used alongside Mocha and can be used as a  **_TDD/BDD_**  assertion library for Node.js that can be paired with any testing framework based on  **JavaScript**.

## Mocking

In  **Unit Testing,**  the test should be small and lightweight to perform, but there are objects under test that have dependencies on other objects.

###### This article is  Reffered From [Medium](https://javascript.plainenglish.io/)
