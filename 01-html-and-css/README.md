# HTML & CSS - Designing Layouts, Content & Styles

## Terminologies

### Internet
The **Internet** is the global system of interconnected computer networks that uses the Internet protocol suite (TCP/IP) to link devices worldwide. ([Wikipedia](https://en.wikipedia.org/wiki/Internet))

### World Wide Web
The **World Wide Web** (**WWW**), commonly known as **the Web**, is an information system where documents and other web resources are identified by Uniform Resource Locators (URLs, such as https://www.example.com/), which may be interlinked by hypertext, and are accessible over the Internet. ([Wikipedia](https://en.wikipedia.org/wiki/World_Wide_Web))

### Web browser
A **web browser** (commonly referred to as a **browser**) is a software application for accessing information on the World Wide Web. ([Wikipedia](https://en.wikipedia.org/wiki/Web_browser))

### HTML
**Hypertext Markup Language** (**HTML**) is the standard markup language for documents designed to be displayed in a web browser. ([Wikipedia](https://en.wikipedia.org/wiki/HTML))

### CSS
**Cascading Style Sheets** (**CSS**) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. ([Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

## Overview

### HTML
HTML describes the structure and content of a web page.
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Title of the page</title>
  </head>
  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```
- HTML introduction: [https://www.w3schools.com/html/html_intro.asp](https://www.w3schools.com/html/html_intro.asp)
- HTML tutorial: [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp)

#### HTML Elements
An HTML element usually consists of an opening tag and a closing tag, with content in between.
```html
<tagname>some content</tagname>
```
- HTML elements: [https://www.w3schools.com/html/html_elements.asp](https://www.w3schools.com/html/html_elements.asp)
- HTML element reference: [https://www.w3schools.com/TAGS/default.ASP](https://www.w3schools.com/TAGS/default.ASP)

### CSS
CSS describes the styles of the elements on a web page.
```css
body {
  background: gray;
}

h1 {
  font-family: sans-serif;
}

p {
  color: red;
}
```
- CSS introduction: [https://www.w3schools.com/css/css_intro.asp](https://www.w3schools.com/css/css_intro.asp)
- CSS tutorial: [https://www.w3schools.com/css/default.asp](https://www.w3schools.com/css/default.as)
- CSS reference: [https://www.w3schools.com/cssref/](https://www.w3schools.com/cssref/)
- CSS default values reference: [https://www.w3schools.com/cssref/css_default_values.asp](https://www.w3schools.com/cssref/css_default_values.asp)

## Hands-on - HTML

### Simplest page
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/01-simplest-page/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/01-simplest-page/index.html)

`<DOCTYPE! html>` defines the document type to be HTML5.

`<html></html>` defines an HTML document, all HTML elements except for `<DOCTYPE html>` go in here.

`<head></head>` defines the information about the document, and elements in here do not show up on the page.

`<title></title>` defines the tile of the page, and shows up in the browser tab of the page.

`<body></body>` defines the body of the page. The elements in the body show up on the page.

`<h1></h1>` defines a heading.

`<p></p>` defines a paragraph.

- HTML doctype declaration: [https://www.w3schools.com/tags/tag_doctype.asp](https://www.w3schools.com/tags/tag_doctype.asp)
- HTML html tag: [https://www.w3schools.com/tags/tag_html.asp](https://www.w3schools.com/tags/tag_html.asp)
- HTML head tag: [https://www.w3schools.com/tags/tag_head.asp](https://www.w3schools.com/tags/tag_head.asp)
- HTML title tag: [https://www.w3schools.com/tags/tag_title.asp](https://www.w3schools.com/tags/tag_title.asp)
- HTML body tag: [https://www.w3schools.com/tags/tag_body.asp](https://www.w3schools.com/tags/tag_body.asp)
- HTML h1 to h6 tags: [https://www.w3schools.com/tags/tag_hn.asp](https://www.w3schools.com/tags/tag_hn.asp)
- HTML p tag: [https://www.w3schools.com/tags/tag_p.asp](https://www.w3schools.com/tags/tag_p.asp)


### Adding comments
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/02-adding-comments/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/02-adding-comments/index.html)
```html
<!--this is a comment-->
```

- HTML comment tag: [https://www.w3schools.com/tags/tag_comment.asp](https://www.w3schools.com/tags/tag_comment.asp)

### Adding an image
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/03-adding-an-image/) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/03-adding-an-image/index.html)
```html
<img src="path/to/image" alt="alternative text">
```
- HTML img tag: [https://www.w3schools.com/tags/tag_img.asp](https://www.w3schools.com/tags/tag_img.asp)
- Unsplash (royalty free photos): [https://unsplash.com](https://unsplash.com)

### Adding a list
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/04-adding-a-list/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/04-adding-a-list/index.html)

#### An unordered list
```html
<ul>
  <li>Unordered Item 1</li>
  <li>Unordered Item 2</li>
  <li>Unordered Item 3</li>
</ul>
```
#### An ordered list
```html
<ol>
  <li>Ordered Item 1</li>
  <li>Ordered Item 2</li>
  <li>Ordered Item 3</li>
</ol>
```
HTML Lists: [https://www.w3schools.com/html/html_lists.asp](https://www.w3schools.com/html/html_lists.asp)

### Adding a link
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/05-adding-a-link/) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/05-adding-a-link/index.html)
```html
<a href="relative/or/absolute/url">This is a link</a>
```
HTML a tag: [https://www.w3schools.com/tags/tag_a.asp](https://www.w3schools.com/tags/tag_a.asp)

### Adding multiple sections
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/06-adding-multiple-sections/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/06-adding-multiple-sections/index.html)
```html
<div>
  <h1>Section 1</h1>
  <p>Paragraph of section 1.</p>
</div>
<div>
  <h1>Section 2</h1>
  <p>Paragraph of section 2.</p>
</div>
```
- HTML div tag: [https://www.w3schools.com/tags/tag_div.asp](https://www.w3schools.com/tags/tag_div.asp)
- HTML header tag: [https://www.w3schools.com/tags/tag_header.asp](https://www.w3schools.com/tags/tag_header.asp)
- HTML nav tag: [https://www.w3schools.com/tags/tag_nav.asp](https://www.w3schools.com/tags/tag_nav.asp)
- HTML main tag: [https://www.w3schools.com/tags/tag_main.asp](https://www.w3schools.com/tags/tag_main.asp)
- HTML article tag: [https://www.w3schools.com/tags/tag_article.asp](https://www.w3schools.com/tags/tag_article.asp)
- HTML aside tag: [https://www.w3schools.com/tags/tag_aside.asp](https://www.w3schools.com/tags/tag_aside.asp)
- HTML footer tag: [https://www.w3schools.com/tags/tag_footer.asp](https://www.w3schools.com/tags/tag_footer.asp)

### A simple website
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/07-a-simple-website/) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/07-a-simple-website/index.html)

A simple website that combines all of the above.

## Hands-on - CSS

### Using CSS
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/08-using-css/) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/08-using-css/index.html)
#### Inline CSS
```html
<p style="color: red;">This paragraph will be in red.</p>
```
#### Internal CSS
```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <p>This paragraph will be in red.</p>
  </body>
</html>
```
#### External CSS
```html
<!-- index.html -->
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <p>This paragraph will be in red.</p>
  </body>
</html>
```
```css
/* style.css */
p {
  color: red;
}
```

- HTML style tag: [https://www.w3schools.com/tags/tag_style.asp](https://www.w3schools.com/tags/tag_style.asp)
- HTML link tag: [https://www.w3schools.com/tags/tag_link.asp](https://www.w3schools.com/tags/tag_link.asp)
- Difference Between the 3 Types of CSS Styles: Inline, External and Internal: [https://www.hostinger.com/tutorials/difference-between-inline-external-and-internal-css#Internal-CSS](https://www.hostinger.com/tutorials/difference-between-inline-external-and-internal-css#Internal-CSS)

### Colors
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/09-colors/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/09-colors/index.html)
```css
body {
  background-color: lightgray;
}

h1 {
  color: rgb(255,0,0);
}

p {
  color: #0000ff;
}
```
- CSS color property: [https://www.w3schools.com/cssref/pr_text_color.asp](https://www.w3schools.com/cssref/pr_text_color.asp)
- CSS background-color property: [https://www.w3schools.com/cssref/pr_background-color.asp](https://www.w3schools.com/cssref/pr_background-color.asp)
- Colors tutorial: [https://www.w3schools.com/colors/default.asp](https://www.w3schools.com/colors/default.asp)
- HTML color picker: [https://www.w3schools.com/colors/colors_picker.asp](https://www.w3schools.com/colors/colors_picker.asp)

### Sizes
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/10-sizes/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/10-sizes/index.html)
```css
h1 {
  font-size: 8em;
}

p {
  font-size: 10px;
}

img {
  width: 50%;
}
```
- CSS width property: [https://www.w3schools.com/cssref/pr_dim_width.asp](https://www.w3schools.com/cssref/pr_dim_width.asp)
- CSS height property: [https://www.w3schools.com/cssref/pr_dim_height.asp](https://www.w3schools.com/cssref/pr_dim_height.asp)
- CSS height and width dimensions: [https://www.w3schools.com/css/css_dimension.asp](https://www.w3schools.com/css/css_dimension.asp)
- CSS font-size property: [https://www.w3schools.com/cssref/pr_font_font-size.asp](https://www.w3schools.com/cssref/pr_font_font-size.asp)
- CSS units: [https://www.w3schools.com/cssref/css_units.asp](https://www.w3schools.com/cssref/css_units.asp)
- Fun with Viewport Units: [https://css-tricks.com/fun-viewport-units/](https://css-tricks.com/fun-viewport-units/)

### Spaces
[View the source code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/11-spaces/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/11-spaces/index.html)
```css
body {
  margin: 0;
  padding: 10vw;
  border-width: 1em;
  border-style: solid;
  border-color: gray;
}

h1 {
  padding: 2em;
  margin-bottom: 50px;
  border: 2px solid green;
}

p {
  margin: 15px;
  padding: 10px 0 0 10px;
  border: 1px dashed blue;
}

img {
  padding-top: 10px;
  border-top: 5px dotted red;
}
```
- CSS box model: [https://www.w3schools.com/css/css_boxmodel.asp](https://www.w3schools.com/css/css_boxmodel.asp)
- CSS margins: [https://www.w3schools.com/css/css_margin.asp](https://www.w3schools.com/css/css_margin.asp)
- CSS borders: [https://www.w3schools.com/css/css_border.asp](https://www.w3schools.com/css/css_border.asp)
- CSS padding: [https://www.w3schools.com/css/css_padding.asp](https://www.w3schools.com/css/css_padding.asp)

## Suggested Homework
- Find a simple webpage that you really like
- Try to replicate the overall layout using HTML
- Try to replicate the styles using CSS
- Google if there are elements of the chosen webpage that you do not know how to replicate
- Use Google Chrome to inspect the underlying HTML and CSS of the chosen webpage only when necessary
- Make notes of the problems that you cannot fix on your own and bring them to the next workshop
