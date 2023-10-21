# Inputs, Display, and More

## What I learned
### Inputs
A major topic we were discussing in my intro Web Deign course was Input and forms. For this assignment wewere tasked with using as text box inputs many as we could.  \
Imputs require two attributes, a ```<input>``` tag and a ```<label>```tag. The ```<input>``` tag is where you will specify what type of input you are using.   \
Examples of them can be... a text box, date, mailto, or a radio button. The ```<input>```  will the type of input, but it also needs and ID and a name, which can all be similar. For example you can use 'text' for the type, 'lastnameID' for the id, and 'lastname' for the name. They will all need to between first ```<input>```   \
ex. ```<input type="text" id="firstname" name="firstname">```. \
The ```<label>``` will hold the title for  the input.  \
ex.```<label for="lastname">Last Name:</label>```  
### *Important note, the label should go before the input when typing code
ex.```<label for="lastname">Last Name:</label>```  
```<input type="text" id="firstname" name="firstname">```

### Displays
I also work also with the display for this website. I worked on using a pagewrapper to better showcase the content of the page. This time juggling the navigation side bar, a photo, and the text. Setting the ```gride: display``` in the css under ```.pagewrapper``` selector that I have housing the content of page in, allows to easily proportion the webpage to create mutliple columns to house the content. 

### Active Navbar
I also learned how to use the ```:active``` tag to enhance my navbar. This tag will display specific CSS while it is on the active page. After using the ```a``` selector in my CSS to pick up the link to different pages, then combine them together, ```a :active {...}``` to change the color of the text with the ```text-color; #XXXXXX```. I also found that you could use ```:not(.active)::after{...}``` to select the linked pages that where not activie, I also changed the opaceity to being more attention to the page the user is on. 

[Visit the Site](https://giaviolini.github.io/inputs-and-display/)
