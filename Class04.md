1. To create a basic link, we wrap text or other content inside what element?
To create a basic link, we wrap texts in <a>  element with the 'href' (aka TARGET) attribute.

2. The 'href' attribute contains the web address. 'title' is a tooltip that displays the overview of what the website may include.

3. We can ensure links on our pages are accessible to all readers by using as less words as possible in regualar text ("link text").

Learn JS
4. Normal flow describes wepage elements lay out originally  wihtout CSS. and elements can be changed via adjustment in normal flow or removing them from it altogether.

5. Difference between block level elements & inline-level elements

- Block level elements ALWAYS start on a new line & occupies the entire horizontal & height of, the space of the parent element (aka CONTAINER) hints, creating a larger structure
      -

      *stacked boxes*
  - Inline-level elements can start anywhere  && corresponds to PHRASING CONTENT (PHRASING CONTENT defines the text and the markup it contains, and can be used everywhere flow content is expected. Runs of phrasing content make up paragraphs.)

6. Static postioning ___ positioning is the default for every html element.

7. Advantages of absolute positioning

- isolation and doesn't exist in normal document flow
- good across browsers (doesnt change)
- can be placed where they want
    **top, left, bottom positioning attributes to set location**
  **NOTE: values will be relative to the next parent element with relative (or absolute) positioning. If there is no such parent, it will default all the way back up to the <html> element itself meaning it will be placed relative to the page itself.**

8. Key differences between absolute and fixed positioning:
fixes an element in place relative to the visible portion of the viewport.

-positioned relative to the viewport (browser window) or where it stands when page is scrolled

- ex: navigation bar visible dispite scroll position

--- Absolutely positioned elements are positioned with respect to a containing block, which is the nearest postioned ancestor. If there is no positioned ancestor, the viewport will be the containing block. Elements with fixed positioning are fixed with respect to the viewport—the viewport is always their containing block---

*NOTE: The top: 0; is required to make it stick to the top of the screen. We give the heading the same width as the content column and then a white background and some padding and margin so the content won't be visible underneath it.{*}

9. difference between a function declaration and a function invocation

- Function declaration = name of the function in the code somewhere, followed by parentheses 
Function Invoke- to use a function after it has been defined, you've got to run


10. What is the difference between a parameter and an argument?

parameter =>  included inside the function parentheses

argument = values declared within a function when the function is called

## THINGS I WANT TO LEARN MORE ABOUT

logic of string when getting alert ( use a + or ~ will convert a string to a number )

- how to break out of while loop (42:00)

Class 4 Lecture notes

## functions

- a resuable data type
- group of statements that perform a task or calculate value store in a structure that prevents them from running until the function is 'called' or 'invoked'
  - input -> processing -. input

### Why do we use functinos?

- reusable/repition
- efficient
-easier to read amongst all users
-prevents bugs
-perform actions

### 2 step process

- to define/ declare function
- call/invoke
