HTML- INTRO
html serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences.
html makes use of tags to mark different elements
HTML is all about recognizing commonly used elements such as paragraphs, headings, lists, and links that define the structure of a webpage.
attributes provide a way to name HTML elements and reference them in other parts of the code stack.  Other attributes in HTML have various functionalities,other attribute allows visitors to edit the content on a web page. HTML attributes facilitate the editing capability within the browser.
ARIA Roles 
are extra attributes that can be added to HTML elements to convey the message more meanigful.
to create a link make use of the 'A'element which stans for ánchor'- we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference
to create a URL that is relative to the root level it needs to start with '/' can be known as absolute URL. a URL that is relative to the location of the file start it with ..- goes to one level which is the one mentioned on the URL. can be known as relative URL. 
THE FUNCTION OF HTML:
HyperText Markup Language, is responsible for marking up the content of a website. It informs the user's computer about various elements on the page.
Cascading Style Sheets, is like the stylist of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.
2. HTML TEXT FORMATING:
HTML SYNTAX: (HTML Paragraphs) 
Html uses tags, which are enclosed in less-than and greater-than symbols, to mark different elements. Tags come in two types: opening tags and closing tags. For example, the opening tag for a paragraph is <p>, and the closing tag is </p>. 
Html tags work together to define elements, which are like packages containing content. Some elements, like paragraphs, require both an opening and a closing tag, while others do not.
There is another phrase that is emphasized, which we have turned into a separate element by using opening and closing em tags. 
Example of a paragraph that has emphasised elements: <p> <em> for effect </em> </p>. 
HTML document is basically a bunch of HTML elements nested inside each other. This nesting creates a tree structure, like a family tree with parents, children, and siblings. The browser pays attention to this structure and builds a big family tree that shows how everything is related. To big Family tree that is called the DOM (Document Object Model). 
HTML HEADLINES: 
(HTML Headlines) elements serve the purpose of dividing content into smaller, more digestible chunks. They help people to comprehend the structure of the comtent. These elements also convey a sense of hierarchy in how the browser interprets and communicates about the page.  
The HTML elements used for marking up headlines come in six different types: h1, h2, h3, h4, h5, and h6. When viewed in a browser, each headline has a distinct visual effect. These elements also convey a sense of hierarchy in how the browser interprets and communicates about the page. 
This hierarchical system of headlines gives meaning to the browser, distinguishing what is most important from what is less important. It also ensures that all article headlines share the same type, h2, which is crucial for screen reader users who rely on consistent hierarchical information to navigate the page. 
HTML BOLD & ITALICS: 
There are four HTML elements related; two for Bold and two for Italics
Two different elements to convey this distinction for ITALICS. We use the "<i>" element to apply visual italics and the "<em>" element to add emphasis.
two different elements for Bold: "<strong>" element, which is used to show importance, seriousness, or urgency. the "<b>" element is more generic and neutral,  It does not carry any specific meaning; it simply allows us to make something bold visually and does not imply any alternative voice or mood.
**HTML LISTS:**
 In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. 
 Each item in the list is enclosed in an <li> element, which represents a list item. 
 To define the entire list and specify its type, we wrap all the items in a <ul> element, which stands for an unordered list. 
 The term "ol" stands for ordered list. 
 <dt> stands for definition term, <dd> tag stand for definition description is used for doe definition list.
 You can have multiple descriptions for each term by using multiple  tags. 
 The entire list is wrapped in a  <dd>tag, representing the definition list. 
 Interestingly, the <dd> tags and <dt> tags are placed side by side without any additional wrapper around them. 
 This is simply how a definition list is structured.
 **HTML QUOTES:** 
<cite> & <blockquote> elements serve a semantic purpose to inform other computers.
We can use the "<q>" element in HTML, which stands for quote. By using this element, the browser will automatically provide the appropriate quote marks for us.
Some HTML elements, like <strong>, <b>, <I>, and <em>, are called "inline" because they are meant to wrap around phrases of text that are inline with other content. 
They serve a similar purpose as the "<q>" element.
Some Elements in HTML known as block-level elements, like block quotes, paragraphs, and unordered lists. 
These elements essentially create separate blocks on the page. 
You can think of them as stand alone entities that can be followed by another block.
Datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this: <time datetime="2025-05-08">May 8, 2025</time>.
**HTML DATE & TIME INPUT**
To insert HTML time tag (<time>) and a closing tag (</time>). For example, we can use it like this: <time>May 8th</time> or <time>May 8th 2025</time>, depending on how we prefer to write dates.
The main purpose of the <time> element is to convey the exact date or time to computers.
**HTML CODE, PRE & BR:**
To add a Code syntax; ut an opening code tag before the CSS snippet and a closing code tag afterward. (code) (</code)
_HTML ENTITIES: "&LT;" & "&GT;" 
When we type "&lt;", it will be displayed as a less than sign. Similarly, typing "&gt;" will show a greater than sign. 
These entities are formatted like this: an ampersand, a short code, and a semicolon. When we include them in an HTML file, they are converted into the specific characters we want. We applied this technique to replace every instance of greater than or less than symbols with their corresponding character entities. 
br element: (mostly used in poems)
The br element is a simple tag without an opening or closing tag. It does not contain anything inside it; it just indicates where a line break should happen.
pre element: 
It is mostly used in poems that have irregular spacing.  Wrap the poem in pre tags, and now you can see that the browser respects the spacing, line breaks, and everything else. We can even insert a random character anywhere, and it will stay exactly where we put it.
HTML SUPERSCRIPTS, SUBSCRIPTS & SMALL TEXT: 
Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest. Subscripts are characters that are set below the normal baseline for text. Superscripts are characters that are set above the normal baseline of text. 
Superscripts: <sup> insert your text </sup> 
Subscripts:  <sub> insert your text </sub> 
Small text: <small> insert your text </small> 
3. **HTML CAPABILITIES:**
TROUBLESHOOTING & DEBUGGING HTML CODES:
**HTML ATTRIBUTES:**
The four most important Global Attributes: "class," "id," "lang," and "dir." You can find a comprehensive list of all the Global Attributes on MDM web docs.
The Class Attribute: allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class.
 Example of how to add "class" to style "class."
The ID Attribute: It is similar to the class attribute, but we can only use unique names once on an entire HTML page. IDs can be used for CSS targeting, but are more specific, which can sometimes cause issues.
Example of how to add "id#"
The lang Attribute: allows us to specify the language of the content using a short language code.
The dir Attribute: explicitly indicates the direction in which the text flows, using "LTR" for left-to-right scripts and "RTL" for right-to-left scripts. 
**ARIA ROLES:**
ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible. 
**FORMATING HTML:**
In HTML, comments are inserted by typing "<!--" at the start and "-->" at the end.
**UNUSUAL CHARACTERS:**
to insert a non-breaking space between the two names, ensuring they stay on the same line-  use the code "&nbsp;"
"&lt;", it will be displayed as a less than sign. Similarly, typing "&gt;" will show a greater than sign.
4. **HTML NAVIGATION & LINKING** 
**HTML LINKS:**
To create a web we use the A element which stand for Anchor;  To do this, we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference.  Between the opening and closing a tags, we can place text or images, or both, to make them clickable. By default, the A element is inline and can be placed within a paragraph or any other text.
The difference between HTTP and HTTPS. The "S" in HTTPS stands for Secure. 
**LINK:** <a href="insert your link"> </a> 
**HTML URL PATHWAYS:**
To create a relative URL, omit the domain name but include the initial slash at the beginning. The slashes in a URL indicate that we should look deeper into the file structure or go one level down.  This tells the browser to start from the root level of the file structure, which is the outermost top level. Alternatively, we can write the path to be relative to the file where the link is written. 
/images/logo.gif 
../images/logo.gif
The first version, /images/logo.gif, creates a URL that is relative to the root level. It means the browser will start looking for the file from the root of the website. 
The second version, ../images/logo.gif, creates a URL that is relative to the location of the file where the URL is written. The ".." followed by a slash means going up one level in the directory structure.
The URL ../images/logo.gif means starting from the current location, go up one level, find the folder named images, and then look inside it for the file logo.gif.
RELATIVE URL vs ABSOLUTE URL:
Relative URLs are based on the current file's location, while absolute URLs start from the root of the website.
**NAVIGATION:** 
creating a menu for a website: 
-wrap each link with the correct element 
-then enclosed in an "li" element to create a list of links
-Finally, encompass the entire menu in a "nav" element to indicate that it is the site's navigation.
-To give the menu a visual appearance, apply CSS styling.
-add some attributes to convey its purpose
-Assign the role "navigation" to the "nav" element, which signifies that it represents the main navigation of the page
-include an "aria label" for the main menu, providing a descriptive label that can be read aloud by a screen reader. 
**MENU ELEMENT**: <nav role="navigation"arial label"main menu"> 
             <ul class="navbar">
                     <li><a href="/"> Home</a></li>
                     <li><a href="/">people</a></li>
             </ul>
             </nav>        
5. **HTML WORKING WITH GRAPHICS & IMAGES:**
**IMAGES:** 
**IMAGE ELEMENT:** <img src="image.pjg"alt="give a depict of your image"width="400"height="300">
There are four ways to consider when inserting Image in a Webpage:
- The source attribute (SRC), which tells the browser which image file to load. (paste the Image URL into the source attribute) 
- The alt attribute (ALT), which provides a text description of the image. (serves as a replacement for the image when it cannot be seen. Description of whats in the Image, just focus on what it depicts). 
- The width and height attributes, which determine the size of the image.
**IMAGE FORMATS:**
when uploading an Image file on a website it needs to be in a certain file format, a format that web browsers can understand.
**MAIN FILE FORMATS:**
  -GIF:are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs. It only supports 256 colors, and images can end up looking pixelated.
  -SVG:is a vector file that contains instructions for drawing rather than individual pixels, are perfect for logos, icons, and other types of illustrations.
  -JPG:a popular choice for compressing photographs, it is important to resize and compress them appropriately when placed websites. 
  -PNG:is a newer format that works well when you need transparency in a photograph
**RESPONSIVE IMAGES:** HTML allows us to deliver different image files to screens of different sizes. We can create multiple image files and include them as options in our HTML code.starting with the basic code for loading an image on a webpage. Use an image element with a source attribute that points to the image file, along with ALT text, width, and height.
**RESPONSIVE WIDTH:** specifying the pixel density like one x, two x, etc., indicate the width of each file: 480w for 480 pixels wide and 960w for 960 pixels wide.
**RESPONSIVE IMAGE:** TO display a small image on a bigger screen you can add attributes like source set or size (piture element).
-use the image element with its ALT text and a URL to the image file.
-wrap this image element with the picture element.
- Within the picture element, list alternative options using the source element.
- first source element, use the source set attribute to point to a mobile image file.
- the other source element, use a kind of media query to specify the image for larger screens.
**FIGCAPTIONS & FIGURES:**
-FIGCAPTION ELEMENT: <figure> <img src="image.pjg"alt="give a depict of your image"width="400"height="300"> <figcaption> add your caption </figcation> <figure>*
-To match an image to a caption. -Show a picture and add a caption to it. - Use the figcaption element to wrap the text and designate it as a caption. -put the image and the caption together in a figure element.
6. **HTML WORKING WITH MEDIA:**
  **WORKING WITH AUDIO:**
-Audio element is different from the Image element because it has opening and closing tags.
-For Audio control you can create them on JavaScript or through HTML media element API.
AUDIO ELEMENT: <audio controls src="audio.mp3"> </audio>
The audio element is an excellent tool for embedding audio files and a player on a webpage.
  **WORKING WITH VIDEO:**
  -video elements has two tags just like the audio element.
  -make the use of source attributes to display videos
  -to specifie multiple fle formats make use of the source element with the appropriate attributes.
  **CAPTIONS & SUBTITLES:**
-use the track element and link it to a text file to add captions to the video.this element will add  functionality to the video player, allowing viewers to toggle captions on and off or switch between different subtitle options.
-The track element it is similar to the source element
-a file format called ibvtt, which stands for web video text tracks, will be used.
-On the track element, use the source attribute to specify the file, the kind attribute to indicate that it contains captions, and a label attribute to display the caption option as "English" in the player
  EMBEDDING MEDIA VIA IFRAMES:
-Embedding refers to taking content from one site and placing it within the middle of another site's page.
-iframe element has attributes like height and width that can be adjusted. The src attribute is used to specify the source of the video file.
-When building a website, also consider security aspects related to the iframe element.*
7. **HTML CONTENT IDENTIFICATION:**
  **LANGUAGE SUPPORT:**
-HTML is equiped with tools to indicate the langauge used in your content, setting the tools correct will enable the search engine to understand the langauge used in your website.
  HTML LANGUAGE ELEMENT:  <html lang="en-US">...</html>
-Lang attribute is used to specify the langauge used on a webpage
-If the whole page is in one language, it is quite simple. Set the language on the main element that wraps everything else, which is usually the HTML element. It may only be required to set it once, like in a template file that applies to the entire site, but do not forget to do it!*
-It is also important to specify the content's direction: <html lang="en-US" dir="ltr">
   **GENERIC ELEMENTS, DIV & SPAN:**
-Div is a block-level element, while span is an inline element. They essentially do nothing until CSS or Javascript is applied to them.
-to add a background color only to the paragraphs, excluding everything else. To achieve this, introduce a div with a class called "boxes". By targeting this box class with CSS, the changes taking effect can be seen.
-If the is a particular phrase in the middle of the text that needs to be specifically targeted use the inline element span to mark the desired phrase.
8.**HTML INTEGRATION:**
  **HTML PAGE:**
     **DOCUMENT HEAD:**
-The HTML head serves as a central hub for connecting and setting up various components, ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way, it is like the headquarters for getting the page off to a good start.
-State important information about your webpage that the browser will need to know about your webpage.
-The character set is not something you want your users to see, it is intended for the browser. To convey this, use the meta element. Ensure that meta elements are only placed inside the head as they provide metadata about the page.
-One common use is to inform the browser that the layout has been adjusted to fit small screens, making it a responsive website. Without this meta tag, the browser assumes the page follows an older layout technique designed for desktops, which needs to be scaled down for mobile devices.
-The script tag is a commonly used element in an HTML document's head. It instructs the browser to load a JavaScript file. Although it is typically placed at the end of the document, some also include it in the head.
 **CONTENT STRUCTURING:6 IMPORTANT ELEMENTS FOR CONTENT STRUCTURING**
-**MAIN:** the main element represents and informs browser about the main content. the main element is used once per page. 
-**HEADER:** Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.
-**FOOTER:**The footer signifies that there are extra things to convey, regardless of its position on the page.
-**ARTICLE:**. The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.
-**SECTION:**The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element.
-**ASIDE:** the aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow. Advertisements can also be marked as an aside
9. **FORMATS & INTERACTIVE ELEMENTS:**
  **FORM FUNDAMENTALS:**
-To create a form, we start with the form element, which informs the browser about the presence of a form using opening and closing tags.
-Use the input element to provide places for users to input their name and email.
-The input element does not have a closing tag due to its older structure. It acts as a marker for the browser to bring in functionality and place it there.
-The insert the button element
-Add "name=name" to the first input element and "name=email" to the second
FORM ELEMENT: <h1>Form</h1>
              <form action="received.html"method="get">
     <div> 
         <label for="name">Name</label>
         <input id="name"name="name"type="text">
     </div>
*create form element for each form section
10. ORGANIZING TABULAR INFORMATION IN HTML:
   HTML TABLES:
-Html tables should be used for tabular data 
TABLE ELEMENT: <table>table</table> used to wrap up the whole table
               <tr>table row</tr>              
               <th>tablehead</th>
               <td>tabledata</td>
**_CSS- INTRO**
Relationship between HTML and CSS is to create a visual aspect of webpages.
1. **COMMENT & ELEMENT SELECTOR:**
CSS Parts [the selector & the declaration block
The CSS selector part: specifies the HTMl pattern if it matches 
The CSS declaration part: are applied to the corresponding HTML elements
It is possible to have multiple styles applied to the same pattern, and that is where the cascading part of CSS comes into play.
The first aspect of CSS is the selector because it is essential to be able to select specific elements in our HTML. to understand the selector you need the ability to undertand the properties & values. 
Selectors in CSS: The first type is the element selector. 
               If we want to select all the paragraphs on our page and make them blue, we can use the HTML element P as the selector
Example: write "P" without the angle brackets and set the color property to blue
to make all the H2s red, for example, we use the selector "H2" in the CSS. Again, we use the color property and set it to red
CSS COMPONENT: selector p { property: value; }
               p{
                  color:red;
                }
2. **CSS COMMENT:**
   /* insert your CSS comment*/
In CSS, comments are written with a slash star and a star slash. You can leave comments for yourself too for reference while writing code. 
   WRITING CLASS SELECTOR:
A **class** is an attribute that can be added to any HTML element, providing additional details about that element.
to turn a paragraph to a different color: add a class attribute to the paragraph tag and give it a name like "intro." 
Use a dot (.) before the class name to differentiate it from HTML element selectors. Write ".intro" and set the color to green.
we can use a span element with a class attribute (Another option)
You do this by adding the span tag with class="guarantee" around that sentence in the HTML. In CSS, we write ".
guarantee" to select that class and set the color to orange and the font-weight to bold.
Style declaration can be place in no particular order
**GROUPING SELECTOR:**
To **group select** insert P (paragraph), li (list) {
                           insert color;
                           }, The web browser will apply this style to all paragraphs and list items, evaluating each one individually.
What about using a class? We can do that too. 
p, li{green;} 
to add color on single word in a paragraph( add that word to the selector 
whenever you see selectors grouped together with commas, it means each of those items is a separate selector. Whether it is paragraphs, list items, or anything with the class 
**DESCENDENT SELECTORS:**
A descendant selector allows us to select list items that are descendants of either an ordered or an unordered list
when applying a style using descendent selector we can write the code without the bodytag.
**Example:**  the space between "OL" and "LI" signifies the descendant relationship, Only the list items that are part of the ordered list will be affected.
CSS selectors that have multiple terms they can be read from right to left, even though we write them from left to right
a single-style declaration means using a series of selectors or just one selector with curly brackets
3. **IDENTIFY A COLOR SCHEME:**
Canvas can be used to edit pictures- gives user different color palettes to choose from. Canva's color palettes also display hex values. Color names and hex values are the most commonly used methods for working with colors on the web.
**FORMATTING COLOR IN CSS:**
After selecting a color palette, the next step is to incorporate it into your code
**HEXADECIMAL CODES:**
only limited colors that have names on CSS, to represent colors online is through **hex codes**, also known as hex values or hex format.
Hex values are typically six-digits long and consist of numbers zero to nine and letters A to F.
The first digits represent the first color and the next two represent another color and the final two represent another color.
**BACKGROUND & TEXT COLOR IN CSS**
to change background in CSSS we can insert the "background-color" property and specifying a hex color, color the background behind specific elements
**UNDERSTADING IMAGES IN CSS:**
There are various image formats, like GIF, PNG, JPEG, bitmap, TIFF, and more proprietary formats like PSD. Traditionally, the web has supported three types of image formats. CSS supports GIF, PNG, JPEG and WebP image formats. 
it is important use the correct format of images, to fast download images resize them to a smaller size by adjusting the dimensions of the image to the required size, trimming or cropping unnecessary parts, and resizing the image.
In HTML, you can use the image element to place an image on the web page alongside the text. These images are crucial for conveying the page's message, such as logos or social media icons. On the other hand, CSS allows you to include background images, which are purely decorative and not essential to the webpage's text. 
**BACKGROUNG IMAGES IN CSS:**
Background images flex and can tile both horizontally (X-axis) and vertically (Y-axis), creating a wallpaper effect. (Defaulft behaviour for Images)
**INSERTING BACKGROUND IMAGE:**
<style> 
h1{ 
 background-image: url(your link) 
}
</style>
(we specify text height, font size, font style (italic & bold), font-family(font name), background, color & alignment(center, left, right,bottom). 
4.**UNDERSTANDING TYPE IN CSS:**
**Two font styles: Serif & San Serif**
**Serif:** fonts have small lines at the ends of the letters called serifs, serifs helped connect the letters, making the text easier to read
**San Serif:** sans serif fonts do not have serifs and have a more modern appearance, sans serif fonts are mainly used on the web for extended text because they look clean and are easy to read.
New times Roman is the default font used on web
**APPLYING TYPE FORMATTING WITH CSS:**
Modification of Fonts: add a font-family property to the body element, the property will allow you to change the fonts on the page. Make use of a font stack, starting with Arial, then Helvetica, and finally Sans-serif. The web browser will evaluate these fonts in order.
**UNDERSTANDING & APPLYIN SIZING IN CSS:**
**Two types of Font Measuring and Size:** Absolute and Relative 
**Absolute sizes**, such as points or pixels, remain the same regardless of the screen size.
**Relative** units like percentages or R-E-M (pronounced "rem") can adjust based on the page size.
According to web developers, the preferred font size unit is usually "rem."
1 rem is equivalent to 16 pixels.  rem can have decimal values
**THE BOX MODEL IN CSS:**
Html elements are like boxes with different properties that are always present even with zero value.
**Two Types of Box Models:** Bolck and Inline Box
Block and inline layout is the default way things behave on the web.
-the type refers to how the box behaves in terms of page flow and in relation to other boxes on the page. Boxes have an inner display type and an outer display type
-HTML elements that uses tthe block box css model are <h1>, <p> 
-HTMl elements that uses the inline box css model are <a>, <span>, <em> & <strong> 
**BORDER:** Sits betweeen the margin and the padding. the size of the border is added to the width and height of the content box. 
**PADDING:** sits between the border and the content. can be controlled by making use of the long-hand properties such as top, bottom, left & right
**MARGIN:** is the visible space arount your content box. can also be controlled through the use of long-hand properties
5. ADVANCED CSS PROPERTIES AND CONCEPTS:
**STYLING LINKS WITH CSS:**
To target links we use the 'a' anchor tag
**INHERITANCE IN CSS:**
**DEBUGGING CSS:**

 
 
**SOTFWARE DEVELOPMENT BOOTCAMP:**
                                                                      JAVASCRIPT BASICS
JAVASCRIPT: It is a scripting language to make your webpages interactive
VARIABLES & DATA TYPE
A variable in JavaScript is a container that holds data values. Variables allow you to store, update, and manipulate information throughout your code.
                                            Declaring Variables:
-var: Can be redeclared & has function scope.
-let: Can be reassigned but not redeclared & has block scope. 
-const: Can not be redeclared nor reassigned, it has the block function which can be used for values that should not change.
                                            DATA TYPES:
-Numbers: Refers to the use of numeric values.
-Strings: Refers to the sequence of characters to represent a text.
-Booleans: Mainly used in conditions & logical operations (true or false).
-Arrays: Refers to the use of list of values that can be different types of data stored in single variable. 
-Objects: Complex data structures that can hold multiple values and functions (methods) as properties.
                                           OPERATORS & EXPRESSIONS:
Operators: are building blocks of expression in JavaScript, they are made of symbols or keywords used to perform operations on values.
                                             TYPES OF OPERATORS:
-Arithmetic Operators: Are used for mathematical caculations. Arithmetic operators refers to mathematical signs used when calculating (+; -; x; % & *).
-Assignment Operators: Are used to assign values to variables. = (assign), += (add and assign), -= (subtract and assign), *= (multiply and assign), /= (divide and assign).
-Comparison Operators: Are used to compare values & return a boolean (true or false). == (equal), != (not equal), === (strict equal), !== (strict not equal), > (greater than), < (less than), >= (greater than or equal to), <= (less than or equal to).
-Logical Operators: Are used to combine multiple conditions. && (AND), || (OR), ! (NOT).
-Unary Operators: They operate on single operand. 
-Ternary Operator: Refers to the short-hand of if-self statement. ++ (increment), -- (decrement), typeof (type of operand).

EXPRESSIONS: refers to the combination of values, variables & operators that evaluates to a single value. Expressions can be simple or comples.
                            TYPES OF EXPRESSIONS:
ARITHMETIC EXPRESSION: Makes use of Arithmetic operators to perform calculations.
COMPARISON EXPRESSION: Makes use of comparison operators to evaluate conditions.
LOGICAL EXPRESSION: Makes use of multiple conditions using logic operator.
                           CONTROL STRUCTURE (if-else,switch)
"if the condition returns **true**, run code A, **else** run code B"
                           1. if-else statement:
if-else: it is an important control structure that puts a block of codes if a specified condition is true.
We use the if-else statement when there are multiple conditions to evaluate, with different outcomes depending on the which confitions are true.
                              STRUCTURE:
if Block: Executes if the condition is true.
else if Block: it is optional, it evaluates if the first condition was false.
else block: when the previous conditions are not met else block executes.
                          2. Switch Statement:
Switch: it is a control structure that can be used to executing one block of code among many based on the value of an expression.
                            STRUCTURE:
switch keyword: analyse expressions if they match with one of the case labels
Case labels: 
Break statement: 
Default case: 
                              FUNCTIONS & SCOPE:
                                     FUNCTIONS:
Function refers to a block of codes that are designeted to perform a spefic task, those block of codes can be reused by coders. 
                                  FUNCTION DECLARATION:


                                        SCOPE:
.Determines the visibility of variables within a code (how accessibly are the variables in different parts of the code).
.Scope serves as enviromment for variables to be layed on (that variables can be declared & accessed on). 
                                     TYPES OF SCOPE:
 .Global scope: Serves as the widest scope in Javascript, variables declared in global scope can be acessed anywhere in your code
 .Local scope: Visibility of variables are limited in local scope, variables can only be accessed within where they are declared
 .Function scope: Each function creates a new scope & a variable declared within a function can only be acessible in that function.
 .Block scope: serves as a large container with nested boxes, each box with its sets of variables, variables declared on block scope can not escape to outer scpes.
 .Hoisting: Refers to the behaviour which affects functions and variables in Javascript
 GLOBAL SCOPE
 -Mainly used for variables declared outside functions
 LOCAL SCOPE
 -used for variables declared inside functions
                                  SELECTING & MODIFYING DOM:
                                      1. DOCUMENT OBJECT MODEL:
Document Object Model is basically a bunch of HTML elements nested inside each other. This nesting creates a tree structure, like a family tree with parents, children, and siblings. The browser pays attention to this structure and builds a big family tree that shows how everything is related. To big Family tree that is called the DOM (Document Object Model). 
JavaScript can be used to manipulate your Html content by updating content and the appearance of a webpage.
                                    2. SELECTING DOM ELEMENTS:
 Refers to targeting specific HTML elements to manipulate with Javascript.
                                  METHODS TO SELECTING DOM ELEMENTS:
 .getElemenyById
 .getElemenByClassName
 .getElements ByTagNames
 .querySelect
 .querySelectAll
                                     3. MODIFYING DOM
  Refers on varies ways that can be used to modify DOM elements by changing style, content, attribute & structure once you have selected your elements.
                                    COMMON MODIFICATIONS:
  .Changing content
  .Changing style
  .Adding/Removing classes
  .Changing attributes
  .creating & inserting elements
                         EVENT HANDLING:
                 1. JAVASCRIPT EVENTS:
Events refers to occurrence (actions) to html elements.
                 2. EVENT LISTENERS:
Refers to functions that act once certain events occurs. 
                 ATTACTING EVENT LISTENERS:
.addEventListener
.in line event handler
                 3. COMMON EVENT TYPES
.Mouse event
.Keyboard event
.Form events
.Document/window events
                 4. EVENT OBJECT
EVENT OBJECT:
                CREATING & REMOVING ELEMENTS DYNAMICALLY:
                 1. CREATING ELEMENTS DYNAMICALLY:
Refers to the creation of new HTML element using Javascript, elements that can be addded to the DOM.
                   STEPS TO CREATE ELEMENTS
.create elements
.Set attributes/ content
.Append to the DOM
                2. REMOVING ELEMENTS DYNAMICALLY:
Refers to deleting existing elements using Javascript.
                    METHODS TO REMOVE ELEMENTS:
.removeChild
.remove
               3. PRACTICAL APPLICATIONS:
 .Adding dynamic content
 .Interactive UI elements
                                                      ADVANCED JAVASCRIPT
 .INTRODUCTION TO NODE.js
 serves the side server version of Javascript, allows you to add more interactive functional to your webpages
 .JAVASCRIPT & NODEs
 
                            PROS OF JAVASCRIPT
 -javascript is advanced with speed
 -has simple syntax 
 -front and back end code and language can be shared (versatality).
                              CALLBACKS & ASYNCHRONOUS TAKS:
                                       CALLBACKS:
 -Refers to a function that is passed as an argument to another function, and then called in that function to perform a task.
 -Callbacks allow you to perform Asynchronous programs in Javascript
 -Callbacks are mainly used in event handling scenarios, making API & when sending a file through Asynchronous programming.
 -Callbacks serve to make it easy to control and manage your Asyncronous program
                                      CALLBACK HELL:
 -Refers to a problem that you may run into while running multiple Asynchronous tasks with callbacks
                                    SYNCHRONOUS TASKS:
-It is a programming technique that allows you to run one task per time, begins with new task once the first one finishes up
                                    ASYNCHRONOUS TASKS:
-It is a programming technique llows you to run multiple task, without waiting for the first one to finishes up
-Makes your Javascript program runs fast
                                      
                                      ES6-FEATURES
 
Block-scope Variables 
FUNCTION FOR BLOCK-SCOPE VARIABLES
-Helps to avoid variable leakage & makes it easy to debug.
1. Let & Const
-allow you to declare variables that are visible to the block instead of the entire function or global scope
2. ARROW FUNCTIONS
-CONCISE SYNTAX
.If creating a function you must make use of the function keyword
-LEXICAL this
3. TEMPLATE LITERAL
-refers to the use of backsticks to denote strings  (````) not quotation marks
                                       EXAMPLE OF TEMPLATE LITERAL:
// Using template literal
const str2 = `Hi ${userName}, your balance is ${balance}.`
console.log("Template literal: ", str2)
                                     ASYNCHRONOUS JAVASCRIPT
1. CALLBACKS:
   Refers to a function that is passed as an argument to another function, and then called in that function to perform a task.
   **Arguments** are values (primitive or object) passed as input to a function. Do not confuse arguments with parameters, which are the names used in the function definition to refer to the arguments.
2. PROMISES:
   Refers to an object that reppresent the eventual completion of Asynchronous expression
   They allow you to chain operations
         STATE OF PROMISE:
.PENDING: initial state 
.FULLFILLED: operation successful
.REJECTED: operation failed
        CHAINING:
.then () & .catch ()
        ADVANTAGE;
-promises improve your code readability
-To avoid Callbacks Hell make use of PROMISES
3. ASYNC/AWAIT
-Are built on top of promise
       USAGE:
   ASYNC: Used to declare a function that returns a PROMISE
   AWAIT: Used inside the ASYNC function to pause the execution until the promise is successful or rejected, making code appear linear.
           ADVANTAGE:
-helps to easily manage code errors.
4.WHY ASYNCHRONOUS MATTERS ON JAVASCRIPT:
-Javascript it is a single-thraded language meaning it can only handle one opertion at a time.
   NON-BLOCKING CODE:
   -Asynchronous operations allow Javascript to perform multiple operations or concurent operatioons. 
   SCALABILITY
   -it is adviceable to make use of Asynchrnous patterns (callbacks,promises,Async & Await) to build scalable applications that can handle multiple tasks.
   MODERM JAVASCRIPT DEVELOPMENT
   -
         ERROR HANDLING (TRY-CATCH)
   -Error handing allows you manage and handle unexpected errors during code execution.
                          try-catch statement
   -provides a structured way to handle errors
   -can only catch errors in synchronous code because it is a Synchronous block
                     TRY
   -
    CATCH
   -
   1. IMPORTANCE OF ERROR HANDLING:
             ROBUST APPLICATION:
   -Error handling helps you to create uder-friendly applications
             DEBBUGING & MAINTENANCE
   -Error handling helps in debuing and maintaining code
   2. The try-catch statement
                  STRUCTURE:
      -allows you to test a block of codes for errors
                   SYNTAX:
       try {
       // code that may throw error
      } Catch (error) {
      // code to handle the error
      } finally {
      // code that runs regardless of the outcome
      }
 3. try-catch up in action:
    try Block
    try Statement
    catch Block
    finaly Block
 4. COOMON USES CASES FOR try-catch:
    HANDLIN EXTERNAL SOURCES:
-

     REACT BASICS:
-React it is a Powerful Javascript library used to build dynamic and interactive user nterfaces (UI).
-react is built around the concept of components.
-JSX (JavaScript XML)is the syntax used within React to describe what the User Interface (UI) should look like.

1. UNDERSTANDING COMPONENTS:
   -Refers to a self-contained  piece of code that represents part of the User Interface.
COMPONENTS CAN EITHER BE: 
   -functional components:
   -class-based components:

TWO TYPES OF COMPONENTS:
    <Presentational Coponents: pays attention on how things look like.
    <Container Compoents: pays attention on how things work.

2. UNDERSTANDING JSX
   -It a syntax extention for JavaScrip  used within React, it looks similar to HTML
   -Makes it easy to visualise the structure of the UI
                  WHY USE JSX?
   -JSX is Decaractive, it allows you to write declaractive and clean code making it easy to understand the UI structure.
   -

3. WRITING COMPONENTS WITH JSX

PROPS & STATE:
-are core concepts that manages your data flow and interactivity within your application. 
1. UNDERSTANDING PROPS
   <Props is short for Properties
   <are used to pass data from one cmponent to another, typicaly from a parent component to a child component
2. UNDERSTANDING STATE:
   <its a build-in object that allows component to create & manage their own data.
   <state is used for data that changes, form inputs are example of data that changes.
3. PROPS vs. STATE:
   PROPS
   <allows data to pass from one component to another
   <are immutable (read-only)
   
   STATE:
   <Allows components to create & manage data within.
   <are mutable (changes).
4. Best practices to uses PROPS and STATE:
   -
   -

ADVANCE REACT:
  COMPONENTS IFECYCLE METHODS: 
 -React compoonents go through a series of phase during their existence, form creation to destruction.
 1. UNDERSTANG THE COMPONENT LIFECYCLE:
    -LIFECYCLE PHASES:
    <MOUNTING PHASE: Components are created and inserted to the DOM
    <UPDATING PHASE: Components are rerendered due to the changes in PROPS and STATE
    <UNMOUNTING PHASE: Components are removed and the DOM cleaned up
2. KEY LIFECYCLE METHODS:
   1. MOUNTING PHASE:
   2. UPDATING PHASE:
   3. UNMOUNTING PHASE:
3. LIFECYCLE METHODS IN FUNCTIONAL COMPONENTS:
   -React Hooks
   -Using UseEffect
4. BEST PRACTICES FOR LIFECYCLE METHODS:
   -Avoid side effects in render()
   -


REACT HOOKS (useState, useEffect)
- React Hooks arefunctions that allow you to use state and React features in functional components.
  1. INTRODUCTION TO REACT HOOKS
     -WHAT ARE HOOKS?
     <Hooks allow you to manage state, perform side effects and much more without converting your functional components to classes.
     -WHY USE HOOKS?
     <Simpler code: they reuce the need for boilerplate code
     <Reuse logic: allows you to use stateful logic across components without creating duplicate code.
 2. useState: Managing State in functional Coponents
    -What is useState?
    <it is a Hook that lets you ad state to functional components.
    -How useState works?
    <You initialize state by calling useState & passing the initial state value.
3. useEffect: Handling side effect on functional components
   -What is useEffect?
   <it is a Hook that lets you perform side effects in functional components. Side effects such as data fetching, subscriptions and manually updating the DOM.
   -How useEffect works?
   <
4. Best practices for useState & useEffect
   -
   -

ROUTING WITH REACT ROUTER:
1. INTRODUCTION TO REACT ROUTER
   -WHAT IS REACT ROUTER?
   <it is a powerful library used for managing navigation & routing in React Applications. it enables you to define different routers in your application.
   -WHY USE REACT ROUTER?
   <React Router allows you to build a Single Page Application (SPA)
   <Routes are defined as components
2. SETTING UP REACT ROUTER:
   -Installation
   -Key Components
3. NAVIGATING BETWEEN ROUTERS:
   -Using the link component
4. DYNAMIC TOUTING:
   -Using URL parameters
   -Nested Routes
5. BEST PRACTICES FOR USING ROUTER
   -Organize Routes clearly
   -Use nested Routes wisely
   -Error Handling
   

                                            PYTHON BASICS:
  












