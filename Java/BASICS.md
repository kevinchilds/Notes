### What is a Variable?
A variable is where we can store data and refer back to later. 
```Java
int x = 4;
```
The syntax for a variable in java is [DATATYPE] [VARIABLE_NAME] = [VALUE];

### What is a Datatype?
A datatype defines what type of data is being stored into the variable. The value we assign the variable must correlate with datatype we defined. In the example above, the datatype is int which stores a whole number. So we must give a whole number value to this variable.

### What is a Primitive Datatype?
A primitive datatype is a datatype that is predefined by the programming language.

### What are the Primitive Datatypes of Java?
```Java
//true or false
boolean b = true;

//whole numbers
byte by = 1;
short s = 2;
int i = 3;
long l = 4;

//decimal numbers
float f = 1.1f;
double d = 1.1;

// one character
char c = 'g';
```
You can refer back to any of these values by referencing the variable name.

### What is an array?
If we want to store multiple values of one datatype, we use an array. An array is a grouping of like datatypes sequential in memory. Arrays are of fixed length so once you defined the size you cannot increase the size
```Java
int[] arr = {23,4,13,36}; //array size = 4;
int[] arr2 = new int[100]; //array size = 100. This line did not defined any values in the array. It just created 100 places in memory next to eachother to store int values later

//A position in the array is called the index. All arrays in java start at index 0 and then increments by 1.
System.out.println(arr[0]); //will print 23 to the console
System.out.println(arr[1]); //will print 4 to the console
System.out.println(arr[2]); //will print 13 to the console

//We can assign values to an array like this
arr[2] = 22; //this reassigned the value at index 2 (which was 13) to 22
```
