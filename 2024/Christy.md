# Dragon Clicker Reflections

## Initial Request
To create my Dragon Clicker, I added a dragon emoji and gave it the class "dragon". I also created a blank 'span' area below it as a space for the click count to be generated.

Using JavaScript, I used .querySelector to target the dragon emoji and an eventListener to recognize when the emoji was clicked on.

I created a function to increase the click count by one when the dragon emoji is clicked on. Using the .innerText property, I appended the HTML document to include the click count.

## Dragon Duo
With the change in request from the client to include a second dragon, I duplicated the first dragon in the HTML doc and then styled each differently to represent fire or water.

I found that after adding the second dragon, only the first counter was functioning. I modified the HTML and JavaScript so each dragon is using unique classes, and this worked, but I'm not sure it is the preferred solution.

## Dragon Gang
I started this challenge using the code created during the code along in class. It already had the click functionality and 5 dragons on the page, but the dragons were placed using HTML and not JavaScript.

To place the dragons on the page using JavaScript, I used the .forEach method on the dragonTypes array to create a new div in the HTML document for each dragon type. I used interpolation to apply a class to each div that was unique for each dragon type in the array. I did run into an issue with this because I had a typo and forgot the closing quotation mark around my class for the div. Once that was corrected, it worked!
