# Function Types

- Used to pass functions as parameters to other functions or return functions
	- Not to be confused with function declarations (covered in the next sedction)
- Function types come in two flavors
	- Internal (default)
		- Can only be called from within the current contract
	- External
		- Can be called with a transaction from any account / contract
- Function types are defined with the following components:
	- function (<parameter types>)
	- internal | external
	- pure | constant | view | payable
	- returns(<return types>)

##Reference Types

- Arrays
	- Defined as T[k] for fixed size of length k
	- T[] for dynamic 
	- Can be allocated to storage or memory
		- Storage arrays can be any data type
		- Memory arrays can be anything but a mapping
	- Declaring the variable public will create a getter function that requires the index of the desired value as a parameter.
