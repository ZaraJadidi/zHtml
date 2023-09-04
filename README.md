# zHtml
HTML: stands for HyperText Markup Language.
### comments
Comments will help others (and future you!) to understand the code.
Comments are ignored by browsers and not displayed on the web page.
"<!--> comments < 
also You can use comments to temporarily disable part of your code so it’s not displayed by the browser.

<br>

###  lines
Elements like headings and paragraphs automatically start on a new line when you create them.
<br>

###  Standards & best practices
web pages compatible with different browsers and devices.
<br>

###  expressions<br>

nesting:The <body> container tag needs to surround all the elements displayed on the page. When some HTML tags go inside others<br>

head :You can use the head to help increase visibility and traffic from search engines like Google.<br>

Title, description and keywords are nested in the head tag.<br>

Indentation :a very good practice to improve code readability. Indentation is the spaces at the beginning of lines.<br>

web browser : Displays the web page<br>

web server : Stores and provides information<br>

formatting tags : Formatting tags are applied to text and are nested inside elements.<br>



b: bold <br>

u : underline text<br>

i : italic <br>

strong : highlight important text, it also has meaning and is used by screen readers<br>

em : define emphasized text, screen reader will verbally stress the words.<br>


Web accessibility : making websites more inclusive and removing barriers<br>

Screen readers : programs that make the content of a web site accessible to users who are blind, visually impaired or have a learning disability.<br>

semantic formatting tags : The strong and em tags are considered semantic formatting tags because they add meaning to the content. They can serve as an indication of emphasis to a screen reader.<br>


HyperText : a text that contains a link to another page, Web pages are called HyperText documents because they are connected by hyberlinks <br>

href: stands for HyperText reference.<br>


Landing page : In digital marketing, a landing page is where a visitor “lands” after clicking on a link in an email, an ad on Google, YouTube, Facebook, Twitter, etc.

Landing pages are great for selling stuff; they also let you track customers and collect data.

Whether you're looking to be a web developer, marketer, or even a data scientist, landing pages can be invaluable.<br> 

Attributes : You can have more control over HTML elements with attributes.
Attributes are modifiers that provide additional information about elements.Attributes can be optional or required. e.g img tag requred src att.For container tags, the attributes always go in the opening tag. The anchor tag is another example of an HTML element that requires an attribute to work correctly.( a tag requred href att . )href (in the anchor tag) and src (in the image tag) are examples of attributes.
<br>

some attributes: <br>

ID:To jump to a specific part of a single-page website, first you need to mark the section with the id (ID) attribute.The id attribute is used to identify the element you want to target with the navigation link. 
Each id attribute value must be:1.unique 2.within quotes
Once the element you want to jump to has been marked with an id, you can target it with an anchor tag <a>
The hash character (#) is needed to tell the web browser that we are targeting a section of the same page. 
 Multiple elements cannot have the same id attribute in HTML
 jump link : ID






<br>


alt : (alternative text) is used to add image descriptions.1.read aloud by screen readers
.2.shown when the image doesn’t load
.3.read by search engines
<br>

Width: is an optional attribute.You can control the size of images in your web pages.controls the horizontal dimension of an image.
name = "value" e.g width ia an att name and "300" is value of an att.
<br>

Height :  is an optional attribute for the image element.Both width and height are measured in pixels by default.

When only one of the 2 attributes is given, the web browser will calculate the other based on the aspect ratio so the image is not stretched or squeezed.The aspect ratio of an image determines its rectangular shape.
Changing the aspect ratio of an image causes distortion, which can look bad.<br>


The way visitors navigate a website depends on its design. Websites come in 2 shapes:

- Multiple-page websites:websites are made of more than one page. Navigating between pages requires the web
browser to load different HTML files


- Single-page websites: A single-page website has all its content on the home page. Any navigation links take the visitor down to different sections (instead of loading new pages). <br>

nav : the nave container tag defines a set of links that allows the user to navigate between pages of a website.Links to the different pages are added with the anchor tag <a> and nested inside the <nav> container tag.

 <br>

 file extension: HTML documents must be saved with the right file extension (file type) for web browsers to recognize them. e.g . html documents : .html 

 index.html: A homepage must be named index.html in order for the web browser to find and load it. It’s best practice to name your homepage index.html so that the web browser can find and load it.
 <br>

 Forms: You can interact with the visitors of your website and collect information from them using forms.Forms are made of input elements like text fields, checkboxes, and submit buttons. These input elements are nested inside the <form> container tag.Form elements will be displayed in the same line unless we use the <br> (line break) tag.An HTML form is a convenient way to send data to a database hosted in a server.



You can use forms to let your visitors:

- get in contact with you

- send orders, requests and other information

- create an account or register

- and much more

Form elements:
1) Input:The most common form element is <input>. There are many forms of input element, depending on the type attribute.Such as Text,Radio,Checkbox
2) label tags: Labels can be added for the different input elements with the label tag.they come before input tags to label them .It's considered a very good practice to connect the label to the input elements with the use of for and id attributes.The id attribute is used to identify a unique input element. The for attribute in a label targets (and matches!) an input’s id.To connect labels and inputs, their id and for attribute values must match up exactly.
label: for
Input:id <br>

Connecting labels and inputs increases the <u> hit area </u>

input elements:
- text
- radio
- checkbox
- submit: A submit button is used to send the data in a form. The submit type of input adds a button to the form.You can use the submit input to send the data in the form to a database hosted in a server.


input attributes :
- name: The name attribute is used to reference the data after submitting the form .Only form elements with a name attribute will have their values passed to the database when submitting a form.The name attribute is used to put the input from the user in the correct field (column) in the database.
- value : The value attribute defines the value that is submitted when the input is selected.Names and values are needed to correctly store information in the database. The HTML code needs to include where and what to put in the database.For the case of text inputs, you can use the value attribute to define a default value that will be submitted unless a different value is provided by the user.Data will be sent when the form is submitted. You can control the data each option sends with the value attribute.



Select container tags: u can use it to create a drop-down list.You can use the <select> element as part of a form to collect user input.The selected attribute creates a drop-down menu with a pre-selected option. The pre-selected option will be displayed first.
Labels and drop-down menus are connected with for and id attributes, just like any other form element.The <select> element can be used in forms in combination with input elements.<br>


Option container tags: is used inside a  select  tag to add choices for the user.<br>

Videos : Videos can captivate and inform.You can use the video container tag to embed video files into a web page.Just like images, videos are embedded (or linked) into a web page. URL is needed. You can add video files in different formats. Common video formats are: MP4, OGG and WebM.The source empty tag provides the location and format of the video file.The src attribute specifies the URL of the video file.The type attribute specifies the format of the video file.Different media formats are needed for compatibility with different browsers and devices. The source tag allows you to add multiple files.When different source options are included, the browser will choose the first one it supports.You can add text between the video tags. The text will only be displayed in browsers that don’t support the video element.You can display play/pause, volume and other video controls with the controls attribute.Add the controls attribute if you want to show default video controls like play, pause, etc.  



<br>

 .video.<br>
 
 .source src="file.mp4" Type="video/mp4".<br>
 
 ./video.<br>
 
 





















 
   





 
  


 


 


































