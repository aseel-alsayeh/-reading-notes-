## Lists and Keys
- What does .map() return?
return a new array after modification, But without affect the original array with these modifications.

- If I want to loop through an array and display each value in JSX, how do I do that in React?
make an arrow/map function and return a html value in each time, after that we render it to the DOM. see the example :

ReactDOM.render(
  <ul>{listItems}</ul>,
  document.getElementById('root')
);

- Each list item needs a unique ____.
key
- What is the purpose of a key?
keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.