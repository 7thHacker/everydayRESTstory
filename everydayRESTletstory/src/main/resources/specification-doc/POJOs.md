Expense :

	package 		: com.everydayRESTletstory.expensesTracker.expense;
	class-type	: Interface
	super-class 	: Comparable<T> // so that all the sub-classes can be sorted
	data-member{	}
	member-method{}

PetrolExpense :

	package 		: com.everydayRESTletstory.expensesTracker.expense;	
	class-type	: Concrete Class
	super-class 	: Expense
	data members {
		01. id, for uniquely identification of object 
		02. airCheck, if air pressure of tyres were checked after petrol filling
      03. price, price of petrol at the time of filling
      04. amountINR, total amount of Rs. petrol were filled
      05. amountLtr, total amount of Ltr. petrol were filled
      06. odometerReading, the reading of odometer at the time of petrol filling
      07. timeMS, the time and date when petrol filled
      08. logTime, the time and date when expenses were logged to system
      09. brand, the name of the petrol brand
      10. pumpAddress, the full address of petrol bunk
      11. modeOfTransection, the mode of transaction like cash, cc, dc, net-banking, paytm ...etc.
      12. geoLocation, to hold the x and y co-ordinates of the Geo-location of the petrol bunk
	}
	member methods {
		01. getters & setters
		02. toString, Override toString method to print the value of data members instead of hashcode of instance.
		03. compareTo, implement the method from super class so that all the instance of this class can be in order (either ASC or DESC)
    }
