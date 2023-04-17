# reference-website
1. Naming convention for all filenames, paths, and folders.
- The naming conventions for all filenames should be lowercase, no spaces and dashes are fine. Folder naming conventions should be similar to file names. For paths, the folders, assets, and files should be inside the root folder so they can be easily linked to any .html files.

2. Best practices for commit messages
- The best practices for commit messages are having a minimum of 3 words and 10 characters, proper spelling and grammar, capitalize first letter and no periods, must start with verbs like create or fix, and lastly pretend every commit starts with "This commit will...".

3. What is HTML?
- HTML stands for hypertext markup language which is the coding language that's used to describe the content of websites.


4. Proper syntax for HTML tags
- Proper syntax for html tags should be an open tag with a tag name inside then write the element content and then finish with a closing tag with the same tag name.

5. Explain or demonstrate commonly used html tags/elements:
headings: h1-h6
- h1-h6 are heading tags h1 is considered the most important of the webpage therefore h6 is considered the least important and smallest of the webpage.
For example, h1-h6 would be written like:
    <h1>example content</h1>

p
- This element defines a paragraph of text and is considered a block-level element. This element also always starts on a new line.
For example, p would be written like:
    <p>paragraph content</p>

lists: ul, ol, dl
- ul is an unordered list, ol is an ordered list, and dl is a description list.
For example, ul, ol, and dl would be written like:
    <ul>content</ul>    <ol>content</ol>    <dl>content</dl>

a
- This is an element used for links. The opening and closing of a defines where the link should start and end. The href piece in this element is the attribute that allows for the actual link to work when using this tag.
For example, a would be written like:
    <a href="link">text</a>

img
- Images are linked to a website by linking the image into the HTML document. In order for this tag to work the images needs to be defined in its location and have a descriptor of alternative content.
For example, img would be written like:
    <img src="image location" alt="description"/>

q
- Q is an element that's used to define quotations. This is used to mark up quotes that may be included in other content like in paragraphs.
For example, q would be written like:
    <q>quote</q>

blockquote
- This is an element that's used for defining quotations. Blockquote specifically is used to define larger quotes.
For example, blockquote would be written like:
    <blockquote>large quote</blockquote>

cite
- This is an element that's used for defining citations. By using cite, this allows for marking the source or author of the quote.
For example, cite would be written like:
    <cite>citation of source</cite>

em
- This is a phrasing element. By using em, this allows emphasis to be put on to the content. 
For example, em would be written like:
    <em>emphasis on content</em>

strong
- This is a phrasing element. By using strong, this allows for bigger emphasis to be put on to content, which puts more urgency of importance into the content.
For example, strong would be written like:
    <strong>important content</strong>

b
- This is a phrasing element. By using b, this allows the content to show a keyword.
For example, b would be written like:
    <b>keyword content</b>

i
- This is a phrasing element. By using i, this allows for another language, techinal term, or title to be present in the content.
For example, i would be written like:
<i>language, techinal term, or title</i>

small
- By using small, this allows for the text to appear smaller suggesting less urgency of importance, which is good for the use of copyright in the footer.
For example, small would be written like:
    <small></small>

6. Explain block Elements and also explain the list of block elements and why they are used from below:

html
- The html tag is used for the set up of a document, known as the "root of the document".
For example, html would be written like:
    <html></html>

head
- Head is an element used to define the container of metadata within the document. This element must be placed between the html element and the body element.
For example, head would be written like:
    <head></head>

body
- Body is the tag used to contain all other content that's placed within the document.
For example, body would be written like:
    <body></body>

header
- The header is part of the introduction of content. This element can be found at the top of a page and is usually accompanied with a logo or company name as well as a navigation. This element can also be in other sections and are used to deifne sections and articles with introductory pieces.
For example, header would be written like:
    <header>heading</header>

nav
- Nav is the tag used to define the navigation in a webpage. Typically, this tag is at the top of a webpage and is able to provide links either in the existing document or on a different document.
For example, nav would be written like:
    <nav></nav>

main
- Main is the tag used for the main content of a webpage. This element can only be used once and lets the webpage know what the main content of the webpage is.
For example, main would be written like:
    <main></main>

section
- Section is the tag used to group similar content together. There can be multiple sections used and typically each section has its own heading or subheading.
For example, section would be written like:
<section></section>

article
- Article is the tag used for self-contained content in a webpage. There can be multiple articles used and this tag is intended for independent distribution or reusable distribution.
For example, article would be written like:
    <article></article>

div
- This is a generic element. Div is a block element that's used to group other elements together. 
For example, div would be written like:
    <div></div>

aside
- Aside is the tag used to define a portion of a document. This portion of content is only able to be used on content that's indirectly related to the main content fo a webpage.
For example, aside would be written like:
    <aside></aside>

footer
- The footer is at the end of many webpages. The footer typically includes information such as copyright, extra information about the company, or lists of links.
For example, footer would be written like:
    <footer></footer>

span
- This is a generic element. Span is an inline container which can be used to mark up part of a text or part of a document.
For example, span would be written like:
    <span></span>

small
- By using small, this allows for the text to appear smaller suggesting less urgency of importance, which is good for the use of copyright in the footer.
For example, small would be written like:
    <small></small>

7. Explain why accessibility is important and also explain the accessibility properties like:
- Accessibility is important because it allows those with impairments to be able to access all information equally and to provide an ideal experience. To make sure a website is accessible, following the four principles perceivable, operable, understandable, and robust is a must in order to comply with accessibility requirements.

landmark roles
-  landmark roles are part of ARIA, meaning those using screen readers are able to jump to specific sections within a website.

aria labels
- aria labels are an attribute that provides an extra description within the HTML of a website and provides users with a non-visual label that will only be announced by screen readers.

image alternative texts
- image alternative text is an attribute that describes an image. Using image alternative text allows for a description of the image incase it doesn't download and allows for a description of the image for users with visual impairments.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS stands for cascading style sheet, which is the language that's used to control the appearance of a website within the HTML pages. In order to put CSS into an HTML file, a CSS file needs to be created first  then create a folder inside the CSS file named style.css. To link the CSS file into the HTML file a link must be created and then write stylesheet into the rel= section then css/style.css into the href section of the link.
For example,
<link rel="stylesheet" href="css/style.css"/>

9. What is the difference between CSS property and value (write explanation and an example code)
- CSS property is the type of design being added to a website while a CSS value is the accepted value for a property. For example, 
    background-color: purple;
    the property would be "background-color" and the value would be "purple".

10. Why do we use border-box property in CSS?
- The border-box property is used in CSS to allow for padding and the border to be included into the width and height within the box so that the total is the same value.

11. Explain different type of ways we can add spacing to an element
-  padding and margins are different ways of applying space to an element. Padding can add space to an element by adding space inside the box. Margins add space outside the box of an element which allows for separation between other elements.

12. What is the main difference between margin and padding?
- Margins and padding are two ways of adding space into a box. The difference between margins and padding is that margins apply space outside of the box while padding applies space inside a box but outside of the content.

13. What are different types of display properties?
- Different types of display properties are inline, block, inline-block, and none. Inline allows an element to be on the same line. Block forces an element to be on its own line. Inline-block allows an element to be formatted like an inline element but still allows for height and width changes. None allows an element to be completely removed.

14. Write a brief explanation of flexbox property
- Flexbox allows for the control of the flow and alignment of elements on a webpage. Flexbox allows elements to fit together on the same line and can also work on a vertical axis as well.

15. What are different types of flexbox properties and what is the major difference between them?
- Different types of flexbox properties are width, flex and inline-flex, flex-direction, flex-wrap, justify-content, align-items, and align-content. The flex box property width, allows for the control of space that will be taken up. Flex is a flex property that allows the container to act as block element. Flex-inline is a property that allows the container to act like an inline-block element. Flex-direction changes the orientation (vertical or horizontal) for the content to be justified or aligned properly. Flex-wrap property allows for the control of the container to be a single-line or multi-line layout. Justify-content allows for the control of the position and alignment on the main axis as well as controlling the space around other flex-items. Align-items works the same as the justify-content property, but instead works on the cross axis. Align-content is a property used to align flex containers when there is extra space on the cross axis.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.

18. What is CSS grid property?

19. Write the parent and two sub-properties used for CSS Grid Property.

20. What is the difference between display: flex and display: grid?

21. What sub-property we use to divide elements in CSS Grid properties?

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)

23. What is the area property in CSS grid we use for the child elements?

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.