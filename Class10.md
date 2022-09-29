# CLASS 10- BUGGING 

## 1) Name some key differences between a Syntax Error and a Logic Error.

Syntax Errors are errors based on misspelling where logic error is  due the code gives incorrect results with the a correct syntax.

## 2) List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

I have experienced a syntax error a couple of times where I was missing the S in elements and it was fixed by starting by the closest ancestor line of code.

## 3) How will this topic continue to influence your long term goals?

It points more in the direction of possible error types and location and tells one what to look for, and not to panic when red is seen.

## How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

The JavaScript debugger is like similar to a bouncer at a busy night club, watching over values and where they may break down, not letting the problem get through.

## Define what a breakpoint is.

a breakpoint is the point where it simply serves as an alarm for the debugger to step in and clarify what type of error it may be. 
    - when the bugger demands a prompt to the coder (inputNewItem)

## What is the call stack?

Call stack is a section showing what code was executed to get to the current line and can only be used while code is running.

Sources: 
-- https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger

--https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong

CLASS 10 NOTES

Lab Review
-- Eric
missing from input (required) fields
  -under fieldset
  <input id="Maxcust" type="number" name="Minicust" required> <-- tethering to clikc name
  15:00  //id is ref ---- name is 

<button> submit information from the fields
Step 1: line 10 grabbing form element and storing it into Standdataa
Step2: line allowing to handle submission -- triggering function
salesStandForm -- first html element going to work with (html perform element)
---- type of event it will be listening for (gave button a type of submit)
salesStandForm is adding an event listener which is getting value frm (submit, handeleSumbit)
20:00 EXPLANATION created eve

24:00 
event.preventDefault();
        - stops from entering URL

newLocation.getCustomers(); 
  .push ing location
newLocation.getCookiesSldPerHr();

32:00 
tfoot,textContent= ' ';
  so it can clear out footer to and then recalling re-render afterward
  - other options:

  used "delete tfoot" referenced to the entire table 
  elementById
  attached to table and then delete  row
        either at 1 (first row)or -1 (final row)
        tfoot.html

58:00   **clock analogy for j being fast loop () and i being slow loop (hour hand on the clock)

REVIEW RENDER FOOTER function
38:00 LINE 129-143
explanation of Footer in total with my input

Activity debugger
1.'l' in stuedent list wasnt capitlized -->studentList
2. line 43 a is the new instance of student should be able to call validate which will reurn something.. can't use this is scoped to the function (studentGenerator) -
3. line 32 should be this.studentName something related to the object that will be created to reference student name in line ____ [1:39:00]
  line 24 split is a method you can attach to a string and split 
  going to return an array based on elements based on where it was told to split and make that  ['Dayo' , 'Jason' ] individual arrays

Lecture
  Examples

ARRAY METHODS (good for next week)
.push = used at the end of the array *why??*

Ways to add to an array
  - .push >> adds to the end of the array *most efficient bc code finds space for it and go to last element
      months.push( 'Aug' , 'Dec');

      console.log(months);
    --> [ 'Apr', 'June', 'July', 'Aug', 'Dec' ]
  - .unshift() >> add to the START of the array *have to move every element into a new index--create an empty space at index0 and shift everything down*
       months.unshift( 'Jan' );
      console.log(months); 
        
    --> [ 'Jan', 'Apr', 'June', 'July', 'Aug', 'Dec ]

  - .pop() removes the VERY LAST element from the array 
      ****MOST EFFICIENT****
    months.pop();
    console.log (months) 
    --> [ 'Jan', 'Apr', 'June', 'July', 'Aug', ]
 2:17:00    + helpful if removing things from an array 

  -.shift >> removes FIRST element from the array
    months.shift();
    console.log(months);

2:22:00 explanation of storing 




COMBINIATION OF ADD OR REMOVE FROM ANYWHERE IN ARRAY
  .splice();
  arg- where to start, # of elements we WANT to remove (if any), what to add  (if any)
    -- want to add september and october
    statr at index one because you want to start/remove June and July

    what you're adding >> start at index 4 becaues 

    months.splice(4, 0, 'Sept', 'Oct' );
    console.log(months);

<2:24:00>

    [ 'Apr', 'June', 'July', 'Aug', 'Dec' ]
    [ 'Jan', 'Apr', 'June', 'July', 'Aug', 'Dec ]
    [ 'Jan', 'Apr', 'June', 'July', 'Aug', ]
      *input console output here*

    start at index one because you want to start/remove June and July

let splicedMonths =
  months.splice(1,2);
  
  console.log(splicedMonths);       June & July  <--- elements removed

  .includes() >> return a boolean value if the arg you pass in, is in the array 
    let isItThere = months.includes('Oct');

    console.log(isItThere);

    //SIDE NOTE FOR NEXT WEEK 
    array and act similar to data structures
    stacks and que
    stacks FILO (think of when you stacking plates- youll grab from top first)
    push()-pop()

    [1,2,3,4]

    push()-pop()
    [1,2,3,3]

    queue FIFO (like first in line, FCFS)
    [3,2,1]
    unshift() - pop()
    push() - 


    Partnered Lab on 10a 
      one person is going to create a repo choc pizza >> next fork it >>*driver nav model*

      *****function wizardsOfMiddleEarth() {
        this.gray = "Gandalf";
        this.white = "Saurumon";
        this.brown = "Radaghast"; 
        this.blue = ["Alatar", "Pallando"];
        return this.gray + this.white + this.brown + this.blue[0] + this.blue[1];
      }