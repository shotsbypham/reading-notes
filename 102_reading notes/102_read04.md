# Read: 04 - Structure web pages with HTML

## Wireframe and Design

A wireframe is a plan on how to design a website before actually designing it. Usually design a bunch of different layouts and see which one works best.

Steps to make a wireframe:

1. Do your research
2. Prepare your research for quick reference
3. Make sure you have your user flow mapped out
4. Draft, don't draw. Sketch, don't illustrate
5. Add some detail and get testing
6. Start turning your wireframes into prototypes

How to make your wireframe good:

1. Clarity
2. Confidence
3. Simplicity is key

## HTML Basics

HTML is a markup language which consists of enclosing tag that make hyperlinks, italicize words, change font sizes, and more.

Basic HTML and HTML5

Say Hello to HTML Elements

Opening and Closing tags: <h1> Hello, World </h1>

Headline with the h2 Element

- h1 : main headings
- h2 : sub headings

Inform with the Paragraph Element

- p: paragraph
- Paragraph tag: <p></p>

_Note: all html tags are written in lowercase_

Fill in the Blank with Placeholder Text

- Lorem ipsum text as placeholder text

Uncomment and Comment HTML

- Comment for notes in your code
- Comment tag: <!- -  - ->

Delete HTML Elements

- Just delete unnecessary elements…lol.

Introduction to HTML5 Elements
More descriptive HTML tags including: main, header, footer, nav, video, article, section and others.

- main: main content of your page

Add Images to Your Websites

- img: images
- <img src= “whatever the url is” alt= “caption of pic”>
- Img elements are self-closing.
- All img elements must have an alt attribute.
- alt: used for screen readers to improve accessibility and is displayed if the image doesn't load.

Link to External Pages with Anchor Elements

- a: anchor element to link to content outside of your website
- href: destination web address
- <a href= “fill this in with link”>caption for the link</a>

 Link to Internal Sections of a Page with Anchor Elements

- a: can also be used to create internal links for within your website

To create an internal link, assign a link to a href attribute using a “#” and assign it to an id attribute. Then add the same id attribute to the elemene you are linking it to.

- id: uniquely describes an element

Nest an Anchor Element within a Paragraph

- target: an anchor tag that specifies where to open the link

<p> Here’s a <a target= “_blank” href= “link”> caption for the link</a> </p>

Make Dead Links Using the Hash Symbol: To create a dead link, replace link with a “#”, used as a placeholder for a link.

- <a href= “#”>Dead Link</a>

Turn an Image into a Link

- You can make elements into links by nesting them within an a element
- <a href= “#”><img src= “link” alt= “caption”>
