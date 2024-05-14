
🔙 [Back to Main](README.md)

### What is an `API`?
----
- `APIs` are mechanisms that enable two software components to communicate with each other using a set of definitions and protocols. For example, the weather bureau’s software system contains daily weather data. The weather app on your phone “talks” to this system via APIs and shows you daily weather updates on your phone. </br>

### What does `API` stand for?
----
- `API` stands for `Application Programming Interface`. In the context of `APIs`, the word Application refers to any software with a distinct function. Interface can be thought of as a contract of service between two applications. This contract defines how the two communicate with each other using requests and responses. Their `API` documentation contains information on how developers are to structure those requests and responses. </br>

### How do APIs work? 
----
- `API` architecture is usually explained in terms of client and server. The application sending the request is called the client, and the application sending the response is called the server. So in the weather example, the bureau’s weather database is the server, and the mobile app is the client. </br>
- There are four different ways that `APIs` can work depending on when and why they were created. </br> 

#### `SOAP APIs`

- These `APIs` use Simple Object Access Protocol. Client and server exchange messages using XML. </br>
- This is a less flexible `API` that was more popular in the past. </br> 

#### `RPC APIs`

- These `APIs` are called Remote Procedure Calls. The client completes a function (or procedure) on the server, and the server sends the output back to the client. </br>

#### `Websocket APIs`

- `Websocket API` is another modern `web API` development that uses JSON objects to pass data. </br>
- A WebSocket API supports two-way communication between client apps and the server. The server can send callback messages to connected clients, making it more efficient than `REST API`.

#### `REST APIs`

- These are the most popular and flexible APIs found on the web today. </br>
- The client sends requests to the server as data. </br>
- The server uses this client input to start internal functions and returns output data back to the client. Let’s look at REST APIs in more detail below. </br>

### What are `REST APIs`?
----

- REST stands for `Representational State Transfer`. </br>
- REST defines a set of functions like GET, PUT, DELETE, etc. that clients can use to access server data. Clients and servers exchange data using HTTP </br>
- The main feature of `REST API` is statelessness. Statelessness means that servers do not save client data between requests. Client requests to the server are similar to URLs you type in your browser to visit a website. The response from the server is plain data, without the typical graphical rendering of a web page. </br>

### What is `web API`?
----

- A `Web API` or `Web Service API` is an application processing interface between a web server and web browser. All web services are APIs but not all APIs are web services. REST API is a special type of Web API that uses the standard architectural style explained above. </br>
- The different terms around `APIs`, like Java API or service APIs, exist because historically, `APIs` were created before the world wide web. Modern web APIs are REST APIs and the terms can be used interchangeably. </br>

### What are `API` integrations?
----

- `API integrations` are software components that automatically update data between clients and servers. Some examples of API integrations are when automatic data sync to the cloud from your phone image gallery, or the time and date automatically sync on your laptop when you travel to another time zone. Enterprises can also use them to efficiently automate many system functions.

### What are the benefits of REST APIs?
----

REST APIs offer four main benefits:

1. Integration </br>

- APIs are used to integrate new applications with existing software systems. </br>
- This increases development speed because each functionality doesn’t have to be written from scratch. You can use APIs to leverage existing code. </br>

2. Innovation </br>

- Entire industries can change with the arrival of a new app. </br>
- Businesses need to respond quickly and support the rapid deployment of innovative services. </br>
- They can do this by making changes at the API level without having to re-write the whole code. </br>

3. Expansion </br>

- APIs present a unique opportunity for businesses to meet their clients’ needs across different platforms. </br>
- For example, maps API allows map information integration via websites, Android,iOS, etc. Any business can give similar access to their internal databases by using free or paid `APIs`. </br>

4. Ease of maintenance </br>

- The API acts as a gateway between two systems. </br>
- Each system is obliged to make internal changes so that the `API` is not impacted. This way, any future code changes by one party do not impact the other party.

### What are the different types of APIs?
----

`APIs` are classified both according to their architecture and scope of use. We have already explored the main types of API architectures so let’s take a look at the scope of use.

#### `Private APIs`
- These are internal to an enterprise and only used for connecting systems and data within the business.

#### `Public APIs`
- These are open to the public and may be used by anyone. There may or not be some authorization and cost associated with these types of `APIs`.

#### `Partner APIs` 
- These are only accessible by authorized external developers to aid business-to-business partnerships. 

#### `Composite APIs`
- These combine two or more different APIs to address complex system requirements or behaviors. 

### What is an API endpoint and why is it important?
----

- API endpoints are the final touchpoints in the API communication system. These include server URLs, services, and other specific digital locations from where information is sent and received between systems. API endpoints are critical to enterprises for two main reasons: 

1. `Security`
- `API` endpoints make the system vulnerable to attack. API monitoring is crucial for preventing misuse.

2. `Performance`
- `API` endpoints, especially high traffic ones, can cause bottlenecks and affect system performance.

### How to secure a REST API?
----

All APIs must be secured through proper authentication and monitoring. The two main ways to secure REST APIs include: </br>

1. `Authentication tokens` </br>

- These are used to authorize users to make the API call. Authentication tokens check that the users are who they claim to be and that they have access rights for that particular API call. </br>
- For example, when you log in to your email server, your email client uses authentication tokens for secure access.

2. `API keys` </br> 

- `API` keys verify the program or application making the API call. They identify the application and ensure it has the access rights required to make the particular API call. </br> 
- `API` keys are not as secure as tokens but they allow API monitoring in order to gather data on usage. You may have noticed a long string of characters and numbers in your browser URL when you visit different websites. This string is an API key the website uses to make internal API calls.

### How to create an API?
----

Due diligence and effort are required to build an API that other developers will want to work with and trust. These are the five steps required for high-quality API design:

1. `Plan the API `
- `API` specifications, like OpenAPI, provide the blueprint for your `API` design. It is better to think about different use cases in advance and ensure the `API` adheres to current `API` development standard </br>

2. `Build the API`
- `API` designers prototype `APIs` using boilerplate code. Once the prototype is tested, developers can customize it to internal specifications.

3. `Test the API`
- `API` testing is the same as software testing and must be done to prevent bugs and defects. `API` testing tools can be used to strength test the `API` against cyber attacks.

4. `Document the API  `
- While `APIs` are self-explanatory, `API` documentation acts as a guide to improve usability. Well-documented APIs that offer a range of functions and use cases tend to be more popular in a service-oriented architecture.

5. `Market the API`
- Just as Amazon is an online marketplace for retail, `API` marketplaces exist for developers to buy and sell other `APIs`. Listing your `API` can allow you to monetize it.

### What is `API testing`?
----

`API testing` strategies are similar to other software testing methodologies. The main focus is on validating server responses. `API testing` includes:
- Making multiple requests to API endpoints for performance testing. </br>
- Writing unit tests for checking business logic and functional correctness. </br>
- Security testing by simulating system attacks. </br>

### How to write `API documentation`?
----

Writing comprehensive `API documentation` is part of the API management process. `API documentation` can be auto-generated using tools or written manually. Some best practices include:

- Writing explanations in simple, easy-to-read English. Documents generated by tools can become wordy and require editing.
- Using code samples to explain functionality.
- Maintaining the documentation so it is accurate and up-to-date.
- Aiming the writing style at beginners
- Covering all the problems the `API` can solve for the users.

### How to use an `API`?
----

The steps to implement a new `API` include:
1. Obtaining an API key. This is done by creating a verified account with the API provider.
2. Set up an HTTP API client. This tool allows you to structure API requests easily using the API keys received.
3. If you don’t have an API client, you can try to structure the request yourself in your browser by referring to the API documentation.
4. Once you are comfortable with the new API syntax, you can start using it in your code.

### What is an `API gateway`?
----

- An API Gateway is an API management tool for enterprise clients that use a broad range of back-end services. API gateways typically handle common tasks like user authentication, statistics, and rate management that are applicable across all API calls.
- Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. It handles all the tasks involved in accepting and processing thousands of concurrent API calls, including traffic management, CORS support, authorization, and access control, throttling, monitoring, and API version management.

### What is `GraphQL`?
----
- GraphQL is a query language that was developed specifically for APIs. It prioritizes giving clients exactly the data they request and no more. It is designed to make APIs fast, flexible, and developer-friendly. As an alternative to REST, GraphQL gives front-end developers the ability to query multiple databases, microservices, and APIs with a single GraphQL endpoint. Organizations choose to build APIs with GraphQL because it helps them develop applications faster. Read more about GraphQL here.
- AWS AppSync is a fully managed service that makes it easy to develop GraphQL APIs by handling the heavy lifting of securely connecting to data sources like AWS DynamoDB, AWS Lambda, and more AWS AppSync can push real-time data updates over Websockets to millions of clients. For mobile and web applications, AppSync also provides local data access when devices go offline. Once deployed, AWS AppSync automatically scales GraphQL API execution engine up and down to meet API request volumes.