### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
--getElementById calls the specific id whoose name matches with called one.It only works with one element.
--getElementByClass returns an array of the class whoose name matches with the searched one.

 Many elements can contain class of same name but each id should be unique and can be declared only in one element

--QuerySelector returns only the first element of all the matching elements
--QueryselectorAll returns a noddelist consist of all the matching elements 

2. How do you **create and insert a new element into the DOM**?
--I can create a new element by using the method'document.createElement()' and I can add this element into the DOM by applying the method 'appendChild()'. Here the added element is the child element and the element in which the child is added is called parent element

3. What is **Event Bubbling** and how does it work?
--Event bubbling is the process in which a event starts from target and passes through its ancestors until it reaches the final and last endpoint.
--When an event is first captured by the target element,it propagates from the lower element(child) to the upper element(parent) and then to its upper element.

4. What is **Event Delegation** in JavaScript? Why is it useful?
-Event Delegation is the process where an eventlistener is added to the parent element instead of child elements. As a result,when the event bubbles up to the parent element,it can decide which child element is clicked.
It is useful because we don't need to add eventlistener to every child element,it shortens the code also. Moreover if any child is appended to the parent element later,it still works.

5. What is the difference between **preventDefault() and stopPropagation()** methods?
--preventDefault() method prevents any default behavior of an element from happening
stopPropagation() method is used for stopping the propagation or bubbling up of an event from the child element through the parent element

