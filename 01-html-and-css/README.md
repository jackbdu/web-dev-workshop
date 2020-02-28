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
- HTML Introduction: [https://www.w3schools.com/html/html_intro.asp](https://www.w3schools.com/html/html_intro.asp)
- HTML Tutorial on W3Schools: [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp)

#### HTML Elements
An HTML element usually consists of an opening tag and a closing tag, with content in between.
```html
<tagname>some content</tagname>
```
- HTML Elements: [https://www.w3schools.com/html/html_elements.asp](https://www.w3schools.com/html/html_elements.asp)

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
- CSS Introduction: [https://www.w3schools.com/css/css_intro.asp](https://www.w3schools.com/css/css_intro.asp)
- CSS Tutorial on W3Schools: [https://www.w3schools.com/css/default.asp](https://www.w3schools.com/css/default.as)

## Hands-on - HTML

### Simplest page
[View the code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/01-simplest-page/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/01-simplest-page/index.html)

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
[View the code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/02-adding-comments/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/02-adding-comments/index.html)
```html
<!--this is a comment-->
```

- HTML comment tag: [https://www.w3schools.com/tags/tag_comment.asp](https://www.w3schools.com/tags/tag_comment.asp)

### Adding an image
[View the code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/03-adding-an-image/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/03-adding-an-image/index.html)
```html
<img src="path/to/image" alt="alternative text">
```
- HTML img tag: [https://www.w3schools.com/tags/tag_img.asp](https://www.w3schools.com/tags/tag_img.asp)
- Unsplash (Royalty Free Photos): [https://unsplash.com](https://unsplash.com)

### Adding an list
[View the code](https://github.com/jackbdu/web-dev-workshop/blob/master/01-html-and-css/04-adding-an-list/index.html) | [View the page](https://jackbdu.github.io/web-dev-workshop/04-adding-an-list/index.html)

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

## Hands-on - CSS

### Useful resources
- HTML Element Reference: https://www.w3schools.com/TAGS/default.ASP
- HTML <link> Tag: https://www.w3schools.com/tags/tag_link.asp
- HTML Color Picker: https://www.w3schools.com/colors/colors_picker.asp
- CSS Reference: https://www.w3schools.com/cssref/
- CSS Units: https://www.w3schools.com/cssref/css_units.asp
