# [[Introduction to Object Oriented Programming]] #[[ITI 1121]]
	- ## OOP and Software Design
		- #### What is object-oriented programming?
			- The design of a software system is an **abstract activity**, as you cannot see or touch the product being built
		- ### Abstraction
			- An **abstraction** allows us to ignore the details of a concept and to focus on its important characteristics
			- The term "**black-box**" is often used as an analogy for an abstraction
		- ### Procedural Abstraction
			- Structured programming
			- The main mean of abstraction is a **procedure**
				- Called a **routine** or **function**, but commonly knows as a **method** in Java
			- If a method is well designed, it is only dependent on formal parameters
		- ### Data Abstraction
			- **Records** and **Structures** were amongst the first forms of data abstraction
			- Allow to model the data and to handle the data as a unit
			- For example, consider modelling a coordinate or point in a 2-D plane
		- **Procedural Abstraction**
		                      +
		  **Data Abstraction**
		                      =
		  **Object-Oriented Programming**
			- The central concept of OOP is the object
			- An **object** consists of
				- Data abstractions (variables)
				- Procedural abstractions(methods)
			- A software system consists of collection of objects interacting together to solve a common task
		- ### Activities of Software Development
			- Requirements analysis; (defining the problem)
			  logseq.order-list-type:: number
			- Design; (how to break the system into subsystems and what are the interactions between these subsystems)
			  logseq.order-list-type:: number
			- Programming
			  logseq.order-list-type:: number
			- Quality assurance
			  logseq.order-list-type:: number
			- Project management
			  logseq.order-list-type:: number
		- ### Unified Modelling Language (UML)
			- A standard graphical language for modelling object-oriented software, developed in the mid-1990s
			- A class diagram is represented by a box divided in three parts:
				- Name of class
				- Attributes
				- Methods
		- ### Coupling
			- Two classes are coupled if the implementation of at least one of them depends on the other
				- One class has access to the variables of the other
			- Maintainability of a system is inversely proportional to the coupling, the number of dependencies
			- Examples
				- Factories, chess game, e-commerce store
			- Each object is **unique** and has a **state** (the current value of its properties) that may or may not be the same as other objects
		- ### Instance
			- #### Instance Variables
				- Class lists all variables that each object must have in order to model the given concept
				- When a variable is declared to be an instance variable, all the instances of the class will reserve space for the variable
				- Can be primitive or reference variables
			- #### Instance Method
				- A instance method, is a method that has access to the instance variables
		- ### Packages
			- A **package** is a organizational unit that allows to group classes
			- ^^A package contains one or more related classes^^
			- Packages may contain other packages (package has members)
		- ### Classes
			- Inside a class you have:
				- **Variables**, **methods**, and nested **classes**
				- Each belongs either to the **class** or the **instance**
				- Can be `public`, `package`, `protected` or`private`
					- Known as a **visible modifier**
				- Each can be `final` or not
					- A variable that can be assigned a value once and cannot further be altered or modified once assigned
					-
		- ### Constructor
			- A **constructor** is a block of statements that are executed when an object is created
			- A constructor has the same name as its class
			- Called in the context `new`when the object is created
			- A constructor has no return type
			- ^^Since the constructor is called when the object is first created, a constructor generally serves to initialize the instance variables^^
		- ### Interface
			- The public variables and methods are defining the **interface** of the class
			- To use an object or class, you need to know its interface
			- Changes to public methods and variables will affect other classes
		- ### Class as a specfication
			- ```
			  class Time{
			  	int hours;
			      int minutes;
			      int seconds;
			      
			      Time(int h, int m, int s){
			      	hours = h;
			          minutes = m;
			          seconds = s;
			      }
			  }
			  ```
			- All the objects specified by the class `Time` will have 3 variables: `hours`, `minutes` and `seconds` as well as the a constructor `Time()`
			- #### Image
			  background-color:: red
		- ### Creating Objects
			- An object is created with the use of keyword `new` to call a method that has special name as class
				- Known as constructor
			- We create an instance of said class
			- ```
			  Time a;
			  a = new Time(16,45,0);
			  ```
			- At runtime, `a = ... `puts the reference (address) of the object at the location designated by `a`, and now `a` points towards the object
	- ## Summary
		- The class specifies the characteristics that are common to an ensemble of objects
		- All variables and methods that we have defined belong to the instance, they were instance methods and variable
		- Each object(instance) has its own set of instance variables (sometimes called attributes) and each object reserves space for its own set of attributes