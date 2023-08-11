# forEachMapFilter

The first difference between map() and forEach() is the returning value. 
The forEach() method returns undefined and map() returns a new array with the transformed elements. 

const myAwesomeArray = [1, 2, 3, 4, 5]
myAwesomeArray.forEach(x => x * x)
//>>>>>>>>>>>>>return value: undefined

myAwesomeArray.map(x => x * x)
//>>>>>>>>>>>>>return value: [1, 4, 9, 16, 25]

2. Ability to chain other methods
The second difference between these array methods is the fact that map() is chainable.
This means that you can attach reduce(), sort(), filter() and so on after performing a map() method on an array.

That's something you can't do with forEach() because, as you might guess, it returns undefined.


.forEach(), is used to execute the same code on every element in an array but does not change the array and it returns undefined.
.map() executes the same code on every element in an array and returns a new array with the updated elements.
.filter() checks every element in an array to see if it meets a certain criteria and returns a new array with the elements that return truthy for the criteria.

The filter() method is an ES6 method that provides a cleaner syntax to filter through an array. It returns new elements in a new array without altering the original array.
