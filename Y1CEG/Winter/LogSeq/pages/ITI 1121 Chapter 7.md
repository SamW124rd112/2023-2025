## [[Exceptions]]
	- ### Error Processing
		- Error can occur at compile-time or runtime
			- Syntax erros are dected at compile time
		- Although type checking is an ecient way of detecting errors as soon as possible,**there are certain verifications that can only be made at execution time**
		- Runtime errors are handled by a mechanism called Exception
	- ### Sources of Error
		- Logic of program
		- External events
			- Running out of memory
			- Write error
	- ### Preconditions
		- **Preconditions** are the ensemble of of conditions that **parameters** and the **state** of the object, must verify so tha tthe computation can be successful
	- ### Exceptions
		- Exceptions are objects
			- An error situation is modelled using an object of class `Throwable`, which encapsulates the error messgae
				- The class `Throwable` declares methods `String getMessage()` and `void printStackTrace()`
	- ### Transfer of Control
		- When an **Exception** is thrown:
		  id:: 66119276-cf8f-4b8d-badb-167ae1954e1c
			- The statement or expression *terminates abruptly*
			- If uncaught, the `Exception`will cause the whole stack of methods to uwind, each method call on the stack will terminate abruptly
			- If the exception is not caught the thread will terminate and print a stack trace
			- None of the statements or parts of the expression that follow are executed
			- Following an exception the next statement should be a `catch` or `finally` block
		- If an exception is thrown, the statements of the first `catch` block that matches
		  the exception are executed
	- ### Check and Unchecked Exceptions
		- A method that throws a "**checked exception**" must **declare** or **handle** the exception
		- **Unchecked** exceptions include `NullPointerException` and `IndexOutOfBoundsException`
			- Java does not require declaration of unchecked exceptions
		- **Checked** exceptions are used to **force** the caller to define a strategy for handling
		  these exceptions (declare or catch