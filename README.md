# What does it mean for a method to “return” a value?

It is what an invoked method will equal to. It will stop the execution of a function.

# What is the difference between a procedure, a function, and a method?

A procedure is a set of statements that can be repeated on demand. A function takes inputs and transforms them into outputs. A method is a procedure that is stored within an object.

# What’s the difference between a hash and an array?

An array stores individual values separated by commas while hashes store key value pairs. Elements can be accessed by their index in arrays, while values can be accessed by their keys in hashes.

# What’s the difference between a hash and an object?

Hashes are simply key-value pairs. Objects however are an instance of class and therefore collections of state and behavior.

# When should you use map? Select? Reduce? Find?

Map is used to iterate through elements and return an element you want for each element. Select is when only a handful of defined elements should be returned within an array of different length. Reduce is designed to return one value transformed using an accumulator and given value, and find is meant to find one non transformed value which meets a condition.

# What is the difference between a class and an instance of a class?

A class is a blueprint from which to create objects. An instance of class is an object of the data type which exists in memory. Instances are concrete implementations of a class.

# What’s the difference between an instance method and a class method?

A class method is sort of like a blueprint or a boiler plate. An instance is an object, so pretty much the actual object which gets assembled from the blueprint.

# What is a gem? Gemfile? Gemfile.lock?

Gems in Ruby are packages of code that can be downloaded and installed. Required gems add additional functionality to programs. Gemfiles are lists of gems, their versions, and where they are required. A Gemfile.lock is a list of gems, their exact versions and which environments require them.

# What is a one to many and a many to many relationship?

A one to many relationship is a relationship where only one set of data relates to another, such as a person and their possessions. A many to many relationship is one where each set of data can have multiple instances, like restaurants and customers.

# How does a database relate two tables?

A column in a dependent table will store an independent table’s primary key as a foreign key. This means the database can only store values where there is a match between foreign and primary key values. If table A has primary key values 1, 3, and 5, and table B references the former table, then 1, 3 and 5 will be the only legal values for relating the two.

# What does “single source of truth” mean?

Single sources of truth are when objects seeking to find more out about their relations are only consulting one locale for their information.

# What is the purpose of the environment.rb file?

The environment.rb contains different run-levels. A run-level is what will be taking place under the hood essentially, and will load libraries, classes and their dependencies on run time.

# What does an ORM do?

An object-relational mapper takes object relationships, which are has-many/belongs-to relationships and translates them to foreign key relationships, and also the other way around. So essentially these are either being mapped to rows & columns in a database or being imported back into an IDE. Object data is naturally nested, and relational data is naturally flat.

# What is an API?

An application programming interface defines a contract where a certain output or state change will be given if a particular input is provided. This also refers to HTTP web APIs which are objects and arrays of stored and accessible data.

# What is semantic HTML?

This refers to using and organizing HTML elements by their meaning and purpose rather by their intended visual appearance.

# What is the DOM?

The document object model is the browser’s representation of an HTML document and its styles. It provides a way to programmatically access and manipulate the documents. It is internally represented as a tree. It provides an eventing interface for its nodes as well.

# Describe the HTTP request response cycle.

Client requests are issued by the user. It goes to the server, which fulfills this with an HTTP response. Requests are expected to have a response. If a response isn’t given within a timeframe it is considered a failure. If it is successful it is sent back to the client.

# What’s the difference between the web and the internet?

The internet is a global network of billions of servers and other hardware devices. The WWW is a common point of connectivity for information sharing which is facilitated by a global network of computers.

# What is a computer virus?

A computer virus is a set of malicious code or programs written to alter the way that a computer operates. It operates by inserting or attaching itself to a legitimate program or document that supports macros in order to execute its code.

# What is validation, where can it occur and what purpose does it serve?

Validation ensures the integrity of supplied data. It can exist on the web in the form of “form validation” which makes sure a user enters their data correctly, and on the server via strong params and model validations in rails.

# What is an event?

An event fires when a user-initiated action occurs on a DOM node. They can also be systems initiated. Generally code is executed to mutate something about the current page or backend when these go off.

# What is event bubbling?

Bubbling is the process of triggering embedded elements which then bubble up to the container elements within a hierarchy.

# What is referential transparency?

These are properties of parts of computer programs. An expression obtains this label if they can be replaced with its corresponding value without altering the program’s behavior.

# What are the four pillars of OOP?

Abstraction (the process of hiding implementation details and showing only the necessary parts), Encapsulation (the process of putting data and functions in a single entity), Inheritance (the process of adopting the features of parent class) and Polymorphism (having the ability to override and overload objects).

# What are some tenets of functional programming?

Testability, purity, immutability, pure functions, referential transparency, and control flow.

# What’s the difference between authentication and authorization?

In authentication, the identity of users are checked for providing the access to the system. In authorization, the user’s authority is checked for accessing the resources. The first is who you are, the second is what you can do.

# How do you avoid storing plain text passwords?

Encryption. Hashing. CHAP is a popular schema.

# What is serialization?

This is the process of translating a data structure or object state into a format that can be stored or transmitted, such as turning a data structure into a string.

# Describe the Model View Control architecture pattern.

This is an architecture pattern that divides a program into three parts. The model corresponds to all the data related logic that a user works with. The view is the UI aspect. The controller is the interface between the model and the view which processes requests, manipulates them using the model, and controls output using the view.

# What is Big O?

Big O calculates the size and efficiency of code. There is O(1), O(n) and O(n2).

# What is a closure?

A closure is the combination of a function bundled together with references to its surrounding state. It gives access to an outer function’s scope from an inner function.

# What is CORS?

Cross origin resource sharing allows a server to indicate any other origin which a server should allow a browser to permit the loading of resources.

# What’s the semantic difference between put and patch?

“PUT” uses the request URI to supply a modified version of the requested resource which replaces the original. “PATCH” supplies a set of instructions to modify the resource.

# What is DRY?

“Don’t Repeat Yourself”. Common ways of implementing this consist of writing helper functions, destructuring, etc.

# What is “class inheritance”?

It is a way for one class to extend another class so new functionality can be built on top of the existing class.

# What is prototypal inheritance?

This is when instances inherit directly from other objects. Instances are instantiated via factory functions. This is simpler than class inheritance as the object is already built out.

# What is “hoisting”?

This is JavaScript’s default behavior of moving all declarations to the top of the current scope.

# What is a “promise”?

Promises support two properties, state and result. When the promise is working, the result is undefined. When it is fulfilled, the result returns a value.

# What is a callback?

A callback is a function passed as an argument to another function so a function can call another function. It can run after another function has finished. These are called “high order functions”.

# What are “pure components”?

These are the simplest and fastest components which can be written. They can replace any component which only has a render(). They enhance the simplicity of code and performance of the app.

# What is “Redux”?

Redux is a library with predictable state container. It is used for state management. It has consistent behavior across different environments. Redux has three primary principles: A single source of truth, meaning state will be stored in an object, read only state, meaning the only way to modify state is by triggering an action, and changes made via pure functions. State exists outside of the component hierarchy, so any component can access the “store” without going up the hierarchy. The state is managed via dispatch(), and this is the only way to change it.
