# Introductory HTML and JavaScript 

## Webpages are created with three main parts:
1. Hypertext Markup Language (**HTML**)
2. Cascading Style Sheets (**CSS**)
3. JavaScript (**JS**)

This page will first touch base on the main concepts to do with HTML and then cover the basics of JavaScript.

## HTML
HTML is the part that describes the structure of the web page. Structure helps the reader understand what they are seeing. 

### Structure
To describe structure, HTML uses elements; each element has an opening and closing tag. Tags act like containers, they tell you a little bit about the information they hold. Tags are made up of `<` left angle bracket, character or tag name, and `>` right angle bracket. For the closing tag it has the same exact make up, except there is a `/` forward slash right after the left bracket. Elements can also contain attributes that tell us more about them, these are usually placed right before the `>` right angle bracket.

Example of tags:

|Tag | Usage|
|---|---|
|`<!DOCUTYPE html>` | placed at the very top of the `.html` page to specify that this page is written in HTML5|
|`<html>`|identifies page is in html|
|`<head>`|element that contains information about the page|
|`<title>`|element that appears on top of the browser or on tab|
|`<body>`|elements visible on the actual web page|

<br>

### Extra Markup
These are some extra points to keep in mind when using HTML

* Use `<!---`comment`--->` to add a comment within the `.html` document that would not be visible to the user.
* Some attributes are called global attributes, that is because they can be used with any element. For example `id = ""` and `class = ""`.
* Block elements are those that do not allow other elements to appear next to them on the page. For example `<h1>`,`<p>`,`<ul>`, and `<li>`.
* Some characters are considered special or reserved by HTML (like `&`, `<`,`>`, and `"`) for those characters to appear on the page you must use escape characters. For example: in order to see the copyright symbol you must enter the following escape characters `&copy;` or `&#169;`.

### HTML Layout 
Generally this is the layout for a `.html` page:
```
<!DOCTYPE html>
<html>
	<head>
		 <title>Font Family</title>
	</head>
	<body>
		<header></header
		<main></main>
		<footer></footer>
	</body>
</html>

```
Here are some of the main tags and their usage:

|Tag | Usage|
|---|---|
|`<header>` |contains the information placed at the very top of the web page|
|`<main>`|contains the main information of the web page that lays between the header and footer|
|`<footer>`|contains the information placed at the very bottom of the web page|
|`<nav>`|navigational blocks|
|`<article>`|stand alone elements|
|`<section>`|single block in larger element|
|`<hgroup>`|for grouping headers and treating them as one|
|`<div>`|sectioning elements|

<br>

When thinking about your webpage, the process of creating it should go as follows:

* Define your audience and understand their needs 
* Create, based on your above decision, fictional visitors that represent the demographic you selected as your target
* Determine key tasks and motivations that would encourage visitors to engage with your site
* Decide what information will you present to visitors to assist them in achieving their reasoning for entering your site
* Set a site map to make sense of how pages should be linked
* Create a wireframe (sketch) to display the key information that needs to be available on each web page as well as a general layout for the pages
* Design the content of your pages by prioritizing, organizing, and applying visual hierarchies to different elements, this is to allow for a smoother experience when on the site
* Design navigation  to make moving in your site user friendly and easy to navigate

<br><br>

## JavaScript
JavaScript makes pages more interactive and reactive, to put it simple JS will:

1. **Access** the content of the page
2. **Modify** the content of the page
3. **Program** rules or instructions the browser can follow
4. **React** to events triggered by the user or browser 

### Scripts:

A script is a series of instructions that a computer can follow to achieve a goal. To write a script you must first determine the goal you hope to achieve and the list the steps or tasks required to achieve that goal (you can sketch those in a flowchart to make them easier to follow). After you write your script you can then code each step to create a single instruction for the computer.

### Basic concepts:

|Concept |Definition|
|---|---|
|Objects| *"In computer programming, each physical thing in the world can be represented as an object"*|
|Properties| Descriptions of the objects.*"Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object."*|
|Events| Interactions with objects, with JS programmers choose which events pages respond to |
|Method| HOW the interactions with objects take place|

<br>

After looking at all of the concepts above, this is how it all ties together:

>*"Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an object's properties. "*

<br>

### How it all fits together: 
The three layers mentioned below allow authors to build pages using the progressive enhancement approach.
1. HTML is the content layer which defines the structure of the page
2. CSS is the presentation layer which sets the styling and formatting of the page
3. JS (JavaScript) is the language that enables you to adjust how the page behaves by adding interactivity.

Focusing on the JS elements; as an author, you may include JS to your web page using two methods:
1. In an external file linked to the HTML file. This is considered best practice. Just like with html and css, to specify that your file is JS, it needs to be saved with the extension **.js**. 

For example: Say you have a file named "index.js" which includes certain objects you want to take effect on your page, all you have to do is link it to your HTML file using the script tag:

```
<script src="index.js"></ script>

```

2. JS could also be applied within the HTML file. For example:

```
<script>document.write(' <h3>Welcome !</h3>');
</script> 

```

What both methods prove, however, is that JS runs only where you apply it in HTML.

<br>

***
<br>

## [Home](README.md) | [Next]()
