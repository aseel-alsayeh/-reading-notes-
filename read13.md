## Local Storage 

- the advantages of local storage/ the Needs that should be exsist to store:
     - a lot of storage space
     - on the client
     - that persists beyond a page refresh
     - and isn’t transmitted to the server
- HTML5 Storage is based on named key/value pairs.
- The named key is a string.
- he data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. BUT  the data is actually stored as a string. 


- We can write this code :  
 var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;   

- The localStorage property is read-only.

- Syntax for SAVING data to localStorage : localStorage.setItem("key", "value");

- Syntax for READING data from localStorage: var lastname = localStorage.getItem("key");

- Syntax for REMOVING data from localStorage:localStorage.removeItem("key");



source : http://diveinto.html5doctor.com/storage.html
