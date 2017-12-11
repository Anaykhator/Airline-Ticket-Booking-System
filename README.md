#			Airline Ticket Booking System

## How to CLONE this in your desktop
* Open Terminal
Write  
`cd Desktop`   
`git clone https://github.com/piyush97/BillingSystem`
### Custom Header File

Reason: We used a custom header file to make things look in a simple in the main file and for data abstraction.

#### #include  "Function.h"

### Variables

`struct node 	//Structure to store bookings done.`

`char src[Size];	 //source of the flight`

`char dest[Size];	// destination of the flight`

 `char time[5];	//block time of the flight`

`int fare; 	//fare of the particular flight`

`struct node* link; //pointer reference used in Linked List`


### Functions

`Struct node addNode(struct node param1. Struct node param2);`
`// function of return node type which returns the linked list it adds the nodes in the program`

`void putData(char *file,sn s) `
`// function to put data in a TEXT file `

`struct node getData(char *file,struct node s)//function to retrieve data from file`

`void displayList(struct node s)//function to display data directly from the Text File`

`struct node delete_nth_node(int n, struct node s) //to delete a particular flight`

`int getSize(sn s)//needed to delete a particular flight, used in the above function`

`void addFlight()//Administrator function to add new flight in the database/file`

`void deleteFlight() //to delete a particular flight using the delete nth node function`

`struct node search(char *s, char *d) // to search for a particular flight`

`void displayBookings()// to display the bookings to the administrator`

`void newBooking()//to add new booking `

`void deleteBooking() //to delete a particular booking`




