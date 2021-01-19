### Transforms

***With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.***


* The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.


#### Transform Syntax


***The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.***



#### Combining Transforms

*It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.*


***Perspective***

*In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.*




***Transform Style***

On occasion three-dimensional transforms will be applied on an element that is nested within a parent element which is also being transformed. In this event, the nested, transformed elements will not appear in their own three-dimensional space. To allow nested elements to transform in their own three-dimensional plane use the transform-style property with the preserve-3d value.




### Transitions & Animations

***One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.***


* With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.



### Shorthand Transitions

***Declaring every transition property individually can become quite intensive, especially with vendor prefixes. Fortunately there is a shorthand property, transition, capable of supporting all of these different properties and values. Using the transition value alone, you can set every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay. Do not use commas with these values unless you are identifying numerous transitions.***


Here are 8 really simple effects that will add life to your UI and smiles to your users’ faces:

Fade in

Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.


Change color

Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them.

Grow & Shrink

To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

Rotate elements

CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.

Square to circle

A really popular effect at the moment is transitioning a square element into a round one, and vice versa. 

3D shadow

3D shadows were frowned upon for a year or so, because they weren’t seen as compatible with flat design.


Swing

Not all elements use the transition property. We can als create highly complex animations using @keyframes, animation and animation-iteration.


Inset border

One of the hottest button styles right now is the ghost button; a button with no background and  heavy border.