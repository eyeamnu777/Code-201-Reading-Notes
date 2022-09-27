# Forms and JS Events

    <!-- HTML FORMS -->

## Why are forms so important in web development?

serves as a containing interactive controls for submitting user information

## When designing a form, what are some key things to keep in mind when it comes to user experience?

   only for the data you absolutely need, keep it short (input fields) and concise

## List 5 form elements and explain their importance

1) <input> 
-used to create interactive controls for web-based forms in order to accept data from the user
-powerful due to # of combinations of input types and attributes 

-----HTMLInputElement interface provides special properties and methods for manipulating the options, layout, and presentation of <input> elements.----------

2) <label> represents a caption for an item in a user interface.
-To associate the <label> with an <input> element, you need to give the <input> an [id attribute].
-associated with only one form control.
-has no labeled control
 ( <label for="name">
  Name: <input type="text" id="name" name="user_name" />
  </label> )


<!-- if the attribute is specified and there is an element in the tree whose ID is equal to the value of the for attribute, and the first such element in tree order is a labelable element, then that element is the label element's LABELED CONTROL. -->

( <input type="text" id="fname" name="fname"> )

3) <select> represents a control that provides a menu of options (defines a dropdown list)
  - [id attribute]
  -Each menu 'option' is defined by an <option> element {nested} inside the <select>.
    -- <option> elements can be {nested} INSIDE <outgroup> to create separate groups of options inside the dropdown.

4) <textarea> = the space/area where text goes (ie: feedback box)
  -id attribute allows the <textarea> to be associated with a label for accessibility purposes

EXAMPLE: 
<label for="story">Tell us your story:</label>

<textarea id="story" name="story"
          rows="5" cols="33">
It was a dark and stormy night...
</textarea>
<label for="story">Tell us your story:</label>


5) <button> -- a clickable button like the submission button

      <!-- LEARN JS- INTRO TO EVENTS -->

## How would you describe events to a non-technical friend?
- In an airport, when the runway is clear for take off, a signal is communicated to the pilot. As a result, the plane can safely take off.

## When using the addEventListener() method, what 2 arguments will you need to provide?
-the name of the event we want to register this handler for &
-the code that comprises the handler function we want to run in response to it

## Describe the event object. Why is the target within the event object useful?
-a parameter inside an event handler function to provide extra features and information
-target property of the event object is always a reference to the element the event occurred upon

- in the DOM (Document Object Model)

<!-- The standard Event object has a function available on it called [stopPropagation()] which, when invoked on a handler's event object, makes it so that the first handler is run -->

## What is the difference between event bubbling and event capturing?
- 
-event bubbling (bubbles rise to the top) checks the click event handler for the direct parent instead of outer most ancesetor (outer most ancestor is html)
-event capturing works its way down FROM the HTML tag


<!-- The FOR for attribute of the <label> tag should be equal to the ID attribute of the <input> element to bind them together. -->

SOURCES:
- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select
- https://html.spec.whatwg.org/multipage/forms.html#the-label-element
- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_objects (example of describin an event)

-------------------------------------------------------------------------------------

# Class 09 

// These are just class notes for Thursday 9/22

- Code review of previous class lab assignment

#Browser Event Types
-click
-submit (when a form is clicked)
- hover event something a
-mousecover
-page load
if you have an event listener listening to a nav link, it may not let you hit the <a> because it will listen to event first and ignore the trying to click on <a>
        -point of pseudo class so events dont fire off at the same time


      Code Demo (Events & Even listeners -- HTML Forms)



                        Events
    
how to take event happening on screen to trigger something else within html page

<section id="container">


            ## JavaScript - Code Event listeners
-Code will be trigger when the event has fired
- Targets some HTML element that it listen to 
`let mycontainer.document.getElementById'my-container');`

-sepcify the type of event to listen to
-specify what function is called
`myContainer.addEventListener('click', handleClick)
method of .ELement in DOM (taking two arguements)



HTML Forms
