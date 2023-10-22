# Inputs, Display, and More
Assignment 6 of 10

## What I learned
### Inputs
A major topic we were discussing in my Intro Web Design course was Input and forms. For this assignment, we were tasked with using as text box inputs many as we could.  
Imputs require two attributes, a ```<input>``` tag and a ```<label>```tag. The ```<input>``` tag is where you will specify what type of input you are using.   
Examples of them can be...  
a text box, date, mailto, or a radio button.  
The ```<input>```  will be the type of input, but it also needs an ID and a name, which can all be similar. For example, you can use 'text' for the type, 'lastnameID' for the id, and 'lastname' for the name. They will all need to between first ```<input>```   
ex. ```<input type="text" id="firstname" name="firstname">```.   
The ```<label>``` will hold the title for  the input.  
ex.```<label for="lastname">Last Name:</label>```  
Important note, the label should go before the input when typing code   
ex.```<label for="lastname">Last Name:</label>```  
```<input type="text" id="firstname" name="firstname">```

### Displays
I also work with the display for this website. I worked on using a page wrapper to better showcase the content of the page. This time juggling the navigation sidebar, a photo, and the text. Setting the ```display: grid``` in the CSS under ```.pagewrapper``` selector that I have housing the content of the page in, allows me to easily proportion the webpage to create multiple columns to house the content. 

### Active Navbar
I also learned how to use the ```:active``` tag to enhance my navbar. This pseudo-class tag will display specific CSS while it is on the active page. After using the ```a``` selector in my CSS to pick up the link to different pages, then combine them together, ```a :active {...}``` to change the color of the text with the ```text-color; #XXXXXX```. I also found that you could use ```:not(.active)::after{...}``` to select the linked pages that were not active, I also changed the opacity to bring more attention to the page the user is on. 

[Visit the Site](https://giaviolini.github.io/inputs-and-display/)
