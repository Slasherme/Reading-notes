# OBJECT..what is it?
* its a something you do in javascript form.
* all things in the world are objects.
* its with a fuctions or even an array is an object.
* we can write it just like
```
var hotel = new Object();
hotel.name= 'Park';
hotel.rooms = 120;
hotel .booked = 77;
hotel .checkAvailability = function()
return this . rooms - this.booked;
} ;
JAVASCRIPT
var elName = document.getElementByid('hotelName');
elName.textContent = hotel . name;
var elRooms = document .getElementByid('rooms');
elRooms .textContent = hotel .checkAvailability(}; 
```
# DOM MODEL:
* The browser represents the page using a DOM tree.
* DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
* You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
* Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
* From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
* An element node can contain multiple text nodes and
child elements that are siblings of each other.
* In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
* Browsers offer tools for viewing the DOM tree .
••