# Html


## Forms

***Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.***


*There are several types of form controls that you can use to collect information from visitors to your site.*



* *A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.*


- *You have probably seen forms on the web that give users messages if the form control has not been filled in correctly; this is known as form validation.*


* Each form control is given a name, and the text the user types in or the values of the options they select re sent to the server.




## Lists, Tables and Forms


* ***There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables and forms.***


*Nobody I know enjoys filling in forms, so if you can make yours look more attractive and easier to use, more people are likely to fill it in. Also, when you come to look at a form in a few different browsers (as shown on the right), you will see that each browser displays them differently.*



* Forms are easier to use if the form controls are vertically aligned using CSS.




## Events


***When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.***



* *When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling.*


- *Event listeners are a more recent approach to handling events.They can deal with more than one function at a time but they are not supported in older browsers.*


***Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround.***


***When an event occurs, the event object tells you information about the event, and the element it happened upon.***


*Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element.*



When calling a function, the event object's target property is the bestway to determine which element the event occurred on. But you may see the approach below used; it relies on the this keyword.





* *User interface CUI) events occur as a result of interaction with the browser window rather than the HTML page contained within it, e.g., a page having loaded or the browser window being resized.*





***The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.***




