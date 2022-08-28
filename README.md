
# parallax website

Parallax scrolling is a web site trend where the background content (i.e. an image) is moved at a different speed than the foreground content while scrolling. Click on the links below to see the difference between a website with and without parallax scrolling.


Approach:
I have used a container element and add a background image to the container. Then we have used the background-attachment: fixed to create the actual parallax effect.
For each HTML section I have given a class so that it can be target in the CSS.
In the HTML page, I have divisions and in each division, there is a header and a small paragraph. In the CSS file, I have decorated our text and placed the head at a fixed position.

Some mobile devices have a problem with background-attachment: fixed. However, you can use media queries to turn off the parallax effect for mobile devices:

## languages used
HTML 5

CSS

## HTML Usage
The html element represents the root of an HTML document.

The head element represents a collection of metadata for the Document.

The meta element represents various kinds of metadata that cannot be expressed using the title, base, link, style, and script elements.

HTML (HyperText Markup Language) is the most basic building block of the Web.
It defines the meaning and structure of web content.
Other technologies besides HTML are generally used to describe a
web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. 
Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people,
you become an active participant in the World Wide Web.

HTML uses "markup" to annotate text, images, and other content for display in a Web browser.
HTML markup includes special "elements" such as <head>, <title>, <body>, <header>, <footer>, <article>, <section>, <p>, <div>,
<span>, <img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol>, <li>
## CSS usage
Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written 
in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes
 how elements should be rendered on screen, on paper, in speech, or on other media.

CSS is among the core languages of the open web and is standardized across Web browsers according to W3C specifications.
 Previously, the development of various parts of CSS specification was done synchronously, which allowed the versioning of the latest recommendations. 
 You might have heard about CSS1, CSS2.1, or even CSS3. There will never be a CSS3 or a CSS4; rather, everything is now CSS without a version number.## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color |body, html [color:rgb(167, 124, 124)];|
| Example Color | Logo [ color: black;] |
| Example Color | header ul li a[color: darkblue;] |
| Example Color | .active,header ul li[background-color: rgb(244, 244, 16);] |
| Example Color |.section-light [background-color:#f4f4f4] |
| Example Color | .section-light [color:#666;]|
| Example Color |.ptext[ color:#000;]|
| Example Color | .ptext .border[color:#fff;] |
| Example Color |.ptext .border.trans[background-color:transparent;] |



