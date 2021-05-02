### ch6: Tables
- A table represents information in a grid format.
- tags used to create table:
  - <table>
  - <tr> :(The tr stands for table row.) 
  - <td> :(The td stands for table data.)
  - <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) , <th></th> <th scope="col">colunm heading</th>
  - <thead>The headings of the table should sit inside the <thead> element. 
  - <tbody>The body should sit inside the <tbody> element. 
  - <tfoot>The footer belongs inside the <tfoot> element.
  - <table width="400" cellpadding="10" cellspacing="5">
  - <table border="2" bgcolor="#efefef">

  ### 
  -  WAYS TO CREATE OBJECTS:
    1- LITERAL NOTATION : ex
    var hotel = {} 
hotel .name= 'Quay'; 
hotel .rooms = 40; 
hotel.booked = 25; 
hotel.checkAvailabil ity =function() 
return this.rooms - this .booked; 
} ;

  2- OBJECT CONSTRUCTOR NOTATION : ex
  var hotel = new Object(); 
hotel.name = 'Quay'; 
hotel .rooms = 40; 
hotel . booked= 25; 
hotel.checkAvailability =function() 
return this .rooms - this.booked; 
} ;

* typeof Arrays are objects, hold set of value pairs, but the key for each value is its index number.

* JavaScript also has several built-in objects such as 
String, Number, Math, and Date. Their properties and 
methods offer functionality that help you write scripts. 
 