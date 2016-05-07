# Lesson 2

Here is the very basic, and first steps as a web developer.

Student needs to understand why HTML and why CSS ? Each one is in order to help solving different problems.

Is important to separate things here in order to see when facing a problem which is the one to be used and why.

HTML Structure content page.

CSS Styling content.

## Intro HTML (Hyper text markup language)

Bring to light some example out of the computer, like a newspaper.

Talk about newspaper content disposition and frames. We can say that if we have to create this newspaper, we need to think on some sort of Structure regarding the frames and content we need inside it.

When we create this newspaper in HTML we see that there is a relation ship between the content and the container. We can talk about child nodes, parent nodes, siblings nodes too.

Every time we write a new HTML page we can see that the first line is a declaration of the document type we will be parsing. So if we need to see definitions about HTML we should go to the correct resource of the HTML page defined.

Warn the student about adding child nodes on nodes that are prepared to receive an html node. Also speak about HTML text Node, which is implicit to the writing of text.

Mention that we add a link to the html in a page in order to apply styles to the page. And we do so in the head tag of the html.

What is an element, and attribute? HTML Semantics, sections vs divs and article, aside and HTML5 tags. Explain also about aria-label attributes and alt for images.

We can see that some of the different HTML tags have some styling by default.

## Intro to CSS (Cascading style sheets)

Start with the need of making that newspaper look great.

We need to add colors, background. So how can we do so? We need some sort of reference to what we want to make look good.

In order to do so we can explain CSS selectors to reference the document and add our styling rules.

Explain types of selectors on CSS breafly:

\* for any element

tagName in order to select all elements in page with a certain tag name.

tagName[foo] for selecting any element with an attribute foo. Explain that there are other attribute selectors like foo=val foo~=val foo|=val foo*=val foo^=val foo$=val.

tagName:nth-child(n) select the tagName child "n"

tagName:hover taName:focus as examples.

tagName::first-letter ::before as pseudo-element selectors.

tagName.className as a selector of a tag with a certain class.

tagName#id as a selector of an element with a certain ID.

### Combining selectors and Grouping selectors.

Explain > "," and combinations of tags and/or classes.

### Pseudo classes

Sometimes we need to reference or select something that lies outside of the document tree or by simple selectors. So the concept of pseudo class consists on selecting this cases. We can see examples of pseudo classes like :link :visited :hover :active :focus etc...

Some of this pseudo classes are inclusive and in other cases they are mutually exclusive.

### Pseudo elements

This are in order to create abstractions beyond specified by the document language. For example the first line of a paragraph, first letter of a paragraph. Also can be used to work with content before of after the current node.

::first-line ::firt-letter ::before ::after.

Bring some examples here.

### Others combinations

Working with siblings with + or using > for the first childs of a certain selection.

## Goal

Student to work on a simple page.
