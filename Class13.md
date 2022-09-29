# why this topic matters as it relates to what you are studying in this module.
Class 13 is about Application States with Local Storage API: gives us information on what can go to local storage and the sensitivity 

## Why would a developer use local storage for a web application?
"The web is stateless" and its state resets every time it is closed
Local storage is what's better known as the 'cookies' as cookie refers to saving small piece of gathered information hosting it on the server



## What information should not be stored in local storage?
nothing personal or sensitive scuh as keys for the site, passwords, or personal data

## Local storage can store what type of data? How would you convert it to that type before storing? 
LocalStorage can only store string data for its keys and values -- using getItem or setItem or JSON.stringify() [prior to sending data into Storag] and JSON.parse()
(no objects) [turns data from a string back into the original datatype]


Sources:
https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/


CLASS LAB NOTES:

reason why added variable, if just created new bunny goat, *looks at constructor*, reconstructed bunny will 
 the views and clicks will be 0
 }
  if(retreivedGoats) {
    goatArray = parsedGoats;
  } else{
    new Goat('bunny-goat', 'png');
    new Goat('...', 'png');
    new Goat('...', 'png');
    new Goat('...', 'png');
  }