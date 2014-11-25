###《Scala in Action》中文翻译——个人自娱，与版权无关
***

# 目 录

## 第一部分：[SCALA基础](ebook/1.md)
- 第1章：[为何选择Scala](ebook/1.1.md)
  - 1.1 [Scala是什么?](ebook/1.1.1.md)
    - 1.1.1 [Scala是一种面向对象的语言](ebook/1.1.1.1.md)
    - 1.1.2 [Scala是一种函数式编程语言](ebook/1.1.1.2.md)  
    - 1.1.3 [Scala是一种多范式语言](ebook/1.1.1.3.md)
    - 1.1.4 [Scala是一种可伸缩和可扩展的语言](ebook/1.1.1.4.md)
    - 1.1.5 [Scala运行在JVM之上](ebook/1.1.1.5.md)
  - 1.2 [目前的危机](ebook/1.1.2.md)
    - 1.2.1 [摩尔定律的终结](ebook/1.1.2.1.md)
    - 1.2.2 [多核编程](ebook/1.1.2.2.md)
  - 1.3 [从Java向Scala过渡](ebook/1.1.3.md)
    - 1.3.1 [Scala可以提高生产力](ebook/1.1.3.1.md)
    - 1.3.2 [Scala用更少的代码做更多的事情](ebook/1.1.3.2.md)
  - 1.4 Coming from a dynamic language
    - 1.4.1 Case for static typing, the right way
  - 1.5 For the programming language enthusiast
  - 1.6 Summary


- 第2章：Getting start
  - 2.1 REPL with Scala interpreter
  - 2.2 Scala basics
    - 2.2.1 Basic types
    - 2.2.2 Defining variables
    - 2.2.3 Defining functions
  - 2.3 Working with Array and List
  - 2.4 Controlling flow with loops and ifs
  - 2.5 For-comprehensions
  - 2.6 Pattern matching
  - 2.7 Exception handling
  - 2.8 Command-line REST client: building a working example
    - 2.8.1 Introducing HttpClient library
    - 2.8.2 Building the client, step by step
  - 2.9 Summary


- 第3章：OOP in Scala
  - 3.1 Building a Scala MongoDB driver: user stories
  - 3.2 Classes and constructors
  - 3.3 Packaging
  - 3.4 Scala imports
  - 3.5 Objects and companion objects
  - 3.6 Mixin with Scala traits
    - 3.6.1 Class linearization
    - 3.6.2 Stackable traits
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
    - 4.9.1 Working with Set and SortedSet
    - 4.9.2 Working with Map and Tuple
    - 4.9.3 Under the hood of for-comprehension
    - 4.9.4 Use Option not Null
  - 4.10 Working with lazy collections: views and streams
    - 4.10.1 Convert a strict collection to a nonstrict collection with views
    - 4.10.2 Working with Streams
  - 4.11 Divide and conquer with parallel collections
    - 4.11.1 Parallel collection hierarchy
    - 4.11.2 Switching between sequential and parallel collections
  - 4.12 Summary


- 第5章：Functional programming
  - 5.1 What is functional programming?
    - 5.1.1 The benefits of referential transparency
    - 5.1.2 A pure functional program
  - 5.2 Moving from OOP to functional programming
    - 5.2.1 Pure vs. impure programming
    - 5.2.2 Object-oriented patterns in functional programming
    - 5.2.3 Modeling purely functional programs
  - 5.3 Functions in all shapes and forms
    - 5.3.1 Methods vs. functions
    - 5.3.2 Higher-order functions
    - 5.3.3 Function currying
    - 5.3.4 Function composition and partial functions
    - 5.3.5 Recursion
  - 5.4 Thinking recursively
    - 5.4.1 Tail recursion
  - 5.5 Algebraic data types
  - 5.6 Why does functional programming matter?
  - 5.7 Building higher abstractions with monads
    - 5.7.1 Managing state using monads
    - 5.7.2 Building blocks for monads
  - 5.8 Summary


## 第二部分：WORKING WITHSCALA
- 第6章：Building web applications in functional style
  - 6.1 Building weKanban: a simple web-based Kanban board
  - 6.2 Building Scala applications using Simple Build Tool
    - 6.2.1 Setting up SBT
    - 6.2.2 Understanding the basics of SBT
    - 6.2.3 Setting up the weKanban project with SBT
  - 6.3 Introducing the Scalaz HTTP module
    - 6.3.1 How the Scalaz HTTP library works
    - 6.3.2 Configuring Scalaz with SBT
    - 6.3.3 Building your first web page using Scalaz
  - 6.4 Summary

- 第7章：Connecting to a database
  - 7.1 Adding a new story to a weKanban board
    - 7.1.1 Connecting to a database using Squeryl
    - 7.1.2 Saving a new story to the database
    - 7.1.3 Building the Create Story web page
  - 7.2 Building the Kanban board page
    - 7.2.1 Creating the view for the Kanban board
    - 7.2.2 Moving cards in the Kanban board
  - 7.3 Summary


- 第8章：Building scalable and extensible components
  - 8.1 Building your first component in Scala
    - 8.1.1 Abstract type members
    - 8.1.2 Self type members
    - 8.1.3 Building a scalable component
    - 8.1.4 Building an extensible component
  - 8.2 Types of types in Scala
    - 8.2.1 Structural types
    - 8.2.2 Higher-kinded types
    - 8.2.3 Phantom types
  - 8.3 Ad hoc polymorphism with type classes
    - 8.3.1 Modeling orthogonal concerns using type classes
    - 8.3.2 Solving the expression problem using type classes
  - 8.4 Summary


- 第9章：Concurrency programming in Scala
  - 9.1 What is concurrent programming?
  - 9.2 Challenges with concurrent programming
    - 9.2.1 Difficulties of shared-state concurrency with threads
    - 9.2.2 New trends in concurrency
  - 9.3 Implementing message-passing concurrency
    - 9.3.1 with actors
    - 9.3.2 What is ActorSystem?
    - 9.3.3 How do Scala actors work?
    - 9.3.4 Divide and conquer using actors
    - 9.3.5 Fault tolerance
    - 9.3.6 made easy with a supervisor
  - 9.4 Composing concurrent programs with Future and Promise
    - 9.4.1 Divide and conquer with Future
    - 9.4.2 Mixing Future with actors
  - 9.5 When should you not use actors?
  - 9.6 Summary


- 第10章：Building confidence with testing
  - 10.1 Importance of automated testing
  - 10.2 Automated test generation using ScalaCheck
    - 10.2.1 Testing the behavior of a string with ScalaCheck
    - 10.2.2 ScalaCheck generators
    - 10.2.3 Working with ScalaCheck
  - 10.3 Test-driven development cycle
    - 10.3.1 Setting up your environment for TDD
    - 10.3.2 Using JUnit to test Scala code
  - 10.4 Better tests with dependency injection
    - 10.4.1 Techniques to implement DI
    - 10.4.2 Cake pattern
    - 10.4.3 Structural typing
    - 10.4.4 Implicit parameters
    - 10.4.5 Dependency injection in functional style
    - 10.4.6 Using a dependency injection framework: Spring
  - 10.5 Behavior-driven development using Specs2
    - 10.5.1 Getting started with Specs2
    - 10.5.2 Working with specifications
  - 10.6 Testing asynchronous messaging systems
  - 10.7 Summary


## 第三部分：ADVANCED STEPS
- 第11章：Interoperability between Scala and Java
  - 11.1 Using Java classes in Scala
    - 11.1.1 Working with Java static members
    - 11.1.2 Working with Java checked exceptions
    - 11.1.3 Working with Java generics using existential types
  - 11.2 Using Scala classes in Java
    - 11.2.1 Using Scala annotations
  - 11.3 Building web applications in Scala using Java frameworks
    - 11.3.1 Building the model, view, and controller
    - 11.3.2 Configuring and running the application
  - 11.4 Summary
- 第12章：Scalable and distributed applications using Akka
  - 12.1 The philosophy behind Akka
  - 12.2 Simple concurrency with Akka
    - 12.2.1 Remote actors
    - 12.2.2 Making mutable data safe with STM
    - 12.2.3 Agents
    - 12.2.4 Dataflow
  - 12.3 Building a real-time pricing system: Akkaoogle
    - 12.3.1 The high-level architecture of Akkaoogle
    - 12.3.2 Setting up the project for Akkaoogle
    - 12.3.3 Implementing the domain models
    - 12.3.4 Implementing the core with actors
    - 12.3.5 Increase scalability with remote actors, dispatchers, and routers
    - 12.3.6 Handling shared resources with Agent
  - 12.4 Adding asynchronous HTTP support with
    - 12.4.1 Play2-mini
    - 12.4.2 Setting up Play2-mini
    - 12.4.3 Running with Play2-mini
  - 12.5 Summary
