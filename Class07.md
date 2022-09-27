# Class 07

## Explain why we need domain modeling

 serves as an important communication tool to solve specific problems among various stakeholders

## Why should tables not be used for page layouts

 reduce accessibility for visually impaired users (ie: screen readers), it makes it harder to write, maintain, and debug code, and are not automatically responsive

## List and describe 3 different semantic HTML elements used in an HTML < table >

 <th> table header <tr> table row <td> table data

## What is a constructor and what are some advantages to using it?

a constructor is a function known as the blueprint for objects -- advantages include it provides a clean code which allows simpler accessibility and it helps keeps code from bugging

## How does the term this differ when used in an object literal versus when used in a constructor?

this in object literals are
this in a constructor is
Object Prototypes Using A Constructor

## Explain prototypes and inheritance via an analogy from your previous work experience

prototypes is like uploading a google docs for a group project and giving permission for others to edit the paper and their edits serve as the inheritance??

<!-- ?? because not sure if correct ideal example concept -->
<!-- prototypical inheritance allows us to reuse the properties or methods from one JavaScript object to another through a reference pointer function -->

'use strict';


let nu = {
  name: 'Nu',
  title: 'Sister',
  course: '201d90'
}

let stan = {
  name: 'Stan',
  title: 'Brother',
  course: '201d90'
}

let steph = {
  name: 'Steph',
  title: 'Brother',
  course: '201d90'
}

//^ this is where constructor functions come in (so we dont have to type a large amount of objects resulting in typing up a lot of object literals)
// CONSTRUCTOR FUNCTION-- generate a # of parameters and gives whole object
// PARAMETERS -- what is unique to each object *hints: what goes inside the paramters aka ()

let prsnOf201d90 = [];

function prsn (firstName, title){
  this.name = firstName;
  this.title = title;
  this.course = '201d90';
  this.interests = [];
  prsnOf201d90.push(this);
}

//line 23= function.*property name* (unique parameters){ 
//assignment operator goes with semicolon ';'
//'this' in a constructor refers to the WHOLE object that gets created via '=' sign
// line 26-- is the exact wording of course because it is consistent throughout each variable (course: 201d90)
// line 27-- empty ARRAY [] not going to be unique b/c we might need to populate later
// ******adds line 23 as empty ARRAY *******
// constructor function is going to add every object created into ARRAY (lines 26-30) into *pplOf201d90
 //*line 30* // so when f(x) is invoked its going to create the object and the coder will tell it to be add it to the empty ARRAY (pplOf201d90 = [];)


   // Create objects using constructor
  // CONSTRUCTION IS A f(x)!

new prsn('Nu', 'Sister');
new prsn('Stan', 'Brother');
new prsn('Steph', 'Brother');

// prsnOf201d90[2].interests.push('bowling');
console.log(prsnOf201d90);

// lines ___ - __ are function calls ('');
// line 49 console.log our ARRAY
// whats different from other code seen, the objects are LABELED (ie: prson -- from line 42/45 & line 30)
//example:
//  console.log(nu);
  // *outputs as object literal - { name: 'Steph', title: 'Brother', course: 
// 201d90' }
//hint: hit control+c anytime to enter REPL

// *wanted to look at adding interests to specific Steph via 'name:'**
//accessing Steph as he is the 3rd element in the ARRAY
//get to interests ARRAY --> (.interests)
// add Stephs interests --> (.push)

 // peopleOf201d90[2].interests.push('bowling');

//console.log(prsnOf201d90);
//console.log allows it to be seen on the webpage
  // { name: 'Steph', title: 'Brother', course: 
// 201d90' interests: [ 'Bowling']}