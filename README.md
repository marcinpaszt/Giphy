# Giphy
For this assingment, I have created a series of buttons using the <button> tag. Afterward, I created an array to hold all my buttons.
The document.ready function holds all of the the next functions. Next I created an .onclick function to assign a value to the new user input
and created a new dynamic button based on the used inout as well. Next, I created another .onclick function to listen for when the predetermined
buttons were clicked. This .onclick function holds my API key as well. Next I made a call to AJAX using the GET method. The .then function
holds a response which i assigned to a variable called var results. I've created a for loop to loop through the reults retrieved by API and
created new divs to assign to. I've assigned an attribute the the musicImg div of results retrieved from API and the source as well. 
I've appended the musicDiv to both the musicImage tag and the p tag. Next, I used a .mouseover function to animate my gifs, which animate when on hover.


Fpr app demo, click here:  https://marcinpaszt.github.io/Giphy/
