## [[ADT Queues]]
	- ### Definition
		- A **queue** is a linear abstract data type such that insertions are made at one end, called the **rear**, and removals are made the other end, called the **front**
		- Queues are sometimes called FIFOs: *first-in, first-out*
		- The two basic operations are:
			- **enqueue:** add an element to the rear end of the queue
			- **dequeue:** removes and returns the element at the front of the queue
	- ### Applications
		- Shared resource management
	- ### Implementations
		- Linked elements
		- Array-based
		- Queues are implemented with arrays or linked elements
		- **Modulo** arithmetic is used when incrementing the index so that the queue wraps around the array when it reaches the end
		- One must be careful to detech the case when the array gets full and avoid **overriding** any elements as well as distinguishing between the full and empty overriding queues
			- Several implementations are possible:
			- Using **sentinel values**, destroying the array,
			- Using a **boolean value** to indicate if the queue is full/empty or to maintain a
			  count of the number of elements in the queue
			- The operation `dequeue()` is sometimes called`serve()`  Q
				- Queues are often used in the context of client/server application
	- ### Asynchronous Processes
		- Applications such as **producer/consumer, client/server** or **sender/reciever** necessitate using a queue for asynchronous proccessing of data
		- **Asynchronous processing** means that the client and server are not synchroniezd, which would occur if the server is not ready or capable of recieving the data at that time or speed
			- The client insert data into a queue (enqueue)
			- The server removes data from the queue (dequeue) whenever it's ready for processing
		- Queue is also called a **buffer**