# Understanding The Problem Domain Is The Hardest Part Of Programming
## What is the hardest thing about writing code?

- There are many common answers to this question:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

![](https://scholarsark.com/wp-content/uploads/2021/07/11704-master-class-creative-problem-solving-decision-making-806x440.jpg)

## A familiar problem
- In a good portion of my Pluralsight courses I show the viewer how to build the “Protein Tracker” application.
- I am often asked why I keep demonstrating how to build the same simple application over and over again in each of my courses.

## The answer is “familiarity.”

![](https://th.bing.com/th/id/R.19d062071e368d04c80be709a7a872cc?rik=KYVuRrniBjb60w&pid=ImgRaw)

- "When I first started using the Protein Tracker example in my Android course, I was just looking for a simple example of an application that could be easily understood and implemented."
- The idea behind the Protein Tracker application is that it allows a user to set a goal for the amount of protein to consume in a day.  The user can add protein amounts which are added to a total protein count that is tracked for that user.

- Very simple functionality, easily explainable, but most importantly, easily understood.

### What I found with this simple application was that because it was so easy to understand, the focus was taken off of the problem domain and put instead on the technology.

### Not only this, but as I reused this same exact application for teaching a variety of different technologies, it served as a reference problem domain that didn’t have to be re-learned, and provided a way to compare and contrast different technologies—I was getting this teaching mechanism for free if a viewer had already watched one of my other Pluralsight courses.



- By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.

###### So what am I trying to say here?

Simply that by taking away the problem domain, or making it so trivial that it is easily understood, I am able to make both teaching and learning easier.

Why problem domains are hard
Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?  How about one like this one, that has a very similar pattern repeated on it and is double-sided?

![](https://th.bing.com/th/id/R.7490bbee2324e24b5bc1e77f03691c37?rik=G8WAa0wSE248Cg&pid=ImgRaw)






# WHAT IS AN OBJECT?
![](https://i.ytimg.com/vi/HEv1SnLhCzs/maxresdefault.jpg)

## Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
If a variable is part of an object, it is called a property. Properties te ll us about the object, such as the name of a hotel or the number of rooms it has.
Each individual hotel might have a different name and a different number of rooms.

### IN AN OBJECT: UNCTIONS BECOME KNOWN AS METHODS
If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.


#### This object represents a hotel. 
It has five properties and one method. The object is in curly braces. It is stored in a variable called hotel .

- Like variables and named functions, properties and methods have a name and a va lue. In an object, that name is called a key.
- An object cannot have two keys with the same name. This is because keys are used to access their corresponding values.
- The value of a property can be a st ring, number, Boolean, array, or even another object. The va lue of a method is always a function.



# CREATING· OBJECTS USING LITERAL NOTATION
- This example starts by creating an object using litera l notation.
- This object is called hotel which represents a hotel called Quay with 40 rooms (25 of which have been booked).
- Next, the content of the page is updated with data from this object. It shows the name of the hotel by accessing the object's name property and the number of vacant rooms using the checkAvail ability() method.
- To access a property of this object, the object name is followed by a dot (the period symbol) and the name of the property that you want.
- Similarly, to use the method, you can use the object name followed by the method name. hotel .checkAvailability()
### example 

var hotel = {

name: 'Quay',

rooms : 40,

booked: 25,

checkAvailability: function() {

return this.rooms - this.booked;

}

} ;

### JAVASCRIPT
var elName = document .getElementByld('hotelName');

elName.textContent =hotel .name;

var elRooms = document.getElementByid{'rooms');

elRooms .textContent = hotel .checkAvailability();

# Document Object Model
 - The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
 - The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:
 ### 1- MAKING A MODEL OF THE HTML PAGE
 When the browser loads a web page, it creates a model of the page in memory. The DOM specifies the way in which the browser should structure this model using a DOM tree.
The DOM is called an object model because the model (the DOM tree) is
made of objects. Each object represents a different part of the page loaded in the browser window.
### 2- ACCESSING AND CHANGING THE HTML PAGE
The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.
You will hear people call the DOM an Application Programming Interface (API). User interfaces let humans interact with programs; APls let programs (and scripts)
talk to each other. The DOM states what your script can "ask the browser about the current page, and how to tell the browser to update what is being shown to the user.


