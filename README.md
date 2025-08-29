

### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
>> getElementById: this helps to select elements by their Id name,
>>getElementsByClassName: this will select all the elements with same class name
>> querySelector: this will select first element of a dom by css selector
>> querySelectorAll: this will select all of the elements of a dom by css selector
2. How do you **create and insert a new element into the DOM**?
>> document.createElement('') and document.appendChild('')
3. What is **Event Bubbling** and how does it work?
>> when any event triggered on the an element it will have impact over its upper element too like a child to parent hierarchy
4. What is **Event Delegation** in JavaScript? Why is it useful?
>> when we add listener to the parent element and it's child triggered any event, its bubble through its parents and it can take actions based on it, its useful to manage event handling
5. What is the difference between **preventDefault() and stopPropagation()** methods?
>> preventDefault() stops unnecessary loading of the page after triggering a event and stopPropagation is something when a child triggered something and you dont want to send that to its parents 
