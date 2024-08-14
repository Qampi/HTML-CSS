HTML- INTRO
html serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences.
html makes use of tags to mark different elements
HTML is all about recognizing commonly used elements such as paragraphs, headings, lists, and links that define the structure of a webpage.
attributes provide a way to name HTML elements and reference them in other parts of the code stack.  Other attributes in HTML have various functionalities,other attribute allows visitors to edit the content on a web page. HTML attributes facilitate the editing capability within the browser.
ARIA Roles are extra attributes that can be added to HTML elements to convey the message more meanigful.
to create a link make use of the 'A'element which stans for ánchor'- we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference
to create a URL that is relative to the root level it needs to start with '/' can be known as absolute URL. a URL that is relative to the location of the file start it with ..- goes to one level which is the one mentioned on the URL. can be known as relative URL. 
THE FUNCTION OF HTML:
HyperText Markup Language, is responsible for marking up the content of a website. It informs the user's computer about various elements on the page.
Cascading Style Sheets, is like the stylist of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.
2. HTML TEXT FORMATING:
HTML SYNTAX: (HTML Paragraphs) 
Html uses tags, which are enclosed in less-than and greater-than symbols, to mark different elements. Tags come in two types: opening tags and closing tags. For example, the opening tag for a paragraph is <p>, and the closing tag is </p>. 
Html tags work together to define elements, which are like packages containing content. Some elements, like paragraphs, require both an opening and a closing tag, while others do not.
There is another phrase that is emphasized, which we have turned into a separate element by using opening and closing em tags. Example of a paragraph that has emphasised elements: <p> <em> for effect </em> </p>. 
HTML document is basically a bunch of HTML elements nested inside each other. This nesting creates a tree structure, like a family tree with parents, children, and siblings. The browser pays attention to this structure and builds a big family tree that shows how everything is related. To big Family tree that is called the DOM (Document Object Model). 
HTML HEADLINES: 
(HTML Headlines) elements serve the purpose of dividing content into smaller, more digestible chunks. They help people to comprehend the structure of the comtent. These elements also convey a sense of hierarchy in how the browser interprets and communicates about the page.  
The HTML elements used for marking up headlines come in six different types: h1, h2, h3, h4, h5, and h6. When viewed in a browser, each headline has a distinct visual effect. These elements also convey a sense of hierarchy in how the browser interprets and communicates about the page. 
This hierarchical system of headlines gives meaning to the browser, distinguishing what is most important from what is less important. It also ensures that all article headlines share the same type, h2, which is crucial for screen reader users who rely on consistent hierarchical information to navigate the page. 
HTML BOLD & ITALICS: 
There are four HTML elements related; two for Bold and two for Italics
Two different elements to convey this distinction for ITALICS. We use the "<i>" element to apply visual italics and the "<em>" element to add emphasis.
two different elements for Bold: "<strong>" element, which is used to show importance, seriousness, or urgency. the "<b>" element is more generic and neutral,  It does not carry any specific meaning; it simply allows us to make something bold visually and does not imply any alternative voice or mood.
HTML LISTS:
 In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. Each item in the list is enclosed in an <li> element, which represents a list item. To define the entire list and specify its type, we wrap all the items in a <ul> element, which stands for an unordered list. The term "ol" stands for ordered list. <dt> stands for definition term, <dd> tag stand for definition description is used for doe definition list.
 You can have multiple descriptions for each term by using multiple  tags. The entire list is wrapped in a  <dd>tag, representing the definition list. Interestingly, the <dd> tags and <dt> tags are placed side by side without any additional wrapper around them. This is simply how a definition list is structured.
 HTML QUOTES: 
<cite> & <blockquote> elements serve a semantic purpose to inform other computers.
We can use the "<q>" element in HTML, which stands for quote. By using this element, the browser will automatically provide the appropriate quote marks for us.
Some HTML elements, like <strong>, <b>, <I>, and <em>, are called "inline" because they are meant to wrap around phrases of text that are inline with other content. They serve a similar purpose as the "<q>" element.
Some Elements in HTML known as block-level elements, like block quotes, paragraphs, and unordered lists. These elements essentially create separate blocks on the page. You can think of them as standalone entities that can be followed by another block.
Datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this: <time datetime="2025-05-08">May 8, 2025</time>.
HTML DATE & TIME INPUT:
To insert HTML time tag (<time>) and a closing tag (</time>). For example, we can use it like this: <time>May 8th</time> or <time>May 8th 2025</time>, depending on how we prefer to write dates.
The main purpose of the <time> element is to convey the exact date or time to computers.
HTML CODE, PRE & BR:
To add a Code syntax; ut an opening code tag before the CSS snippet and a closing code tag afterward. (code) (</code)
_HTML ENTITIES: "&LT;" & "&GT;" 
When we type "&lt;", it will be displayed as a less than sign. Similarly, typing "&gt;" will show a greater than sign. 
hese entities are formatted like this: an ampersand, a short code, and a semicolon. When we include them in an HTML file, they are converted into the specific characters we want. We applied this technique to replace every instance of greater than or less than symbols with their corresponding character entities. 
br element: (mostly used in poems)
The br element is a simple tag without an opening or closing tag. It does not contain anything inside it; it just indicates where a line break should happen.
pre element: 
It is mostly used in peoms that have irregular spacing.  Wrap the poem in pre tags, and now you can see that the browser respects the spacing, line breaks, and everything else. We can even insert a random character anywhere, and it will stay exactly where we put it.
HTML SUPERSCRIPTS, SUBSCRIPTS & SMALL TEXT: 
Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest. Subscripts are characters that are set below the normal baseline for text. Superscripts are characters that are set above the normal baseline of text. 
Superscripts: <sup> insert your text </sup> 
Subscripts:  <sub> insert your text </sub> 
Small text: <small> insert your text </small> 
3. HTML CAPABILITIES:
TROUBLESHOOTING & DEBUGGING HTML CODES:
HTML ATTRIBUTES:
The four most important Global Attributes: "class," "id," "lang," and "dir." You can find a comprehensive list of all the Global Attributes on MDM web docs.
The Class Attribute: allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class.
The ID Attribute: It is similar to the class attribute, but we can only use unique names once on an entire HTML page. IDs can be used for CSS targeting, but are more specific, which can sometimes cause issues. 
The lang Attribute: allows us to specify the language of the content using a short language code.
The dir Attribute: explicitly indicates the direction in which the text flows, using "LTR" for left-to-right scripts and "RTL" for right-to-left scripts. 
ARIA ROLES:
ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible. 
FORMATING HTML:
In HTML, comments are inserted by typing "<!--" at the start and "-->" at the end.
UNUSUAL CHARACTERS:
to insert a non-breaking space between the two names, ensuring they stay on the same line-  use the code "&nbsp;"
"&lt;", it will be displayed as a less than sign. Similarly, typing "&gt;" will show a greater than sign.
4. HTML NAVIGATION & LINKING 
HTML LINKS:
To create a web we use the A element which stand for Anchor;  To do this, we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference.  Between the opening and closing A tags, we can place text or images, or both, to make them clickable. By default, the A element is inline and can be placed within a paragraph or any other text.
The difference between HTTP and HTTPS. The "S" in HTTPS stands for Secure. 
HTML URL PATHWAYS:
To create a relative URL, omit the domain name but include the initial slash at the beginning. The slashes in a URL indicate that we should look deeper into the file structure or go one level down.  This tells the browser to start from the root level of the file structure, which is the outermost top level. Alternatively, we can write the path to be relative to the file where the link is written. 
/images/logo.gif 
../images/logo.gif
The first version, /images/logo.gif, creates a URL that is relative to the root level. It means the browser will start looking for the file from the root of the website. 
The second version, ../images/logo.gif, creates a URL that is relative to the location of the file where the URL is written. The ".." followed by a slash means going up one level in the directory structure.
The URL ../images/logo.gif means starting from the current location, go up one level, find the folder named images, and then look inside it for the file logo.gif.
RELATIVE URL vs ABSOLUTE URL:
Relative URLs are based on the current file's location, while absolute URLs start from the root of the website.
NAVIGATION: 
creating a menu for a website: 
-wrap each link with the correct element 
-then enclosed in an "li" element to create a list of links
-Finally, encompass the entire menu in a "nav" element to indicate that it is the site's navigation.
-To give the menu a visual appearance, apply CSS styling.
-add some attributes to convey its purpose
-Assign the role "navigation" to the "nav" element, which signifies that it represents the main navigation of the page
-include an "aria label" for the main menu, providing a descriptive label that can be read aloud by a screen reader. 
5. HTML WORKING WITH GRAPHICS & IMAGES:
IMAGES: 
There are four ways to include when inserting Image in a Website
- The source attribute (SRC), which tells the browser which image file to load. (paste the Image URL into the source attribute) 
- The alt attribute (ALT), which provides a text description of the image. (serves as a replacement for the image when it cannot be seen as Description of whats in the Image, just focus on what it depicts). 
- The width and height attributes, which determine the size of the image.
IMAGE FORMATS:
when uploading an Image file on a website it needs to be in a certain file format, a format that web browsers can understand.
MAIN FILE FORMATS:
  -GIF:are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs. It only supports 256 colors, and images can end up looking pixelated.
  -SVG:is a vector file that contains instructions for drawing rather than individual pixels, are perfect for logos, icons, and other types of illustrations.
  -JPG:a popular choice for compressing photographs, it is important to resize and compress them appropriately when placed websites. 
  -PNG:is a newer format that works well when you need transparency in a photograph
RESPONSIVE IMAGES:HTML allows us to deliver different image files to screens of different sizes. We can create multiple image files and include them as options in our HTML code.starting with the basic code for loading an image on a webpage. Use an image element with a source attribute that points to the image file, along with ALT text, width, and height.
RESPONSIVE WIDTH: specifying the pixel density like one x, two x, etc., indicate the width of each file: 480w for 480 pixels wide and 960w for 960 pixels wide.
RESPONSIVE IMAGE:TO display a small image on a bigger screen you can add attributes like source set or size (piture element). -use the image element with its ALT text and a URL to the image file. -wrap this image element with the picture element. - Within the picture element, list alternative options using the source element. - first source element, use the source set attribute to point to a mobile image file. -he other source element, use a kind of media query to specify the image for larger screens.
FIGCAPTIONS & FIGURES:
-To match an image to a caption. -Show a picture and add a caption to it. - Use the figcaption element to wrap the text and designate it as a caption. -put the image and the caption together in a figure element.
6. HTML WORKING WITH MEDIA:
  WORKING WITH AUDIO:
-Audio element is different from the Image element because it has opening and closing tags.
-For Audio control you can create them on JavaScript of through HTML media element API.
AUDIO ELEMENT: <audio controls src="audio.mp3"> </audio>
The audio element is an excellent tool for embedding audio files and a player on a webpage.
  WORKING WITH VIDEO:
  -video elements has teo tags just like the audio element.
  -make the use of source attributes to display videos
  -to specifie multiple fle formats make use of the source element with the appropriate attributes.
  CAPTIONS & SUBTITLES:
-use the track element and link it to a text file to add captions to the video.this element will add  functionality to the video player, allowing viewers to toggle captions on and off or switch between different subtitle options.
-The track element it is similar to the source element
-a file format called ibvtt, which stands for web video text tracks, will be used.
-On the track element, use the source attribute to specify the file, the kind attribute to indicate that it contains captions, and a label attribute to display the caption option as "English" in the player
  EMBEDDING MEDIA VIA IFRAMES:
-Embedding refers to taking content from one site and placing it within the middle of another site's page.
-iframe element has attributes like height and width that can be adjusted. The src attribute is used to specify the source of the video file.
-When building a website, also consider security aspects related to the iframe element.*
7. HTML CONTENT IDENTIFICATION:
  LANGUAGE SUPPORT:
-HTML is equiped with tools to indicate the langauge used in your content, setting the tools correct will enable the search engine to understand the langauge used in your website.
  
_CSS- INTRO
Relationship between HTML and CSS is to create a visual aspect of webpages.
1. COMMENT & ELEMENT SELECTOR:
CSS Parts [the selector & the declaration block
The CSS selector: part specifies the HTMl pattern if it matches 
The CSS declaeation part: are applied to the corresponding HTML elements
It is possible to have multiple styles applied to the same pattern, and that is where the cascading part of CSS comes into play.
The first aspect of CSS is the selector because it is essential to be able to select specific elements in our HTML. to understand the selector you need the ability to undertand the properties & values. 
Selectors in CSS: The first type is the element selector. If we want to select all the paragraphs on our page and make them blue, we can use the HTML element P as the selector
Example: write "P" without the angle brackets and set the color property to blue
to make all the H2s red, for example, we use the selector "H2" in the CSS. Again, we use the color property and set it to red
In CSS, comments are written with a slash star and a star slash. You can leave comments for yourself too for reference while writing code.
2. A CLASS SELECTOR:
A class is an attribute that can be added to any HTML element, providing additional details about that element.
to turn a paragraph to a different color: add a class attribute to the paragraph tag and give it a name like "intro." 
Use a dot (.) before the class name to differentiate it from HTML element selectors. Write ".intro" and set the color to green.
we can use a span element with a class attribute (Another option) You do this by adding the span tag with class="guarantee" around that sentence in the HTML. In CSS, we write ".guarantee" to select that class and set the color to orange and the font-weight to bold.
Style declaration can be place in no particular order
GROUPING SELECTOR:
To group select insert P (paragraph),  li (list) {insert color;}, The web browser will apply this style to all paragraphs and list items, evaluating each one individually. What about using a class? We can do that too. 
p, li{green;} 
to add color on single word in a paragraph( add that word to the selector 
whenever you see selectors grouped together with commas, it means each of those items is a separate selector. Whether it is paragraphs, list items, or anything with the class 
DESCENDENT SELECTORS:
A descendant selector allows us to select list items that are descendants of either an ordered or an unordered list
when applying a style using descendent selector we can write the code without the bodytag.
Example:  the space between "OL" and "LI" signifies the descendant relationship, Only the list items that are part of the ordered list will be affected.
CSS selectors that have multiple terms they can be read from right to left, even though we write them from left to right
a single-style declaration means using a series of selectors or just one selector with curly brackets
3. IDENTIFY A COLOR SCHEME:
Canvas can be used to edit pictures- gives user different color palettes to choose from. Canva's color palettes also display hex values. Color names and hex values are the most commonly used methods for working with colors on the web.
FORMATTING COLOR IN CSS:
After selecting a color palette, the next step is to incorporate it into your code
only limited colors that have names on CSS, to represent colors online is through hex codes, also known as hex values or hex format. Hex values are typically six-digits long and consist of numbers zero to nine and letters A to F. the first digits represent the first color and the next two represent another color and the final two represent another color.
BACKGROUND & TEXT COLOR IN CSS
to change background in CSSS we can insert the "background-color" property and specifying a hex color, color the background behind specific elements
UNDERSTADING IMAGES IN CSS:
There are various image formats, like GIF, PNG, JPEG, bitmap, TIFF, and more proprietary formats like PSD. Traditionally, the web has supported three types of image formats. CSS supports GIF, PNG, JPEG and WebP image formats. 
it is important use the correct format of images, to fast download images resize them to a smaller size by adjusting the dimensions of the image to the required size, trimming or cropping unnecessary parts, and resizing the image.
In HTML, you can use the image element to place an image on the web page alongside the text. These images are crucial for conveying the page's message, such as logos or social media icons. On the other hand, CSS allows you to include background images, which are purely decorative and not essential to the webpage's text. 
BACKGROUNG IMAGES IN CSS:
Background images flex and can tile both horizontally (X-axis) and vertically (Y-axis), creating a wallpaper effect. (Defaulft behaviour for Images) 
4. UDERSTANDING TYPE IN CSS:
Two font styles: Serif & San Serif
Serif: fonts have small lines at the ends of the letters called serifs, serifs helped connect the letters, making the text easier to read
San Serif: sans serif fonts do not have serifs and have a more modern appearance, sans serif fonts are mainly used on the web for extended text because they look clean and are easy to read.
New times Roman is the default font used on web
APPLYING TYPE FORMATTING WITH CSS:
Modification of Fonts: add a font-family property to the body element, the property will allow you to change the fonts on the page. Make use of a font stack, starting with Arial, then Helvetica, and finally Sans-serif. The web browser will evaluate these fonts in order.
UNDERSTANDING & APPLYIN SIZING IN CSS:
Two types of Font Measuring and Size: Absolute and Relative 
Absolute sizes, such as points or pixels, remain the same regardless of the screen size.
Relative units like percentages or R-E-M (pronounced "rem") can adjust based on the page size.
According to web developers, the preferred font size unit is usually "rem."
1 rem is equivalent to 16 pixels.  rem can have decimal values
THE BOX MODEL IN CSS:
BORDER, PADDING & MARGIN IN CSS:
5. ADVANCED CSS PROPERTIES AND CONCEPTS:


