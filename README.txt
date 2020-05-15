The module cover the following:

1. Render Content Conditionally: 
- See in App.js
- Taking the use of 'state' to add elements to a null variable 'persons' 
- Note the function togglePerson > toggle the targeted state for rendering, 
taking the fact that any code inside the render() function will be re-run 
continouslly > this is why the 'persons' variable can be re-assigned to 
null and add elements Conditionally

- See condition.pdf for the recommend way for coding condition in 
React

2. Outputing Lists: 

- Ouputing list: using map to get all the elements for outputing the 
list of elements. See how we use the map() function in the code for more
details

- Important to Notice: avoiding mutation and unpredictable data in application
 see in deletePersonHandler()

In Javascript, the object are reference so 
    persons and this.state.persons are actually poiting to a same 
    reference, calling slice() or using spread operator to copy this.state 
    and assign it to a new object so we have an 
    independent object to work with, this will avoid unpredictable app

3. Updating and Deleting the targeted property in state: 
- Updating: See the use of nameChangedHandler() function
- Deleting: See the use of deletePersonHandler() function

Review: Spread Operator, splice() and find() method from Javascript
