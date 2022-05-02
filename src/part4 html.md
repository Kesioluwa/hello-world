# Part 4
- Learn basic html syntax
- html tags (h1, heading tags), (p, paragraph tags), (a, link tags), (img, image tags)
- html tag attributes (target, href; specific to links), (class and id; used in css and javascript for identifying places where you want to put styling or animation), NOTE: a class can be used in many places within the same document but you can only use an id once. 
- html metatags

Every website in the world has a structure

## Assignment
 - give every heading a color
 
 Status: Done

 ## Lists
- ul- unordered list
- ol- ordered list
- li- list item (to be "nested" inside ul or ol)
- to duplicate a line we use "shift + alt + down arrow"

 "a" - tag used to create a hyperlink to go to another page

 - "img"-Image elements do not have an opening or closing tags, "img" is used to open an image reference
 - "src"- Source attribute, allows you to locate an image or document that you want to insert into your html file by using the  symbol "/"

 ## Comments in HTML
 A  comment in html is used to hide text that you dont want to be visible on the main browser. it's symbol is <!-->
and its shortcut is "ctrl + /" to comment an entire line, it can be used as a reminder of something you feel you might forget while coding or to indicate something important for yourself.

## Next steps in html
- HTML5 - HTML5 is simply the latest evolution of the standard that defines html. It doesnt necessarily mean html 5 is the highest level of html at that present time, it just means that is the best level that html is currently at, it doesnt mean there are other html's before it like in games or movies where we have part 1,2,3 and so on, it just simply means that this is where html is presently at. 

Visit "html.spec" for more information about html attributes
## Quick Assorted elements
- "div"- content divider element, it is used to group content together, it is a block element, which means it is used to group a few texts or a group of texts and buttons and images into one huge block or line, it's basically used to put a lot of stuff together in a block
- "span"- it is a way of calling a text opr character out of its main line so that it can be styled differntly, style meaning adding color or italics or bold to the text, span is used to do that
- "hr"- it is literally just used to draw a horizontal line on your website, like a divider sort of thing
- "br"- it makes a break in your line of content, consider it a mini paragraph.. A paragraph is used to seperate huge chunks of content, but a break "br", is used to seperate tiny tiny content instead of abusing the paragraph "p", attribute.
- "sup" and "sub" - simply means to have a superscript or subscript in your content or text 

## HTML ENTITIES
 they are special codes that we can use in html that will result to different characters. they start wth the "&" and end with ";"
 - you can use entity codes for characters such as < and > to avoid messing with the hhtml code which is normally used to making use of those brackets when indicating an element of some sort
 for example the entity code of < is &lt; and the entity code for > is &gt;. Check "entitycode.com" for more

 ## Semantic Markup
 - Means a markup that is related to the meaning of that markup
 Instead of DIVS we can make use of;
 - < section > - supposed to represent a section part of a website
 - < article > - any self contained composition, also used to group content together
 - < nav > - to represent anything on the page that provides navigation links
 - < main > -  it should be the main or dominant content of your page and should exculde any content that will be repated accross the page
 - < header > - used to indicate any sort of introductory content and navigation panels
 - < footer > - used to indicate any nested information or navigation panels at the BOTTOM of the website
 - < aside > - used to identify a part of the document thats not so essential, like sidebars, or notes or bonus topics
 - < summary >
 - < details >
 - < time > - an inline element that is wrapped around some piece os content containing a time, usually wrapped inside a < datetime > markup.
 < fig > - used to call attention to some sort of mini image or picture often with a caption instead of just using the div
 