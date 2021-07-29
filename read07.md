# Tables 
 
  ![](https://alvinalexander.com/sites/default/files/2018-05/javascript-console-output-logging-debugging.jpg)
  

## There are several types of information that need to be displayed in a grid or table. For example:
- sports results, 
- stock reports,
-  train timetables.
** When representing information in a table, you need to think in terms of a grid made up of rows and columns (a bit like a spreadsheet). In this chapter you will learn how to:
- Use the four key elements for creating tables
- Represent complex data using tables
-  Add captions to tables

### What's a Table?
- A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

### Basic Table Structure
#### table
- The table element is used to create a table. The contents of the table are written out row by row.
  
 #### tr
- You indicate the start of each row using the opening tr tag. (The tr stands for table row.)
- It is followed by one or more td elements (one for each cell in that row).
- At the end of the row you use a closing tr tag.
  
  
  
 #### td
Each cell of a table is represented using a <td> element. (The td stands for table data.)
  
  
 # WHAT IS A FUNCTION?
  - Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).
  
  ## A BASIC FUNCTION
  ![](https://th.bing.com/th/id/R.fe5b61d7084e2a7cbc0c412117db9c6e?rik=zwEBBsw2Cisykg&pid=ImgRaw) 
  
##   FUNCTION DECLARATION
A function declaration creates a function that you can ca ll later in your code. It is the type of function you have seen so far in this book.
  ## FUNCTION EXPRESSION
  If you put a function where the interpreter would expect to see an expression, then it is treated as an expression, and it is known as a function expression.
In function expressions, the name is usually omitted. A function with no name is called an anonymous function. Below, the function is stored in a variable
called area. It can be called like any function created with a function declaration.

  # CREATING OBJECTS USING CONSTRUCTOR SYNTAX
 
 - On the right, an empty object called hote 1 is created using the constructor function.
 - Once it has been created, three properties and a method are then assigned to the object.
 
 var hotel = new Object();
 
hotel.name= 'Park';
 
hotel.rooms = 120;
 
hotel .booked = 77;
 
hotel .checkAvailability = function()
 
return this . rooms - this.booked;
 
} ;
 
#### JAVASCRIPT
 
var elName = document.getElementByid('hotelName');
 
elName.textContent = hotel . name;
 
var elRooms = document .getElementByid('rooms');
 
elRooms .textContent = hotel .checkAvailability(};
 
 
 
 - ( If the object already had any of these properties, this would overwrite the values in those properties.)
 
 - To access a property of this object, you can use dot notation, just as you can with any object.

 * For example, to get the hotel's name you could use: hotel .name
 
 Similarly, to use the method, you can use the object name followed by the method name:
hotel.checkAvailability()
