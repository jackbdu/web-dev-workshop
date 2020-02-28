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
HTML Introduction: [https://www.w3schools.com/html/html_intro.asp](https://www.w3schools.com/html/html_intro.asp)

#### HTML Elements
An HTML element usually consists of an opening tag and a closing tag, with content in between.
```html
<tagname>some content</tagname>
```
HTML Elements: [https://www.w3schools.com/html/html_elements.asp](https://www.w3schools.com/html/html_elements.asp)

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
CSS Introduction: [https://www.w3schools.com/css/css_intro.asp](https://www.w3schools.com/css/css_intro.asp)

## Hands-on - HTML

### [Simplest page](01-01-simplest-page.html)
[View the page](https://jackbdu.github.io/web-dev-workshop/01-html-and-css/01-01-simplest-page.html)

`<DOCTYPE! html>` defines the document type to be HTML5.

`<html></html>` defines an HTML document, all HTML elements except for `<DOCTYPE html>` go in here.

`<head></head>` defines the information about the document, and elements in here do not show up on the page.

`<title></title>` defines the tile of the page, and shows up in the browser tab of the page.

`<body></body>` defines the body of the page. The elements in the body show up on the page.

`<h1></h1>` defines a heading.

`<p></p>` defines a paragraph.

## Hands-on - CSS

### Useful resources
- HTML Tutorial on W3Schools: https://www.w3schools.com/html/default.asp
- CSS Tutorial on W3Schools: https://www.w3schools.com/css/default.asp
- HTML Element Reference: https://www.w3schools.com/TAGS/default.ASP
- HTML <link> Tag: https://www.w3schools.com/tags/tag_link.asp
- HTML Color Picker: https://www.w3schools.com/colors/colors_picker.asp
- CSS Reference: https://www.w3schools.com/cssref/
- CSS Units: https://www.w3schools.com/cssref/css_units.asp
- Unsplash (Royalty Free Images): https://unsplash.com/
