These topics matter because the previous lab asked for a nice visualization to be presented.


## What does the <canvas> allow a developer to acheive?
Allows coders to draw two dimensional graphics using JS.


## What is the importance of the closing `</canvas> tag?
 Anything within the tags serve as fallback content in case a browser doesnt support the element (basically a backup option) and requires the closing tag </canvas>

## Explain what the getContext() method does.

 The getContext takes one argument (the type of drawing context).

// Chart.js Documentation:
## What is Chart.js and how it can be brought into your project?

Chart.js is a JS plugin that uses HTML5’s canvas element to draw three different types of graphs onto the page.

## List 3 different Chart types you can create using Chart.js.

pie line and bar chart

## What are some advantages to displaying data via a chart over a table?

It would be helpful for screen readers and it's easier to catch a reader's eye- by providing a visual.


## How could Chart.js aid your previously created applications visually?
Odd Duck Product Co preferred a graph for visualization purposes.


##Things I want to learn more about:
is this what the next lab (12) be about? hmm i wonder.

#sources:
<https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/ >


Leanred about how Chart.js offer different formats to pratice with and problem sold like documents.

                        LAB 12
                        
  <h2>Choose your preferred item.</h2>
  <h3 id="vote-count-display"> </h3>
</section>
<section class="result-section">      
  <div class="div-container">
    <div id="p-div"></div>
    <div id="canvas-div">
      <!-- <canvas id="my-chart" width="350px" height="350px"></canvas> --> --from classmate example?
    </div>
  </div>

</section>


<!-- //have local storage start after every round is completed
  // *under if(count === 0) after constructor -- .push makes it into string
    // Step one: want to STRINGIFY data (get ready to be stored in local storage)
      
    *2:09:00 explanation broken down 
    let stringifiedGoats = JSON. stringify(goatArray);

      console.log('stringified goats >>>', stringifiedGoats);

  // STEP 2: add to local storage
    localStorage.setItem('myGoats',stringifiedGoats);
    // -------------------------------------------
// ***** more local storage code *****

    // STEP 3: how to pull stuff out of local storage (getItem) -- just an object{...}
    let retreivedGoats = localStorage.getItem('myGoats')
    console.log('retrievedGoats >>>', retreivedGoats);

  // Step 4: PARSE DATA INTO CODE MY APP CAN USE -- takes all of 
    let parsedGoats = JSON.parse(retrievedGoats);
    console.log('parsedGoats >>>', parsedGoats);


    // myGoats = key
    // goat created instances 
    // loops through and see's an _bracket {_}_ and created an array, _[]____ create an object 
    // if had prototypes in/ under constructor function
    // Goat.prototype.method = function() {

    // }

    // ***set up conditional (if) if there are goats if there's information in the storage -we wwill run
  

  }
//   // ***REBUILD GOAT INSTANCES USING CONSTRUCTOR****
//   for let i = 0; i < parsedGoats.lenth; i++){
//     if(parsedGoats[i].name === 'bunnygoat') {
//       let reconstructedBunnyGoat = new Goat(parsedGoats[i].name, 'png');
//       reconstructedBunnyGoat.clicks = parsedGoats[i].clicks;
//       reconstructedBunnyGoat.views = parsedGoats[i].views;
//     } else {
//       let reconstructedGoat = new Goat(parsedGoats[i].name);
//       reconstructedGoat.clicks
//     }
//     } 
// reason why added variable, if just created new bunny goat, *looks at constructor*, reconstructed bunny will 
//  the views and clicks will be 0
//  }
//   if(retreivedGoats) {
//     goatArray = parsedGoats;
//   } else{
//     new Goat('bunny-goat', 'png');
//   }

  // as long as some empty string is true, will return

  // empty array globally , every time refreshed it would say its empty, if there is youre no longe going to be an empty array, you will be assigned the values
  // *** We are checking whether or not there have already been goats stored in the local storage. If there is, we're going to use the local storage to access our goat objects. Otherwise, we're going to create new instances of goats

  // step 1-2 if value exists, going to need to parse information and use that information in code (parsedArray), if first time you're here, will create new goats.

  // 2:10:00
  // with vote count hitting 0 
  // 2:15:00
  // if(retrievedGoats){
  //   goat
  // } -->