# HTML-Content-Identification
-----------------------------------------------------------
Identification of HTML content entails identifying and comprehending the different components and tags that are utilized in HTML texts. Understanding the various forms of content and how to use them to organize web pages is crucial when dealing with HTML. 

•	Basic structure tag:
-----------------------------------------------------------
<!DOCTOTYPE html> : declares the document type and HTML version
<html>: the root element of the HTML page
	<head>: contains meta- information about the document, like its title and links to scripts and stylesheets.
	<title>: specifies the title of the document which is shown in the browser’s title bar or tab.
	<body> contains the content of the document such as text, images, paragraphs ad other media.
    
	Text formatting tags:
 --------------------------------------------------------
•	<h1>, <h2>, <h3>, …. <h6>: headings with <h1> being the highest( most important ) level and <h6> is the lowest
•	<p> is for paragraphs.
•	<br>: line break
•	<hr>: horizontal line break
•	<strong> and <b>: bold text with <strong> indicating importance.
•	<em> and <i>: italic text with <em> indicating emphases.

Hyperlinks and images:
--------------------------------------------------------------
•	<a href=ÜRL”>:Hyperlink to another document or resource
•	<img src=ïmge url” alt=”alternative text”>: Embeds an image into the document.

Lists: 
--------------------------------------------------------------
•	<ul>: Unordered (bulleted list) list.
•	<ol> Ordered (numbered list) list.
•	<li>: list item.

Tables:
--------------------------------------------------------------
•	<table>: define tables
•	<tr>: table row
•	<th>: table header cell
•	<td>: table data cell.

Forms:
-------------------------------------------------------------
•	<form>: define a form for user
•	<input>: input field
•	<label>: label for an <input> element
•	<textarea>: multi-line text input
•	<button>: button

Semantic tags (HTML5)
-----------------------------------------------------------
•	<Header>: introductory content or navigational links.
•	<nav>: navigation links.
•	<article>: independent, self-contained content.
•	<section>: sections of a document.
•	<footer>: footer for a document or section.
•	<aside>: content indirectly related to the document content.

Media and embedding:
-----------------------------------------------------------
•	<video>: and <audio>: embedded video and audio content.
•	<canvas>: used for drawing graphics on the fly.
•	<iframe>: embeds another HTML page within the current page.

HTML Generic Elements, Div and Span:
-----------------------------------------------------------
Standard HTML components such as <div> and <span> are used to organize other elements and apply JavaScript actions or CSS style to them. They are basically containers that, while not intrinsically representing anything or having any semantic significance, are useful tools that help web developers organize and layout web pages effectively.

DIV Element: 
-----------------------------------------------------------
•	Description: When using CSS for styling or layout, HTML elements can be grouped together using the <div> element, which is a block-level container. It symbolizes a segment or a break within an HTML document.

Characteristics: 
-----------------------------------------------------------
•	Block-level: occupies the entire possible width, with a fresh line appearing before and after.
•	used to arrange items into sections or groups so they can be styled together or arranged as a single unit inside a layout.

	Common uses:
-----------------------------------------------------------
•	Creating a layout structure (e.g., header, footer, sidebar, content area)
•	Grouping elements to apply the same styling or classes.
•	Serving as containers for dynamic content updated via JavaScript.

<SPAN>Element:
------------------------------------------------------------
•	Description: An inline container called the <span> element can be used to mark up a section of a text or a document for style or to apply JavaScript operations. It has no semantic significance or intrinsic representation.

	Characteristics:
------------------------------------------------------------
•	Inline: takes up only the appropriate width and does not result in a line break.
•	Used to style a small part of the text or to apply specific behavior without changing the documents flow.

	Common uses:
------------------------------------------------------------
•	Changing the style (color, font, background) of a part of a text.
•	Wrapping a text portion to apply JavaScript actions like click events.
•	Highlighting a part of text without affecting the document’s layout.

Key display:
-------------------------------------------------------------
Display: <div> is a block-level element, while <span> is an inline element.
Purpose: 
--------------------------------------------------------------
•	<div> is typically used for larger blocks of html, often as containers for layout sections.
•	<Span> is used for smaller portions of text or inline element within other displayed content.

Effect on layout: 
---------------------------------------------------------------
•	By default, adding a <div> will result in the creation of new lines before and after it, which will have a greater impact on the layout. <span> won't impede the surrounding content's flow.
<div> and <span> are essential elements of HTML that are used extensively in web development for content organization and CSS style application. Because of their generic character, which gives them great versatility, developers can change web page elements for both layout and styling without giving the content any additional semantic significance.


