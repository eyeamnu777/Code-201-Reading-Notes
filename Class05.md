# Readings: Images, Color, Text
images: 
  <img src="https://www.example.com/images/dinosaur.jpg" alt="Dinosaur" /> (absolute URL)

<!-- What is a real world use case for the alt attribute being used in a website? -->
- [alt] attrobute is the textual description of the image USED WHEN image doesn't load or internet has slow connection that causes it to rinder (inside <img > as ' alt= ' )
- for search engines to match alt text w/ search queries
- when images are turned off turned off images to reduce data transfer volume (based off bandwidth) and distractions

## <!-- How can you improve accessibility of images in an HTML document? -->
- Add alt text and title if you want your images to be conveyed to all users
- If the picture is purely decorative, provide at least null alt text (alt=””)

<!-- Provide an example of when the figure element would be useful in an HTML document.--> -->
- to provide a semantic container for figures, and to clearly link the figure to the caption 
## <figure>
  <img
    src="images/dinosaur.jpg"
    alt="The head and torso of a dinosaur skeleton;
            it has a large head with long sharp teeth"
    width="400"
    height="341" />

  <figcaption>
    A T-Rex on display in the Manchester University Museum.
  </figcaption>
</figure>
*reference: <a href=" https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML>">MDN Web Docs</a>
<a href="https://www.w3schools.com">Visit W3Schools</a>

<!-- Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community. -->
    - Expresses your meaning in a compact, easy-to-grasp way.
Could go in several places in the page's linear flow.
Provides essential information supporting the main text.
A figure could be several images, a code snippet, audio, video, equations, a table, or something else.

                        <!-- EXTRA  --> 
CSS background images
<p  {
  background-img: url("images/dinasour.jpg"); 

}
## Elements like <img> and <video> are sometimes referred to as replaced elements. This is because the element's content and size are defined by an external resource (like an image or video file), not by the contents of the element itself. 

<!-- Describe the difference between a GIF image and an SVG image, pretend you are explaining to an elder in your community. -->
  -GIF means Graphic Interchange Format ( .gif )
      `for simple images and animations (series of moving stills)
      `a compressed graphics format
` gif is HTLM based (more front-end) and SVG is an XLM-based vector (back end)
  -SVG stands for Scalable Vector Graphics
      ` XML-based vector graphics format that specifies the contents of an image as a set of drawing commands that create shapes, lines, apply colors, filters, and so forth.
      ` for diagrams, icons, and other images which can be accurately drawn at any size
  -DEFINITION: are text files containing source code that, when interpreted, draws the desired image
  Explanation: gifs are a line of images appearing to move (like old school flickery photographery animation) while the other format of imaging 

<!-- What image type would you use to display a screenshot on your website and why? -->
`PNG image type is what would be used as it is a lossless format.
  -important for visibility of text in the screenshot (so it doesnt pixalate)

<!-- Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge. -->
`Foreground- property defined by ( color ) property [aka the text]
`background- property defines the element's background

<!-- Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character? -->
` body { 

}