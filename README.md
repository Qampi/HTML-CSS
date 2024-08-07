HTML- INTRO
html serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences.
html makes use of tags to mark different elements
HTML is all about recognizing commonly used elements such as paragraphs, headings, lists, and links that define the structure of a webpage.
attributes provide a way to name HTML elements and reference them in other parts of the code stack.  Other attributes in HTML have various functionalities,other attribute allows visitors to edit the content on a web page. HTML attributes facilitate the editing capability within the browser.
ARIA Roles are extra attributes that can be added to HTML elements to convey the message more meanigful.
to create a link make use of the 'A'element which stans for ánchor'- we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference
to create a URL that is relative to the root level it needs to start with '/' can be known as absolute URL. a URL that is relative to the location of the file start it with ..- goes to one level which is the one mentioned on the URL. can be known as relative URL. 

CSS- INTRO
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

