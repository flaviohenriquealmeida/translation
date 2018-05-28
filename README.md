# TRANSLATED SUMMARY FROM THE BOOK MEAN

- 1 Introduction
    * 1.1 MEAN Stack
    * 1.2 A bet on JavaScript
    * 1.3 Advantages of the stack
    * 1.4 Overview of our journey
    * 1.5 Installing Node.js
- 2 Express: web framework for Node.js
    * 2.1 Express and its role
    * 2.2 Project structure and package.json
    * 2.3 Installing Express through Npm
    * 2.4 Creating the Express Configuration Module
    * 2.5 Understanding environment variables and middlewares
    * 2.6 View and template engine
    * 2.7 Configuring routes
    * 2.8 Creating controllers
    * 2.9 Loading dependencies with express-load
    * 2.10 Listing contacts
    * 2.11 A little bit about REST API
    * 2.12 Returning contact from the list
- 3 Bower: front-end dependency manager
    * 3.1 Installation
    * 3.2 bower.json and our dependencies
    * 3.3 Downloading front-end dependencies
    * 3.4 Changing the Target Folder with .bowerrc
    * 3.5 Other commands
- 4 AngularJS: Google's MVC framework
    * 4.1 An old acquaintance: DOM
    * 4.2 Difficulties arising from manipulation of the DOM
    * 4.3 Characteristics of AngularJS
    * 4.4 Preparing the environment
    * 4.5 Enabling AngularJS on our page
    * 4.6 Our first module with AngularJS
    * 4.7 Angular expression (AE)
    * 4.8 Our first controllers
    * 4.9 $ scope: the queue between controller and view
    * 4.10 AngularJS and the MVC model
    * 4.11 Performing Actions on the Controller Through Policy
    * 4.12 The magic of data binding
    * 4.13 Single page application (SPA) and our project
    * 4.14 The ngRoute module
    * 4.15 Creating Partial Views
    * 4.16 Configuring Routes with $ routeProvider
    * 4.17 The object $ routeParams
    * 4.18 Bootstrap: professional look in our views
    * 4.19 The ng-repeat directive
    * 4.20 The ng-model directive and list filtering
    * 4.21 Reviewing What We Learn
- 5 Integrating AngularJS and Express
    * 5.1 The $ http service
    * 5.2 Asynchronous programming and callback HELL
    * 5.3 Promises: fighting the HELL callback
    * 5.4 Getting contacts with $ http
    * 5.5 The ngResource module: working at a high level
    * 5.6 Consuming REST Endpoints with $ resource
    * 5.7 Adding exclusion route to the Express
    * 5.8 Express: better organizing our routes
    * 5.9 Removing contacts from the list
    * 5.10 The ng-hide and ng-show directives
    * 5.11 Displaying Selected Contact
    * 5.12 Saving a Contact
    * 5.13 Adding Write Route to Express
    * 5.14 Services: better organizing our code
- 6 MongoDB: document-based database
    * 6.1 Relational vs. NoSQL: Is there a winning bank?
    * 6.2 Searching for the smallest possible impedance: JSON "everywhere"
    * 6.3 Installing MongoDB
    * 6.4 Using Mongo Shell
    * 6.5 The concept of a document
    * 6.6 The ObjectId type
    * 6.7 Creating the application bank
    * 6.8 Collections and insertion of documents
    * 6.9 Searching Documents
    * 6.10 The cursor object
    * 6.11 Searching with discretion
    * 6.12 Query selectors
    * 6.13 Indexing documents
    * 6.14 Returning Partial Documents
    * 6.15 Removing Documents
    * 6.16 Updating Documents
    * 6.17 Performing upserts
    * 6.18 $ set: update modifier
    * 6.19 Embedded Documents
    * 6.20 Simulating JOINS on the application side
    * 6.21 DBRefs: database references
- 7 Integrating Express and MongoDB
    * 7.1 Mongo Driver
    * 7.2 Schematic missing?
    * 7.3 Mongoose Object-Document Modeler
    * 7.4 Managing the Connection
    * 7.5 Creating schemas
    * 7.6 Using Templates
    * 7.7 Searching for Documents
    * 7.8 Searching for ID
    * 7.9 Removing Documents
    * 7.10 Updating documents
    * 7.11 Persistence Functions in Model or Document?
    * 7.12 Creating References
    * 7.13 Modifying our view to display emergencies
    * 7.14 The ng-options directive
    * 7.15 Populate and Search for References
- 8 Authentication with Passport
    * 8.1 OAuth 2.0
    * 8.2 Authentication Provider Registration
    * 8.3 OAuth 2.0 with Passport
    * 8.4 Authentication strategy
    * 8.5 Defining User Schema
    * 8.6 Mongoose and plugins
    * 8.7 Serialization and deserialization of the user
    * 8.8 Protecting resources
    * 8.9 Combining server / client views
    * 8.10 Implementing Logout
    * 8.11 REST Endpoints: allowing only authenticated access
- 9 Making your application even more secure
    * 9.1 Helmet: security middlewares
    * 9.2 MongoDB / REST API: avoiding query selector injection
    * 9.3 Avoiding document replace
    * 9.4 Dealing with 404
- 10 Grunt: front-end task automation
    * 10.1 Welcome to Grunt
    * 10.2 The Gruntfile.js File
    * 10.3 Installing our first plugin
    * 10.4 Tasks
    * 10.5 Targets
    * 10.6 Task Shortcut
    * 10.7 Minification and concatenation techniques
    * 10.8 grunt-usemin: Minimizing and concatenating with Grunt
    * 10.9 The tasks usemin and useminPrepare
    * 10.10 Angular and Minimal
- 11 Testing the application
    * 11.1 Karma: instant feedback of unit tests
    * 11.2 Jasmine: test framework
    * 11.3 Creating Test Suites
    * 11.4 Running Karma Test Suites
    * 11.5 Angular-mocks and integration with Jasmine
    * 11.6 $ httpBackend: "mockando" our backend
    * 11.7 Testing from end to end
    * 11.8 Protractor: end-to-end testing with AngularJS
    * 11.9 Configuring the Protractor for the Application
    * 11.10 Automating User Authentication
    * 11.11 Testing Scenarios
    * 11.12 PageObject: improving readability and maintenance of tests
- 12 Continuous integration
    * 12.1 Travis CI
    * 12.2 Configuring .travis.yml
    * 12.3 Associating Your Repository with Travis
    * 12.4 TaaS: test as a service with SauceLabs
    * 12.5 Preparing the application for different environments
    * 12.6 Integrating Travis and Sauce Labs
- 13 Creating Your Own Policies
    * 13.1 DDO Directive Definition Object
    * 13.2 Isolating the scope of our policy
    * 13.3 Transclusion
    * 13.4 Separating the DDO from your template
    * 13.5 More directives
    * 13.6 Manipulating DOM through Policy
    * 13.7 The $ watch
    * 13.8 Working with $ broadcast
    * 13.9 Testing Policies
- 14 Deploy the application
    * 14.1 Continuous Deploy
    * 14.2 OpenShift: platform as a service (PaaS)
    * 14.3 Configuring the deploy environment
    * 14.4 Preparing the application for deploy
    * 14.5 Integrating Travis with OpenShift
    * 14.6 Final considerations    

# TRANSLATED SUMMARY FROM THE BOOK CANGACEIRO JAVASCRIPT    

- 1 Prologue: Once upon a time in the hinterland
    * 1.1 The problem with our code
    * 1.2 The Model-View-Controller (MVC)
- 2 Do you have the courage to negotiate with the cangaceiro?
    * 2.1 The Role of a Model
    * 2.2 The Trading Class
    * 2.3 Class Builder
    * 2.4 Class methods
    * 2.5 Encapsulation
    * 2.6 The syntax get
    * 2.7 Immutable objects
    * 2.8 Is the instance really immutable?
    * 2.9 Defensive schedule
    * 2.10 Less verbosity in constructor with Object.assign
    * 2.11 Shortcut to literal object properties
    * 2.12 Surprises of declarations with var
    * 2.13 Declaration of variables with let
    * 2.14 Temporal Dead Zone
- 3 In the cangaço, it's action everywhere.
    * 3.1 The role of a controller
    * 3.2 The NegotiationController class
    * 3.3 Associating controller methods with user actions
    * 3.4 Avoiding unnecessarily moving the DOM
    * 3.5 Creating a Trading Instance
    * 3.6 Creating a Date Object from User Input
    * 3.7 A challenge with dates
    * 3.8 Solving a problem with the functional paradigm
    * 3.9 Arrow functions: leaving the code even less verbose
- 4 Two weights, two measures?
    * 4.1 Isolating Date Translation Responsibility
    * 4.2 Static Methods
    * 4.3 Template string
    * 4.4 The good practice of fail-fast
    * 5 The flock must follow a rule
    * 5.1 Creating a new template
    * 5.2 The Achilles tendon of JavaScript
    * 5.3 Shielding our model
- 6 The fashion in the cangaço
    * 6.1 The Role of View
    * 6.2 Our View solution
    * 6.3 Building a dynamic template with the map function
    * 6.4 Totalizing the volume of negotiations
    * 6.5 Totalizing with reduce
- 7 The plan
    * 7.1 Default parameter
    * 7.2 Creating the MessageView class
    * 7.3 Code Inheritance and Reuse
    * 7.4 Abstract classes?
    * 7.5 More info: super
    * 7.6 Acquiring a New Habit with Const
- 8 A cangaceiro can delegate tasks
    * 8.1 What if we update View when the template changes?
    * 8.2 Dribbling this dynamic
    * 8.3 Arrow function and its lexical scope
- 9 They cheated the cangaceiro, right?
    * 9.1 The Proxy Project Pattern
    * 9.2 Learning to Work with Proxy
    * 9.3 Building Reading Traps
    * 9.4 Building Writing Traps
    * 9.5 Reflect API
    * 9.6 An Unexpected Problem
    * 9.7 A solution for our traps to work
    * 9.8 Building traps for methods
    * 9.9 A pinch of ES2016 (ES7)
    * 9.10 Applying the Solution in NegotiationController
- 10 Accomplice in ambush
    * 10.1 The Factory Design Pattern
    * 10.2 Our proxy is not yet 100%!
    * 10.3 Associating Model and View through Bind Class
    * 10.4 REST Parameters
- 11 Date of the Hells!
    * 11.1 The problem with the input date
    * 11.2 Adjusting our converter
    * 11.3 Handling Exceptions
    * 11.4 Creating our own exception: first attempt
    * 11.5 Creating our own exception: second attempt
- 12 Pillaging what matters!
    * 12.1 Server and Infrastructure
    * 12.2 Ajax requests with the XMLHttpRequest object
    * 12.3 Performing parse response
    * 12.4 Separating Responsibilities
- 13 Fighting to the end
    * 13.1 Callback HELL
    * 13.2 The Promise Design Pattern
    * 13.3 Creating Promises
    * 13.4 Creating a Service to Isolate the Complexity of XMLHttpRequest
    * 13.5 Solving Promises Sequentially
    * 13.6 Solving Promises In Parallel
    * 13.7 Sorting the Period
    * 13.8 Preventing Duplicate Imports
    * 13.9 The filter () and some ()
- 14 The pocket is stuck!
    * 14.1 IndexedDB, the browser database
    * 14.2 The connection to the bank
    * 14.3 Our first store
    * 14.4 Bank Update
    * 14.5 Transactions and persistence
    * 14.6 Cursors
- 15 Putting the house in order
    * 15.1 The ConnectionFactory Class
    * 15.2 Creating Stores
    * 15.3 Ensuring an application-only connection
    * 15.4 The Pattern Pattern Module Pattern
    * 15.5 Monkey Patch: great powers bring great responsibilities
- 16 Entering the Line
    * 16.1 The DAO Design Pattern
    * 16.2 Creating our DAO of Negotiations
    * 16.3 Implementing Inclusion Logic
    * 16.4 Implementing Listing Logic
    * 16.5 Creating a DAOFactory
    * 16.6 Combining Design Patterns
    * 16.7 Displaying All Negotiations
    * 16.8 Removing All Negotiations
- 17 Divide to conquer
    * 17.1 ES2015 Modules (ES6)
    * 17.2 Installing the loader
    * 17.3 Transforming Scripts into Modules
    * 17.4 The role of a transcompiler
    * 17.5 Babel, installation and build-step
    * 17.6 Sourcemap
    * 17.7 Compiling Files in Real Time
    * 17.8 Barrel, simplifying the import of modules
- 18 Going beyond
    * 18.1 ES2017 (ES8) and the async / await syntactic sugar
    * 18.2 Find out more: generators
    * 18.3 Refactoring the project with async / wait
    * 18.4 Ensuring compatibility with ES2015
    * 18.5 Better Handling with Exceptions
    * 18.6 Debounce pattern: controlling anxiety
    * 18.7 Implementing Debounce pattern
- 19 Reaching the Limit
    * 19.1 The Decorator Design Pattern
    * 19.2 Supporting Decorator through Babel
    * 19.3 An Unexpected Problem with our Decorator
    * 19.4 Designing a DOM Injector
    * 19.5 Class Decorator
    * 19.6 Simplifying Ajax requests with the Fetch API
    * 19.7 Configuring a request with Fetch API
    * 19.8 Shortcut to Property of Literal Objects
    * 19.9 Validation with default parameter
    * 19.10 Reflect-metadata: advancing in metaprogramming
    * 19.11 Adding Metadata with Method Decorator
    * 19.12 Extracting Metadata with a Class Decorator
- 20 Final confrontation
    * 20.1 Webpack, Module Builder
    * 20.2 Preparing the Site for the Webpack
    * 20.3 The fearsome webpack.config.js
    * 20.4 Babel-loader, the bridge between Webpack and Babel
    * 20.5 Preparing the production build
    * 20.6 Changing the environment with cross-env
    * 20.7 WebPack Dev Server and Configuration
    * 20.8 Treating CSS Files as Modules
    * 20.9 Solving FOUC (Flash of Unstyled Content)
    * 20.10 We solve one problem and create another, but there is a solution!
    * 20.11 Importing Scripts
    * 20.12 Dealing with Global Dependencies
    * 20.13 Optimizing the build with Scope Hoisting
    * 20.14 Separating Our Code from Libraries
    * 20.15 Generating the main page automatically
    * 20.16 Further simplifying the import of modules
    * 20.17 Code splitting and Lazy loading
    * 20.18 System.import vs import
    * 20.19 What are the distribution files?
    * 20.20 Project Deploy in Github Pages
    * 20.21 Changing the API Address in Production Build
    * 20.22 Final considerations