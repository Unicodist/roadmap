
## 1. C# Language Basics 
Reference can be found here :
* https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/
* https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/types/

* [x] Statements & Operators
	* [x] Statements
	* [x] Expressions
	* [x] Anonymous Functions
	* [x] Equality and Equality Comparisons
* [x] Types
   * [x] Data Types
   * [x] Boxing and Unboxing
   * [x] String & Numeric Types
   * [x] Type Dynamics
   * [x] Date time handling
   * [x] others specified in the above reference

* [x] Casting
	* [x] What
	* [x] Syntax
	* [x] Quirks 
		* [x] Data loss in some specific cases
		* [x] Wrong conversion for some data types etc  

* [x] Classes
	* [x] Objects
	* [x] Structures
	* [x] Inheritance 
	* [x] Polymorphism 
	* [x] Members
	* [x] Properties 
	* [x] Methods
	* [x] Constructors
	* [x] Finalizers / Desctructors 
	* [x] Partial Class
	* [x] Nested Types
	* [x] Anonymous Types
* [x] Interfaces
* [x] Delegates 
* [x] Arrays
* [x] Strings
* [x] Indexers
* [x] Events
	* [x] Keyboard Events
	* [x] Mouse Events
* [x] Generics
	* [x] What are they
	* [x] Why
	* [x] How to create custom Generic methods
	* [x] Tradeoffs and advantage
	* [x] Generic Type Parameters
	* [x] Generic Classes
	* [x] Generic Interfaces
	* [x] Generic Methods
	* [x] Generics and Arrays
	* [x] Generic Delegates
	* [x] Generics and Reflection
	* [x] Generics and Attributes
* [x] Namespaces
* [x] Unsafe code and Points
* [x] Exception and Exception Handling
* [x] File System and File Handling

* [x] Collections
	* [x] What are collections
	* [x] List, IList, Enumerable, IEnumerable
	* [x] Dictionary, Lookup
	* [x] LINQ methods
		* [x] Query Syntax
		* [x] Fluent Syntax
	* [x] Some Collections methods concepts
		* [x] Map method [Select]
		* [x] Filter method [Where]
		* [x] Aggregate
		* [x] SOME / ANY  / ALL etc
		* [x] Language-specific functions/syntax for the above concepts




## 2. Object Oriented Basics :
* [x] Class
* [x] Interface
* [x] Inheritance 
* [x] Composition 
* [x] Why composition over inheritance?
* [x] Access modifier [Public,Private, Protected, Internal] and when to use them
* [x] Implementing inheritance
* [x] Interface inheritance
* [x] static methods and properties
* [x] Overloading [When to use them, when not to use them]
* [x] Sealing class
* [x] Extension methods
	* [x] What are they
	* [x] How are they useful
	* [x] How to use them
	* [x] How to create custom extension methods
* [x] Attributes
	* [x] What are they
	* [x] How to write custom attributes
## 3. .Net Core MVC
*  Tutorial Web Apps : https://docs.microsoft.com/en-us/learn/modules/create-razor-pages-aspnet-core/?view=aspnetcore-3.1
* Tutorial : Security : https://docs.microsoft.com/en-us/learn/modules/secure-aspnet-core-identity/?view=aspnetcore-3.1
* Main Link : https://docs.microsoft.com/en-us/aspnet/core/getting-started/?view=aspnetcore-3.1&tabs=windows

### 3.1 Fundamentals
* https://docs.microsoft.com/en-us/aspnet/core/fundamentals/?view=aspnetcore-3.1&tabs=windows
  
* [x] Startup Class
* [x] Dependency Injection ( Services )
* [x] Servers ( Kestrel and Reverse Proxy )
* [x] Environments ( Dev, Stage, Prod )
* [x] Basic Routing ( Model View Controller )
* [x] Logging
* [x] Error Handling
* [x] Static Files
* [x] Views
* [x] Controller
* [x] Model
* [x] Tag Helpers
	* [x] Anchor
	* [x] Form
	* [x] Input
	* [x] Label
	* [x] Link
	* [x] Image
	* [x] Select
	* [x] Textarea
	* [x] Validation Message

### 3.2 Basic Clean Code Practices
* [x]  Why ? 
* [x] Benefis
* [x] Naming ( with examples )
	* [x] Intention Revealing Names
	* [x] Avoid Disinformation
	* [x] Meaningful Distinctions
	* [x] Pronounceable Names
	* [x] Searchable Names
	* [x] Avoid Mental Mapping
	* [x] Class Names
	* [x] Method Names
	* [x] Property Names
	* [x] Solution Based Domain Names
	* [x] Meaningful Context
* [x] Functions
	* [x] Blocks  and Indentation / Formatting
	* [x] Switch Statements
	* [x] Using Descriptive Names
	* [x] Functions Arguments / Parameters
		* [x] Parameter Counts and Limit
		* [x] Flag Parameters
		* [x] Dyadic Functions
		* [x] Triads
		* [x] Argument Lists
		* [x] Argument Naming
* [x] Command Query Separation 
* [x] CQS Exception
* [x] Exceptions
* [x] Comments
	* [x] Good Comments
	* [x] When to Write Comments
	* [x] Why we avoid comments
* [x] Code, HTML, CSS Formatting

### 3.3 Basic DDD Concepts
* https://domainlanguage.com/
* https://domainlanguage.com/ddd/reference/

* [x] Entity 
* [x] Value Objects
* [x] Services
* [x] Modules
* [x] Aggregates
* [x] Repositories
* [x] Factories
* [x] Understanding Core Domain
### 3.4 Basic Unit Test
* [x]  Setup Method
* [x]  Exception Testing
* [x]  Dependant Tests
* [x]  Mocking
* [x] Spy Object
* [x] Multiple Assertions

## 4 Dependency injection
* [x] What
* [x] Why
* [x] How to use them
* [x] Asp.Net core DI
* [x] Configuration in Startup
* [x] Can the configuration be moved to individual projects?

## 5 Database Concepts
Mainly MySQL based
* [x] Data Types
	* [x] Int { All types }	
		* [x] Tiny Int
		* [x] Small Int
		* [x] Medium Int
		* [x] Big Int
	* [x] Decimal 
		* [x] Float, Double
		* [x] Single bit : bit
		* [x] Serial
		* [x] Boolean
		* [x] ZeroFill types
		* [x] Unsigned and Signed
	* [x] Date / Time
		* [x] Date
		* [x] Time
		* [x] DateTime
	* [x] TimeStamp
		* [x] Year
		* [x] String
		* [x] Char
		* [x] VarChar
		* [x] Enum
	* [x] Binary
	* [x] VarBinary
	* [x] TinyBlob
	* [x] Blob
	* [x] Long Blog
	* [x] Tiny Text
	* [x] Text
	* [x] Long Text
	* [x] SET
* [x] Data type deciding principle
* [x] Difference between Varchar and Char
* [x] Unicode Support Type
* [x] Concept of Character Sets and Unicode Support Characters Sets

* [x] Rows / Columns
	* [x] Size of Rows
	* [x] Column Sizes
	* [x] Column Ordering
	* [ ] Proper Column Naming
	* [ ] Large Table Concept
	* [ ] Performance Implication of Rows vs Columns
* [ ] Table
	* [ ] Table Size
	* [ ] Table Types
	* [ ] Database Engine Types
	* [ ] Character Sets
	* [ ] How data is stored in Table
* [ ] Keys
	* [ ] Primary
	* [ ] Foreign
	* [ ] Unique
* [ ] DML
	* [ ] Create / Insert
	* [ ] Update 
	* [ ] Delete
	* [ ] Select
	* [ ] Ordering
	* [ ] Pagination
	* [ ] Where
		* [ ] Normal Operators ( = , > , < , <=, >=, <>, != etc)
		* [ ] Not Operator
		* [ ] Between Operator
	* [ ] In
	* [ ] Like
	* [ ] Wild Card ( % )
	* [ ] Aggregate Functions
	* [ ] Count
	* [ ] Sum
	* [ ] Min
	* [ ] Max
	* [ ] Group by
	* [ ] Having
* [ ] DDL
	* [ ] Table
	* [ ] Create
	* [ ] Alter
	* [ ] Copy
	* [ ] Drop
	* [ ] Truncate
	* [ ] Column
		* [ ] Create
		* [ ] Alter
		* [ ] Rename
	* [ ] Reorder
	* [ ] Drop
	* [ ] Default Value
* [ ] Transaction
	* [ ] Start
	* [ ] Commit
	* [ ] Rollback
	* [ ] Concurrency
	* [ ] Nested Transaction 
* [ ] Index
	* [ ] Why?
	* [ ] Types of Index
	* [ ] Use of Data Structure in Index
	* [ ] Creating Index
	* [ ] Updating Index
	* [ ] Query Optimization / Usage of Explain
* [ ] Relationship
	* [ ] One to One
	* [ ] One to Many
	* [ ] Many to Many
	* [ ] Performance Consideration of Relationship
	* [ ] Defining Relationship and Dropping
* [ ] Joins
	* [ ] Inner
	* [ ] Outer (Left, Right )
	* [ ] Full
* [ ] Subquery 
	* [ ] Defining Subquery
	* [ ] Using Subquery
	* [ ] SubQuery vs Joins
* [ ] Transaction Isolation Levels
	* [ ] Read Committed
	* [ ] Repeatable Read
	* [ ] Read Uncommitted
	* [ ] Serializable
* [ ] Database Engine Concept
	* [ ] InnoDB
	* [ ] MyISAM
	* [ ] Memory
	* [ ] Archive 
* [ ] Concept of Partitioning 
* [ ] Database Security
	* [ ] SQL Injection
	* [ ] Database User Levels
* [ ] Database Error Handling
	* [ ] Reading Database Exception
	* [ ] Finding Problem
	* [ ] Fixing Problem
* [ ] ORM
	* [ ] ORM Definition
	* [ ] Relationship
	* [ ] Single Table Inheritance
	* [ ] Inheritance
	* [ ] Setup
	* [ ] Entity Definition
	* [ ] Concept of Entity Builder
* [ ] Use of Database Tools
	* [ ] phpMyAdmin
	* [ ] Management Studio
	* [ ] MySQL Workbench
* [ ] Database Sharding
	* [ ] Master – Slave
	* [ ] Master Master
	* [ ] Two Way Sync

## 6. Advanced MVC Concepts 
* [ ] Razor Pages
	* [ ] Models
	* [ ] Scaffolding 
	* [ ] Updating Pages
	* [ ] Validation
* [ ] MVC
	* [ ] Partial Views
	* [ ] Unit Test concept
	* [ ] Layout
	* [ ] Tag Helper
		* [ ] Cache
		* [ ] Distributed Cache
		* [ ] Form Action
		* [ ] Environment
		* [ ] Partial
		* [ ] Script
		* [ ] Validation Summary
	* [ ] View Components
	* [ ] View Compilation Process
	* [ ] App Model
	* [ ] Filters
	* [ ] Areas
	* [ ] Uploading Files
	* [ ] App Parts
	* [ ] Asp. Net Code Generator

* [ ] Routes
* [ ] Name
	* [ ] Parameters
	* [ ] Specifying routes for actions
	* [ ] Route URL generation 
		* [ ] In controllers [Redirect]
		* [ ] In views [href and actions]
	* [ ] Getting data from request
		* [ ] From GET query
		* [ ] From POST
		* [ ] From Header
		* [ ] From Session
		* [ ] From body
		* [ ] Getting Uploaded file
		* [ ] Model Binding 
			* [ ] How it works
			* [ ] Binding data submitted from form
			* [ ] Binding data submitted using JS
				* [ ] $.ajax
				* [ ] fetch
			* [ ]	Binding uploaded file
			* [ ]	Binding data with dynamic index name[0], name[1] etc
			* [ ]	Model Validation
			* [ ]	Adding custom error message to model
	* [ ]	Returning data to client
		* [ ]	JSON
		* [ ]	Redirect header
		* [ ]	As HTML
			* [ ]	Views for actions
			* [ ]	Returning another view from an action
			* [ ]	View Component
			* [ ] Sending data from controller to view
			* [ ] Viewbag, Viewdata, Tempdata, Viewmodel
				* [ ] Why viewmodel should be preferred for sending data
				* [ ] In what circumstances Viewbag, Viewdata etc are useful
			* [ ] Asp.Net core tag helpers
				* [ ] Anchor tag helper
					* [ ] asp-controller
					* [ ] asp-action
					* [ ] asp-area
					* [ ] asp-route
					* [ ] asp-route-value
				* [ ] Select tag helper
				* [ ] input tag helper
					* [ ] Input for a property of a model
					* [ ] label for a property of a model
					* [ ] validation message for a property of a model
				* [ ] Partial tag helper
		* [ ] Displaying data in view [PHP/Razor syntax]
			* [ ] Displaying variable passed from controller
			* [ ] writing conditionals in views
			* [ ] Writing loops in views
		* [ ] Pagination
* [ ] Async / Await
* [ ] Null conditional operation (?. and ?[])
* [ ] Json response formats and standard
* [ ] Rest API concepts
* [ ] Middlewares
	* [ ] What
	* [ ] Why
	* [ ] How to use middlewares
	* [ ] How to create custom middlewares 
* [ ] Authentication
	* [ ] Session based
	* [ ] JWT 
	* [ ] What is the role of cookies?
	* [ ] How to perform authentication when cookie is not an option? Android app for example
	* [ ] How to enable public routes without authentication
	* [ ] Retrieving the logged in user in the application
	* [ ] Roles
	* [ ] Permissions provided to roles
	* [ ] Restrict access based on the permission given
	* [ ] [Authorize] [AllowAnonymous] attributes

### 7. ORM
* [ ] ORM 
	* [ ] What
	* [ ] Why
	* [ ] Tradeoffs
	* [ ] Why think in entities rather than database tables
	* [ ] Transaction
		* [ ] Start'
		* [ ] Rollback
		* [ ] Commit
	* [ ] Sending queries to the database [Flushing]
	* [ ] Relationships between entities
		* [ ] One to one
		* [ ] One to many
		* [ ] Many to many
	* [ ] Entity inheritance
		* [ ] Single table inheritance
		* [ ] Class table inheritance
	* [ ] Mapping entities to database
	* [ ] Persisting (Saving) entities
	* [ ] Updating entities
	* [ ] Retrieving entities
		* [ ] By id
		* [ ] Using conditionals
	* [ ] What conditionals can the ORM convert to query and what it performs in memory.
		* [ ] Cascade in entity relations
		* [ ] Implementing Aggregate root concept of DDD using entities
	* [ ] Lazy loading , Eager loading
		* [ ] Advantages and drawbacks of both methods
		* [ ] Eagerly loading some lazy loaded properties in specific cases
	* [ ] Life cycle events
		* [ ] Can we have some method like IsValid on entities that will be called just before the entity is saved?
	* [ ] Dealing with concurrency

## 8. Basic CSS concepts
* [ ] Units [px,em,rem,pt, in etc]
* [ ] Text coloring
* [ ] Background image/coloring
* [ ] Box model
* [ ] Display properties [Block, inline-block, inline table ,tale-cell,table-row, none]
* [ ] Float
* [ ] Clearing float
* [ ] Margin, padding, border ,outline
* [ ] Css specificity
* [ ] Font
* [ ] Media query
## 9. Basic JS Concepts
* [ ] const vs let vs var
* [ ] Object literal
* [ ] Array literal
* [ ] for ..or and for .. in
* [ ] JSON.parse and JSON.stringify
* [ ] Creating FormData
	* [ ] From form
	* [ ] Without form
* [ ] Making request 
	* [ ] fetch
	* [ ] $.ajax
	* [ ] Handling response of request
	* [ ] Handling error 
* [ ] Retrieving elements from dom
	* [ ] querySelector
	* [ ] querySelectorAll
* [ ] map,filter,reduce, any methods
* [ ] adding event listeners to elements
* [ ] Removing event listeners from element
* [ ] Retrieving element data
	* [ ] Value
	* [ ] textContent
	* [ ] innerHTML
	* [ ] class
	* [ ] style
	* [ ] dataset values
	* [ ] id
	* [ ] attribute values
	* [ ] childrens
	* [ ] parent
	* [ ] closest parent matching a selector
* [ ] Modifying element
	* [ ] changing value
	* [ ] changing textContent
	* [ ] removing class
	* [ ] adding class
	* [ ] changing style
	* [ ] adding/updating dataset data
	* [ ] removing element
	* [ ] removing child elements
	* [ ] dispatching event on the element
	* [ ] cloning element
* [ ] DocFragment
* [ ] Creating element
	* [ ] Adding element to DOM
	* [ ] Accessing localstorage
	* [ ] Preventing default action of event. Preventing form submit, for example
	* [ ] Prototypal inheritance of JS


### 10. Advanced Concepts
#### 10.1 Authentication and Authorization ( ACL )
* https://docs.microsoft.com/en-us/aspnet/core/security/authentication/?view=aspnetcore-3.1

* [ ] Authentication
	* [ ] Cookie
	* [ ] JWT
	* [ ] OAUTH
* [ ] Authorization
	* [ ] RBAC ( Role Based Access Control )
	* [ ] AllowAnonymous Attribute
	* [ ] Authorize Attribute
	* [ ] Role Inheritance
	* [ ] Resource, Permission, Role Concept
	* [ ] Blacklist Approach
	* [ ] Whitelist Approach
#### 10.2 Advanced Clean Code Concepts
* [ ] Objects and Data Structures
* [ ] Data Abstraction / Encapsulation
* [ ] Data / Object Anti-Symmerty
* [ ] Law of Demeter
* [ ] Data Transfer Objects ( DTO )
* [ ] Error Handling
* [ ] Creating Exception class as per need
* [ ] Normal Flow Concept
* [ ] Don’t return Null
* [ ] Don’t pass null
* [ ] Boundaries 
* [ ] Learning Boundary Concepts
* [ ] Unit / Integration Tests
* [ ] Writing Clean Tests
* [ ] Single Concept per test
* [ ] Classes and Class Organization
* [ ] Small Class
* [ ] Single Responsibility Principle ( SRP )
* [ ] Cohesion
* [ ] Isolating from Change
* [ ] Systems
	* [ ] Separation of Main
	* [ ] Factories
	* [ ] Dependency Injection
	* [ ] Optimizing Decision Making
	* [ ] Other concepts as in the book
* [ ] Emergence
	* [ ] Running All the tests
	* [ ] Refactoring
	* [ ] No Duplication
	* [ ] Minimal Classes and Methods
* [ ] Concurrency 
	* [ ] Why ?
	* [ ] Concurrency Defense
	* [ ] Thread-safety in collections
	* [ ] Producers & Consumers
	* [ ] Writers and Readers
	* [ ] Dependency between syncronized Methods
	* [ ] Thread-safe writing code
* [ ] Continuous Refinement
	* [ ] Incremental cleanup

#### 10.3 Advanced DDD
https://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf

* [ ] Modelling
* [ ] Bounded Context
* [ ] Ubiquitous Language
* [ ] Continuous Integration ( CI )
* [ ] Continuous Delivery ( CD ) 
* [ ] Model-Driven Design
* [ ] Refactoring
* [ ] Building Blocks
	* [ ] Layered Architecture 
	* [ ] Entity
	* [ ] Value Objects
	* [ ] Domain Events
	* [ ] Services
	* [ ] Modules
	* [ ] Aggregates
	* [ ] Repositories
	* [ ] Factories
* [ ] Supple Design
	* [ ] Intention revealing Interfaces
	* [ ] Assertions
	* [ ] Standalone Classes
	* [ ] Closure of Operations
	* [ ] Declarative Design
	* [ ] Conceptual Contours
* [ ] Context Mapping
	* [ ] Context map
	* [ ] Partnership
	* [ ] Shared Kernel
	* [ ] Customer / Supplier Management
	* [ ] Conformist
	* [ ] Anti-corruption Layer
	* [ ] Open-host service
	* [ ] Published Language
	* [ ] Separate Ways
	* [ ] Big Ball of Mud
* [ ] Distillation of Strategic Design
	* [ ] Core Domains
	* [ ] Generic Sub-domains
	* [ ] Domain Vision Statement
	* [ ] Highlighted Core
	* [ ] Cohesive Mechanisms
	* [ ] Segregated Core
	* [ ] Abstract Core 
* [ ] Large-Scale Structure
	* [ ] Evolving Order
	* [ ] System Metaphor
	* [ ] Responsibility Layer
	* [ ] Knowledge Level
	* [ ] Pluggable Component ( Plugin Architecture )
#### 10.4 Rest API
* [ ] HTTP Methods
	* [ ] GET
	* [ ] POST
	* [ ] PUT
	* [ ] PATCH
	* [ ] OPTIONS
	* [ ] HEAD
	* [ ] DELETE
	* [ ] TRACE
* [ ] Learning JSON Standard :  https://code.crystalhost.net/crystal-main-group/standards/blob/master/Json%20Standard.md

#### 10.5 Model Binding
* https://docs.microsoft.com/en-us/aspnet/core/mvc/models/validation?view=aspnetcore-3.1

* [ ] Model Binding
* [ ] Model Validation
* [ ] Model Validation Attributes
* [ ] URL Rewriting
* [ ] Writing Middleware
#### 10.6 Cron Job ( Background Task )
* https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services?view=aspnetcore-3.1&tabs=visual-studio

* [ ] Base Class
* [ ] Timing
* [ ] Queuing
#### 10.6 Real time Apps with SignalR
* https://docs.microsoft.com/en-us/aspnet/core/signalr/introduction?view=aspnetcore-3.1

* [ ] Hub
* [ ] SignalR Server
* [ ] Socket Concept
* [ ] SignalR Client
	* [ ] JavaScript Client
	* [ ] .Net Framework Client
	* [ ] .Net Core Client

#### 10.7 Making HTTP Calls
* https://docs.microsoft.com/en-us/aspnet/core/fundamentals/http-requests?view=aspnetcore-3.1

#### 10.8 Advanced Patterns
* [ ] Domain Logic
* [ ] Transaction Script
* [ ] Domain Model
* [ ] Table Module
* [ ] Service Layer
* [ ] Data Source
	* [ ] Table Gateway
	* [ ] Row Data Gateway
	* [ ] Active Record
	* [ ] Data Mapper
* [ ] Object Relational Behaviour
	* [ ] Unit of Work
	* [ ] Identity Map
	* [ ] Lazy Loading
* [ ] Object Relation Structure 
	* [ ] Identity Field
	* [ ] Foreign Key Mapping
	* [ ] Association Table Mapping
	* [ ] Dependent Mapping
	* [ ] Embedded Value
	* [ ] Serialized LOB
	* [ ] Single Table Inheritance
	* [ ] Class Table Inheritance
	* [ ] Concrete Table
	* [ ] Inheritance Mappers
* [ ] Object Relational MetaData
	* [ ] Medata Mapping
	* [ ] Query Object
	* [ ] Repository
* [ ] Web Presentation
	* [ ] MVC
	* [ ] Page Controller
	* [ ] Front Controller
	* [ ] Template View
	* [ ] Transform View
	* [ ] Two-Step View
	* [ ] Application Controller
* [ ] Distribution 
	* [ ] Remote Facade
	* [ ] Data Transfer Object ( DTO )
* [ ] Offline Concurrency 
	* [ ] Optimistic Offline Lock
	* [ ] Pessimistic Offline Lock
	* [ ] Coarse Grained Lock
	* [ ] Implicit Lock
* [ ] Session State
	* [ ] Client Session
	* [ ] Server Session
	* [ ] Database Session
* [ ] Base Patterns
	* [ ] Gateway
	* [ ] Mapper
	* [ ] Layer SuperType
	* [ ] Separated Interface
	* [ ] Registry
	* [ ] Value Object
	* [ ] Money
	* [ ] Special Case
	* [ ] Plugin

	* [ ] Service Stub
	* [ ] Record Set
* [ ] Singleton Pattern
* [ ] Factory
* [ ] Decorator
* [ ] Strategy 
* [ ] Adapter
* [ ] Command
* [ ] Iterator
* [ ] Proxy
* [ ] Composite
* [ ] Prototype
* [ ] Abstract
* [ ] Bride
* [ ] Template

## 11. Clean Code
* [ ] Clean Coders 01 - Clean Code
* [ ] Clean Coders 02 - Names
* [ ] Clean Coders 03 - Functions
* [ ] Clean Coders 04 - Function Structure
* [ ] Clean Coders 05 - Form
* [ ] Clean Coders 06 - Test Driven Development
* [ ] Clean Coders 07 - Architecture Use Cases And High Level Design
* [ ] Clean Coders 08 - Foundations of the SOLID Principles
* [ ] Clean Coders 09 - Single Responsibility Principle
* [ ] Clean Coders 10 - Open Closed Principle
* [ ] Clean Coders 11 - Liskov Substitution Principle
* [ ] Clean Coders 12 - The Interface Segregation Principle
* [ ] Clean Coders 13 - The Dependency Inversion Principle
* [ ] Clean Coders 14 - Solid Case Study
* [ ] Clean Coders 15 - Solid Components
* [ ] Clean Coders 16 - Component Cohesion
* [ ] Clean Coders 17 - Component Coupling
* [ ] Clean Coders 18 - Component Case Study
* [ ] Clean Coders 19 - Advanced TDD
* [ ] Clean Coders 20 - Clean Tests
* [ ] Clean Coders 21 - Test Design
* [ ] Clean Coders 22 - Test Process
* [ ] Clean Coders 23 - Mocking
* [ ] Clean Coders 24 - Transformation Priority Premise
* [ ] Clean Coders 25 - Design Patterns
* [ ] Clean Coders 26 - Factories
* [ ] Clean Coders 27 - Strategy and Template Method Patterns
* [ ] Clean Coders 28 - Finite State Machines and The State Pattern
* [ ] Clean Coders 29 - SMC Parser
* [ ] Clean Coders 30 - SMC Generator
* [ ] Clean Coders 31 - The Observer Pattern
* [ ] Clean Coders 32 - Pile O'Patterns
* [ ] Clean Coders 33 - Pattern Roundup
* [ ] Clean Coders 34 - Pattern Apocalypse
* [ ] Clean Coders 35 - Behavior Driven Development
* [ ] Clean Coders 36 - Behavior Driven Development Design
* [ ] Clean Coders 37 - Elaborating the Requirements
* [ ] Clean Coders 38 - The Clean Coder
* [ ] Clean Coders 39 - Defects
* [ ] Clean Coders 40 - Proof
* [ ] Clean Coders 41 - Small Releases
* [ ] Clean Coders 42 - Life, The Universe, and Everything
* [ ] Clean Coders 43 - Productivity
* [ ] Clean Coders 44 - Estimates
* [ ] Clean Coders 45 - The Programmer's Oath
