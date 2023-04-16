# reference-website

1. Naming convention for all filenames, paths and folders

-Naming conventions should always be lowercase and use dashed lines to seperate two words instead of spaces. Folder names should be similar to file name and content. For example, when creating a css folder, you should name the folder 'css' while naming the file 'style.css'. All folders and assets should be placed inside root folder for easy access and to link to any .html file. Ex. index.html

2. Best practices for commit messages

-Commit messages should be frequently noted and pushed regularly following any updates or changes made to your code. It is best to use past tense within your message and to provide a brief yet detailed summary of changes you made. For example, "updated and styled all divs in body content".

3. What is HTML?

-HTML stands for HyperText Markup Language. It is the standard coding language used and displayed in web browsers. In web design, it is used to input all text elements and main content of a web page. HTML is used when organizing content into various sections of a website such as defining a header, body, main content, and a footer. In other words, HTML provides structure and acts as a backbone to any webpage.

4. Proper syntax for HTML tags

-All HTML tags are enclosed between angle brackets. These brackets signify the beginning and end of a particular tag or element. For example, <p> represents the beginning of a paragraph or text. After typing the content we are displaying, we would close the tag using </p> to signify the end of a paragraph.

5. Explain or demonstrate commonly used html tags/elements:

a. h1-h6: is used in HTML to define a header or title of a particular section or article of a webpage. These headers are represented as < h1 > to < h6 >. Each tag numbered 1 through 6 varies in terms of font size and stroke weight. < h1 > is the largest in size and typically used at the top of a webpage, while < h6 > is the smallest in size and stroke weight, and can be used to distinguish the title of a smaller article or to emphasize a particular word or piece of content.

b. p: stands for 'paragraph' and is used to define a piece of text within a block of content. The <p> tag contains relevant info to the section or article.

c. lists: ul, ol, dl: lists are used in HTML to list items one after another. <ul> (unordered list) tag displays content as a bulleted list. <ol> (ordered list) displays content as a numerical list, while <dl> (description list)  lists items in a way that allows us to define terms and names.

d. a: stands for "anchor tag" and is used to embed a specific link to another article or webpage, on or off of your page, within a text or paragraph. It can be stylized as an interactive button, or as a navigation/guide within the header content of your page. It is displayed as <a href="insert-link"></a>. It is good to add an aria label to describe what the user will be clicking through so as to incorporate accessibility into your code.

e. img: is a tag used to embed an image (jpg, png, etc) into your webpage. It can be used in any section that requires visuals for either decoration or to serve a particular purpose. Image tags are displayed as <img src="insert-source"></img>. To add accessibility, it is good to add "alt" after inserting the source as it decribes what the user will be looking at.

f. q: is tag used to define short inline quotations.

g. blockquote: is used to define a large, specific section that is quoted from another source.

h. cite: is used to specify a URL that relates to or explains a quote.

i. em: stands for "emphasis" and is used for words that have a stressed emphasis compared to other text. It creates an italic effect on a particular word and can be nested within another tag such as <p>

j. strong: is used to define a particular text or words as an importance or urgency. Using < strong > nested within a < p > tag will result in that word being bold.

k. b: stands for "bold" and is similar to < strong > tag. Nesting within a < p > tag will result in a bold text but does not represent importance.

l. i: stands for "italic" and is used to define a certain part of a text and adds an italic effect.

m. small: defines a smaller text, such as a side-comment or copyright statement. This tag is typically used in the footer of a webpage.


6. A block element occupies the horizontal space of its container and the vertical space equal to the content being displayed. Block elements can force a new line to begin and cause a line break to occur.


a. html: used to define the beginning of the content within the text portion of a webpage and to define the language

b. head: this block element is situated at the very top of an html file and contains metadata and is responsible for holding information about the document like scripts and style sheets.

c. body: this element contains all the contents of an html page such as the paragraphs, images, lists, etc... It is used typically above the < main > tag.

d. header: this element holds introductory content such as a main title, any logos, and any navigations.

e. nav: responsible for serving as a directory to guide the user to a specific section fo the page. For example, a nav can guide the user to a particular section or article with relevant info.

f. main: contains content that is relevant to the main focus or topic of the webpage. Consists of various organized sections and articles.

g. section: encloses a series of articles revolving around one main idea or topic. It is used as an organization element and creates division between other areas of the webpage.

h. article: encloses one piece of content about a particular event, story or piece of information.

i. div: a widely used block element that can organize multiple pieces of information or content within a "box" or container. Divs can be stylized in CSS to add background colours, outlines, etc

j. aside: defines a portion of content that is not directly related to the main information or topic of the webpage. This is usually used in sidebars.

k. footer: defines information about author of section, copyright and any related links to other articles

l. span: represents a common inline container for organizing content and grouping different sections together. Can be styled using class or id attributes.

m. small: defines small text for side comments or for copyright information nested within the footer of a document.

7. Explain why accessibility is important and also explain the accessibility properties

Accessibility in web design is important because it accounts for all users who will visit your webpage with potential disabilities. It allows for all users to have an equal quality of experience and allows for all of your information and content to be easily accessible.

a. Landmark roles: help users to orient themselves on a page and can reference them to other areas or sections of a webpage

b. aria labels: provide a label to different objects, such as a button, that can be read by screen readers so that users know what they will be clicking on.

c. image alternative texts: provide an alternative text for an image if a user cannot view it. It allows for screen readers to understand what the user would be seeing.

8. CSS stands for Cascading StyleSheet. It implements design choices to the HTML of a webpage and can stylize the information and content to add visual appeal and organization. We can implement our CSS to our HTML files by creating a link to the CSS file within the head our index.html file. A sample code:

<html>
<head>

<link rel="stylesheet" href="/css/style.css">

</head>

9. A CSS property is a type of selector that specifies a characteristic of a webpage and can stylistically change its appearance. A CSS value is a unit of a CSS property whose value sets the change in a particular element. For example:

< color > is a CSS property that changes the color of a text written in HTML

Written as:

.text {
    color: white;
}

10. Why do we use border-box property in CSS?

We use the border-box property in CSS to adapt or account for any padding or border and includes those values in the total width or height of the element(s).

11. Explain different type of ways we can add spacing to an element

We can add spacing to different elements through multiple approaches. First, we can use the margin and padding property in our CSS to create space between a piece of content within a div, or to create more distance between a piece of content and other surrounding elements. Margin, in terms of a div, controls the space on the outside of the div in relation to the overall viewport, while padding controls the inner space between the content itself and the borders of the div. Another way we can add spacing to an element is by using flexbox. Using a property such as justify-content can control space between multiple elements on the same line and we can control their orientation. EX:

.div {
    justify-content: space-between;

}

12. What is the main difference between margin and padding?

The main difference between margin and padding is that margin controls the space around the element, or div's, outer border, while padding controls the inner space between the content and the inner border or the div itself.

13. What are different types of display properties?

Some display properties include:

display: flex;
display: block;
display: inline;
display: inline-block;

These properties specify the display behaviour of the element

14. Write a brief explanation of flexbox property

The flexbox property is used to control the display of an element or multiple elements. It can group content together and can control their orientation and spacing depending on their container.
We can use properties like justify-content, align-items and align-self to stylistically control the appearance of various pieces of content.

15. What are different types of flexbox properties and what is the major difference between them?

Different types of flexbox properties include:

justify-content: controls how the browser adds space between different elements ( ex.space-between, space-evenly, space-around)

align-items: controls how items are laid within a container (ex.flex-start, flex-end, stretch, center)

flex-direction: controls items to be laid out either horizontally or vertically within a container

align-content: aligns a flex container's lines only when there is more space on the cross-axis

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property

EX.

.div-1 {
    display: flex;
}

Some sub properties you may need for the flexbox property are justify-content to control the spacing between multiple pieces of content within the div, another property you could use is align-content to control how they are oriented within the container.

17. 

EX. 

.div-1 {
    display: flex;
    justify-content: space-between;
    align items: flex-start;
    background color: #FAFAFA;
    color: white;
    
}

18. What is CSS grid property?

CSS grid property is a grid-based layout system that divides a page into multiple rows and columns in order to make it easier to position various elements and pieces of content and control their size and how they layer with one another.

19. Write the parent and two sub-properties used for CSS Grid Property.

EX. 

.div {
    display: grid;
    grid-gap: 5px;
    grid-template-rows: (4, 1fr);
}

20. What is the difference between display: flex and display: grid?

The main difference between display: flex and display: grid is that flexbox was designed for one-dimension layout, while Grid was designed for two-dimension layout as it is divided between rows anc columns.

21. What sub-property we use to divide elements in CSS Grid properties?

We use the grid-template-rows or grid-template-columns sub-property to divide elements in CSS Grid 

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively?

We use the unit fr to fractionally divide the element's width in CSS Grid. 1fr refers to 1 part of the available space. Other units we can use include px (pixels) and percentages.

23. What is the area property in CSS grid we use for the child elements?

We can use the grid-area property to define a grid item's size and its position within the grid itself by setting a specific value.

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

To prevent displaying empty columns, we can use the sub-property grid-auto-columns

EX.

.grid-container {
    <p>display: grid;
    grid-template-areas: "image detail detail"
    grid-template-columns: 200px 400px;
    grid-auto-columns: 150px;</p>
}

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.

We can add google fonts to our CSS file by copy pasting the code found in the bottom right window beneath the chosen font family into the < head > of our HTML file. After linking the chosen font to our HTML file, we can use it in our CSS by typing:

EX.

#header-1 {
    <p>font-family: 'Open Sans', serif;</p>
}












