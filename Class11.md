1) Explain how the ability to use video and audio on the web has evolved since the early 2000s.
      - The internet used to be plug-in based where AdobeFlash had to be a plug-in on the computer or else a little broke paper would pop up. There were security and accessibility issues. <video> and <audio> elements in JS are apart of the change.


2) Describe the use of the src and controls attributes in the <video> element.
      -src serves as the PATH to the video you want to embed
      controls is the way to control video and audio playback - stop and play media or turn the volume or proved resoultion settings, etc.


3) Why is it important to have fallback content inside the <video> element?
      - In case the browser doesn't support the video element, it reverts to the embedded link/legacy.

4) Write a very short story where <audio> and <video> are characters.
      - Man this guy named Sound Audio started out as an idea and next thing you know he had M's: mp3, mp4, on dvds and cds. I remember when you didn't need money to get downloads of Mr. Audio. His friend Sight Video on the other hand wasn't always the most embedded. But now in 2022 they are still long time friends, working closely at HTML who's corporate is the web.


5) How does Grid layout differ from Flex?
      - Grids are two dimensional meaning it can work columns and rows simultaneously.
      Flexbox is one dimensional moreso the insider used to align and create spacing items in a container (container => made of grids) and used for more small scale layouts.


6) Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
      - Grid container is the parent or the outside of the box. Grid lines are the lines that create rows and columns. Grid item is one of the children of the grid container and is under the div class.


7) Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
      - Because there are different screen sizes, more variety now than before making it accessible across all screens.
    "Responsive image technologies were implemented recently to solve the problems indicated above by letting you offer the browser several image files, either all showing the same thing but containing different numbers of pixels (resolution switching), or different images suitable for different space allocations (art direction)."

8) Define the following <img> attributes srcset and sizes. Write an example of how they are used.
    - Srcset are the set of images we allow the browser to choose between and what size each image is separated by comma. 
      example: elva-fairy-480w.jpg (480w) the w measures width units instead of px
    - Sizes define media conditions and chooses what size would be best according to the condition. Before each comma.
      example: (max-width:600px) viewport is 600px or less


9) How is srcset more helpful for responsive images than CSS or JavaScript?
    - allows to change the source image to a different size if desired beneficial because of the different size of screens there are in modern tech

Sources: 
-- < https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content >
-- < https://css-tricks.com/snippets/css/complete-guide-grid/ >
-- < https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images >
-- < https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio >
-- < https://www.geeksforgeeks.org/comparison-between-css-grid-css-flexbox/ >


What I learned today: I was reminded of how Adobe Flash and Flashplayer used to pop up on screens and this was right around the time where Apple had the 3G Iphone. Now that I program I see how HTML CSS Aand Java serve as the head huncho of the internet, the new standard basically. The <video> element matched with controls attribute is what allows videos to be altered within the video "grid". Srcset controls the width and is the 'w' instead of px in CSS whereas px and isn't based on resolution more so the size of images. I gained a new perspective of how to calculate grid template in CSS.**
Push() adds one or more elements to the end of an array.
/////////////////////////////////////////////////////////////////////

Class 11 Notes -Monday Sep 26

Resume approval via Audrey
      -add links for github, linkedin
      -section for languages in tools: Github, VS Code, HTML, CSS, JS
      - another assignment with accountability partners

go on any job board (3) fill out spreadsheet to see what type of companies would be of interest, Job postings have keywords in their posts, 
sunday at 11:59pm LAST DAY TO TURN IN WORK--be at least at 80% for object week to pass class need 90% project group assignments 
      - Exam opens friday ends on sunday!!!!! miss up to 5 questions

// Code demo: CSS Grid
Grids
-way for us to layout page and resposnive feel
-% or fractionals allows us to more responsive for Grid by using fractionals
      1fr 1fr 1fr share equally the 90% (of the screen) equally
      2fr is double the size
-standard 12x12 (normal screen), smaller size 8x8, 4x4
use on the parent : grid-template-columns:      
            example: grid-template-columns: 200px 200px 200px
      next describe column --> rows
3 columns--->  200px auto 200px takes care of whatever is remaining     
            only auto is responsive
Columns - f(x) called REPEAT way for me to shorthand how many times want refractional to repeat
      (3, 1r) --> 1fr, 1fr, 1fr
      ex: repeat(2, 1fr, 2fr)

***** @media(max-width: 960px) { //open code block up
      main {
      width      
      }
serves as a breakpoint
} *****

grid-template-rows: 200px 500px
      more content, can do REPEAT functions
      -can add gaps between
            ex: grid-template-rows: 200px 500px
                  row-gap
                  column
                  if same #s column and row = (gap:)
      for no hard code--> auto (for the amount of content need)

How we can use grid to ____ page: very basic layout and then nest information inside
      -using a template area --> give tag name
      ex: grid-template-areas: 
            "header header header" <-- 3 columns>
            "sidebar content content" <first column 3 rows>
            "sidebar content content"
            "sidebar content content"
            "sidebar article article" youre only going to be a2x3 article is 2x1 sidebar 1x3
            "footer footer footer"
      (want header to go all the way across)

** grid-auto-rows == as many rows as want within area
grid-container div {
      border: 2px;
      font-size: 1.5em;
      padding:

}
.grid-item1{
      /* grid-area: sidebar*/
      grid-column: 1/-1 *similar to grid column start)
      grid column-start:1
      grid column end:-1

.grid-item2{
      grid row-2/6 *wanted it to spand down 4 rows*
      *

.grid-item3{
/*grid area content*/
      grid-column: *starts at line 2/-1* 2/-1
      grid-row: 2/5

.grid-item4{

}
.grid-item5{
      grid-column:1/-1;
      grid-row:6/6



other way to do exact same thing WITH NUMBERS 
each child has a line that lives on each side of wher its at
where we tell it to start adn end is going to be based off line numbers
      ex: have header start on line 1 end of line 4
      .grid-item1{
            grid-column: 1/-1
      
}
negative -1 first at the very end grid-column 1/-1

Read me.md

## What do we need
      
#### Globals
-storage -voting rounds (global counter)
- goat array
- DOM Windows -render images 
#### Constructor - GOAT Objects build goat instances
- Goat images -# of times viewed vs clicks
1 for each image
- names

#### Execuable code
- method to calculate view and clicks
- 2 random images to display
- render f(x) to get images on the page (DOM)
-eventListeners
- click count cotes and rerender new images
-


//if wanted to creat a new goat, will have a name
// new Goat(bunny-goat, 'img/bunny-goat.png');
// ---> ${name}.${fileExtension}`;
//use file extension to build pathway 
