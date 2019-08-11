---
title: Send Action Data to the Store
---
## Send Action Data to the Store

### Solution
<section id='solution'>
  
```javascript
const ADD_NOTE = ‘ADD_NOTE’;
const notesReducer = (state = ‘Initial State’, action) => {
switch(action.type) {
  // change code below this line
  case ADD_NOTE:
	return action.text
  // change code above this line
   default:
	return state;
}
};

const addNoteText = (note) => {
 // change code below this line
	const action = {type: ‘ADD_NOTE’,  text: note}
	return action
 // change code above this line
};
	
```
</section>
