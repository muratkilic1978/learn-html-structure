# learn-html-structure

This is a short introduction to the **HTML5 structure** and some basic HTML Tags for **beginners**. I recommend that you create a new index.html file with your editor eg. _Sublime_, _Atom Brackets_ or _Visual Studio Code_. I suggest that your insert All the HTML Tags from this introduction into your own **index.html** document and finally open the **index.html** in your browser eg. Mozilla FireFox or Chrome to check the result. <br><br>

## The HTML `<DOCTYPE>` declaration

### Examples

`<!DOCTYPE html>`<br>
All **HTML** documents must start with a `<!DOCTYPE>` declaration.<br>
The declaration is not an **HTML** tag. It is an "information" to the browser about what document type to expect.<br><br>

## The `<html>` Element

### Examples

`<html lang="en">`<br>
`</html>`<br>
The `<html>` tag comes in pairs and represents the root of an HTML document and is the container for all other HTML elements (except for the `<!DOCTYPE>` tag). Always include the _lang_ attribute inside the `<html>`tag to assiste search engines and browsers.<br><br>

## The `<head>` Element

`<head>`<br>
`</head>`<br>
**The `<head>` tag comes in pairs and primarily contains header information about the document, such as its title, keywords, description, and style sheet** <br>

### Examples

`<meta charset="UFT-8">`<br>
**Define the character set used and comes as single tag**<br><br>

`<meta name="keywords" content="HTML, Tags, structure, block-elements, inline-elements">`<br>
**Define keywords for search engines and comes as single tag**<br><br>

`<meta name="author" content="John Doe">`<br>
**Define the author of a page and comes as single tag**<br><br>

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`<br>
**Setting the viewport to make your website look good on all devices and comes as single tag**<br><br>

`<title>HTML5 Tags and structure</title>`<br>
**The`<title>` tag comes in pairs and defines a title in the browser toolbar and provides a title for the page when it is added to favorites in the browser** <br><br>

`<link rel="stylesheet" href="css/style.css">`<br>
**The `<link>` element defines the relationship between the current document and an external resource and is often used to link to external style sheets. It comes as single tag.**<br><br>

**Another example with `<link>` tag is when you want to create a favicon to your website**<br>

`<link rel="icon" type="image/x-icon" href="img/favicon.ico">`<br>
**A favicon is a small image displayed next to the page title in the browser tab and comes as single tag.**<br><br>

## Here is an overview of the most popular HTML5 tags from WebsiteSetup.org

![alt text](cheatsheet.png)
