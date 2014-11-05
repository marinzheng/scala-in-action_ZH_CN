《Scala in Action》中文翻译——个人自误，与版权无关
===============


# 目 录

## 第一部分：SCALA基础
- 第1章：Why Scala?
  - 1.1 What’s Scala?
    * Scala as an object-oriented language
    * Scala as a functional language  
    * Scala as a multi-paradigm language
    * Scala as a scalable and extensible language
    * Scala runs on the JVM
  - 1.2 The current crisis
    * End of Moore’s law
    * Programming for multicores
  - 1.3 Transitioning from Java to Scala
    * Scala improves productivity
    * Scala does more with less code
  - 1.4 Coming from a dynamic language
    * Case for static typing, the right way
  - 1.5 For the programming language enthusiast
  - 1.6 Summary


- 第2章：Getting start
  - 2.1 REPL with Scala interpreter
  - 2.2 Scala basics
    * Basic types
    * Defining variables
    * Defining functions
  - 2.3 Working with Array and List
  - 2.4 Controlling flow with loops and ifs
  - 2.5 For-comprehensions
  - 2.6 Pattern matching
  - 2.7 Exception handling
  - 2.8 Command-line REST client: building a working example
    * Introducing HttpClient library
    * Building the client, step by step
  - 2.9 Summary


- 第3章：OOP in Scala
  - 3.1 Building a Scala MongoDB driver: user stories
  - 3.2 Classes and constructors
  - 3.3 Packaging
  - 3.4 Scala imports
  - 3.5 Objects and companion objects
  - 3.6 Mixin with Scala traits
    * Class linearization
    * Stackable traits
  - 3.7 Case class
  - 3.8 Named and default arguments and copy constructors
  - 3.9 Modifiers
  - 3.10 Value classes: objects on a diet
  - 3.11 Implicit conversion with implicit classes
  - 3.12 Scala class hierarchy
  - 3.13 Summary


- 第4章：Having fun with functional data structures
  - 4.1 Introducing type parameterization
  - 4.2 Type variance with covariance and contravariance
  - 4.3 Lower and upper type bounds
  - 4.4 Higher-order functions, including map, flatMap, and friends
  - 4.5 Using foldLeft and foldRight
  - 4.6 Building your own function objects
  - 4.7 Scala collection hierarchy
  - 4.8 Mutable and immutable collections
  - 4.9 Working with List and ListBuffer
    * Working with Set and SortedSet
    * Working with Map and Tuple
    * Under the hood of for-comprehension
    * Use Option not Null
  - 4.10 Working with lazy collections: views and streams
    * Convert a strict collection to a nonstrict collection with views
    * Working with Streams
  - 4.11 Divide and conquer with parallel collections
    * Parallel collection hierarchy
    * Switching between sequential and parallel collections
  - 4.12 Summary


- 第5章：Functional programming
  - 5.1 What is functional programming?
    * The benefits of referential transparency
    * A pure functional program
  - 5.2 Moving from OOP to functional programming
    * Pure vs. impure programming
    * Object-oriented patterns in functional programming
    * Modeling purely functional programs
  - 5.3 Functions in all shapes and forms
    * Methods vs. functions
    * Higher-order functions
    * Function currying
    * Function composition and partial functions
    * Recursion
  - 5.4 Thinking recursively
    * Tail recursion
  - 5.5 Algebraic data types
  - 5.6 Why does functional programming matter?
  - 5.7 Building higher abstractions with monads
    * Managing state using monads
    * Building blocks for monads
  - 5.8 Summary


## 第二部分：WORKING WITHSCALA
- 第6章：Building web applications in functional style
  - 6.1 Building weKanban: a simple web-based Kanban board
  - 6.2 Building Scala applications using Simple Build Tool
    * Setting up SBT
    * Understanding the basics of SBT
    * Setting up the weKanban project with SBT
  - 6.3 Introducing the Scalaz HTTP module
    * How the Scalaz HTTP library works
    * Configuring Scalaz with SBT
    * Building your first web page using Scalaz
  - 6.4 Summary

- 第7章：Connecting to a database
  - 7.1 Adding a new story to a weKanban board
    * Connecting to a database using Squeryl
    * Saving a new story to the database
    * Building the Create Story web page
  - 7.2 Building the Kanban board page
    * Creating the view for the Kanban board
    * Moving cards in the Kanban board
  - 7.3 Summary


- 第8章：Building scalable and extensible components
  - 8.1 Building your first component in Scala
    * Abstract type members
    * Self type members
    * Building a scalable component
    * Building an extensible component
  - 8.2 Types of types in Scala
    * Structural types
    * Higher-kinded types
    * Phantom types
  - 8.3 Ad hoc polymorphism with type classes
    * Modeling orthogonal concerns using type classes
    * Solving the expression problem using type classes
  - 8.4 Summary


- 第9章：Concurrency programming in Scala
  - 9.1 What is concurrent programming?
  - 9.2 Challenges with concurrent programming
    * Difficulties of shared-state concurrency with threads
    * New trends in concurrency
  - 9.3 Implementing message-passing concurrency
    * with actors
    * What is ActorSystem?
    * How do Scala actors work?
    * Divide and conquer using actors
    * Fault tolerance
    * made easy with a supervisor
  - 9.4 Composing concurrent programs with Future and Promise
    * Divide and conquer with Future
    * Mixing Future with actors
  - 9.5 When should you not use actors?
  - 9.6 Summary


- 第10章：Building confidence with testing
  - 10.1 Importance of automated testing
  - 10.2 Automated test generation using ScalaCheck
    * Testing the behavior of a string with ScalaCheck
    * ScalaCheck generators
    * Working with ScalaCheck
  - 10.3 Test-driven development cycle
    * Setting up your environment for TDD
    * Using JUnit to test Scala code
  - 10.4 Better tests with dependency injection
    * Techniques to implement DI
    * Cake pattern
    * Structural typing
    * Implicit parameters
    * Dependency injection in functional style
    * Using a dependency injection framework: Spring
  - 10.5 Behavior-driven development using Specs2
    * Getting started with Specs2
    * Working with specifications
  - 10.6 Testing asynchronous messaging systems
  - 10.7 Summary


## 第三部分：ADVANCED STEPS
- 第11章：Interoperability between Scala and Java
  - 11.1 Using Java classes in Scala
    * Working with Java static members
    * Working with Java checked exceptions
    * Working with Java generics using existential types
  - 11.2 Using Scala classes in Java
    * Using Scala annotations
  - 11.3 Building web applications in Scala using Java frameworks
    * Building the model, view, and controller
    * Configuring and running the application
  - 11.4 Summary
- 第12章：Scalable and distributed applications using Akka
  - 12.1 The philosophy behind Akka
  - 12.2 Simple concurrency with Akka
    * Remote actors
    * Making mutable data safe with STM
    * Agents
    * Dataflow
  - 12.3 Building a real-time pricing system: Akkaoogle
    * The high-level architecture of Akkaoogle
    * Setting up the project for Akkaoogle
    * Implementing the domain models
    * Implementing the core with actors
    * Increase scalability with remote actors, dispatchers, and routers
    * Handling shared resources with Agent
  - 12.4 Adding asynchronous HTTP support with
    * Play2-mini
    * Setting up Play2-mini
    * Running with Play2-mini
  - 12.5 Summary
