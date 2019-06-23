### Node
- V8 engine (and how it is important to Node)
    - [How JavaScript engines work](https://www.youtube.com/watch?v=p-iiEDtpy6I)

    - [Inside the V8 engine + 5 tips on how to write optimized code](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized-code-ac089e62b12e)

- Deferred Execution (process.nextTick)

- Event Loop
    - [Event Loop, Timers, and process.nextTick()](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)

    - [What the heck is the event loop?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

    - [In the loop](https://www.youtube.com/watch?v=cCOL7MC4Pl0) - Talk by Jake Archibald

- [Overview of Blocking vs Non-Blocking](https://nodejs.org/en/docs/guides/blocking-vs-non-blocking/)
- [Don't Block the Event Loop (or the Worker Pool)](https://nodejs.org/en/docs/guides/dont-block-the-event-loop/)
- [Timers in Node.js](https://nodejs.org/en/docs/guides/timers-in-node/)
- Request/Response cycle
- http, fs, process modules
- EventEmitter
    - [Understanding Node.js Event-Driven Architecture](https://medium.freecodecamp.org/understanding-node-js-event-driven-architecture-223292fcbc2d)
- Streams
- Buffers
- Error Conventions
- Node's Single threaded model.
- Creating child processes.
- Garbage Collection.

**Node Resources**

- [Official Docs](https://nodejs.org/docs/latest/api/)

- [Awesome NodeJS](https://github.com/sindresorhus/awesome-nodejs)

### Express

- [MVC](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) (Model, View, Controller)

    - [Model-View-Controller (MVC) Explained Through Ordering Drinks At The Bar](https://medium.freecodecamp.org/model-view-controller-mvc-explained-through-ordering-drinks-at-the-bar-efcba6255053)

- [morgan](https://github.com/expressjs/morgan) - log each request
- [cors](https://github.com/expressjs/cors) - enable CORS
- [body-parser](https://github.com/expressjs/body-parser) - Node.js body parsing middleware
- [Helmet.js](https://github.com/helmetjs/helmet) - help secure Express apps with various HTTP headers

**Express Resources**

- [Official Docs](https://expressjs.com/en/4x/api.html)

- [Github Repo](https://github.com/expressjs/express)

### Mongo

- SQL vs MongoDB ( Know the difference )

- Introduction to the Mongo Shell, JSON, BSON, and the MongoDB query language
- ORM
- CRUD
- collections
- documents
- `mongod`
- daemons
- models
- Mongo Shell, Query Operators, Update Operators
- Deeper dive on the Node.js MongoClient driver; CRUD operations in the driver; Cursors
- Schema Design
- Aggregation Framework

    - $unwind

    - $group
    - $project
- [Indexing](https://docs.mongodb.com/manual/indexes/?searchProperty=all&query=indexing) and [performance concepts](https://docs.mongodb.com/manual/administration/analyzing-mongodb-performance/index.html)

- [Mongoose](http://mongoosejs.com/docs/guide.html)

**Mongo Resources**

- [MongoDB Docs](https://docs.mongodb.com/)

- [MongoDB basics](https://university.mongodb.com/courses/M001/about)
- [MongoDB for Node.js Developers](https://university.mongodb.com/courses/M101JS/about)
- [Aggregation framework](https://university.mongodb.com/courses/M121/about)

#### Auth
- [bcrypt-nodejs](https://www.npmjs.com/package/bcrypt-nodejs)

- [jwt-simple](https://github.com/hokaccha/node-jwt-simple)
- [passport](https://github.com/jaredhanson/passport)
- [passport-jwt](https://github.com/themikenicholson/passport-jwt)
- [passport-local](https://github.com/jaredhanson/passport-local)
- salt
- rainbow tables
- never store plain-text passwords
- JWT
- token-based authentication
- stateless authentication
- JWT secret

#### APIs

- Rest

- #### GraphQL

    #### Understand

    - The type system

    - Queries and mutations
    - Resolvers
    - Fields
    - Arguments
    - Aliases
    - Fragments
    - Operation Name
    - Variables
    - Directives
    - Mutations
    - Inline Fragments
    - [Apollo Ecosystem](https://www.apollographql.com/) [They have their own docs]

    - [Official Docs](https://www.apollographql.com/docs/)

    - apollo-client
    - apollo-server
    - graphql-tools

    #### GraphQL Resources

    - [Official Docs](http://graphql.org/) [Read the **Learn** Segment for most of **Understand** Section]

    - Articles

    - [So what’s this GraphQL thing I keep hearing about?](https://medium.freecodecamp.org/so-whats-this-graphql-thing-i-keep-hearing-about-baf4d36c20cf)

    - [REST APIs are REST-in-Peace APIs. Long Live GraphQL.](https://medium.freecodecamp.org/rest-apis-are-rest-in-peace-apis-long-live-graphql-d412e559d8e4)
    - [The Anatomy of a GraphQL Query](https://dev-blog.apollodata.com/the-anatomy-of-a-graphql-query-6dffa9e9e747)
    - [GraphQL vs. REST](https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b)
    - [Full-stack React + GraphQL Tutorial](https://dev-blog.apollodata.com/full-stack-react-graphql-tutorial-582ac8d24e3b)
    - [The GraphQL stack: How everything fits together](https://dev-blog.apollodata.com/the-graphql-stack-how-everything-fits-together-35f8bf34f841)
    - [Tutorial: How to build a GraphQL server](https://dev-blog.apollodata.com/tutorial-building-a-graphql-server-cddaa023c035)
    - [GraphQL schema stitching](https://dev-blog.apollodata.com/graphql-schema-stitching-8af23354ac37)
    - [GraphQL Fragments are the Best Match for UI Components](https://blog.manifold.co/graphql-fragments-are-the-best-match-for-ui-components-72b8f61c20fe)
    - [Five Common Problems in GraphQL Apps (And How to Fix Them)](https://medium.freecodecamp.org/five-common-problems-in-graphql-apps-and-how-to-fix-them-ac74d37a293c)
    - Books
    - Learning GraphQL and Relay - Samer Buna

    #### Courses

    - Websites and Videos

    - [How to GraphQL](https://www.howtographql.com/)

    - **[Awesome GraphQL](https://github.com/chentsulin/awesome-graphql)**
