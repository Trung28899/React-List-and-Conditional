1. Condition: 
- See condition.pdf for the recommend way for coding condition in 
React
- Ouputing list: using map to get all the elements for outputing the 
list of elements. See how we use the map() function in the code for more
details
- Important to Notice: see in deletePersonHandler()
In Javascript, the object are reference so 
    persons and this.state.persons are actually poiting to a same 
    reference, calling slice() or using spread operator to copy this.state 
    and assign it to a new object so we have an 
    independent object to work with, this will avoid unpredictable app

Review: Spread Operator, splice() and find() method from Javascript
