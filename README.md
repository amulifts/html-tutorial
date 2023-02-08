# HTML Tutorial

In this tutorial, i'll start from the very beginning. You don't need to know anything about HTML or anything about code to start.

## Table of Contents

 * [HTML](#html)
 	* [History](#history)
	* Basic
		* [Basic HTML document syntax](#syntax)
		* [Basic HTML document structure](#structure)
		* [HTML Elements and Attributes](#elementsandattributes)
		* [List of HTML Elements and Attributes](#listofelementsandattributes)
		* [Text Formatting in HTML](#textformatting)
		* [Adding Images and Media to HTML Pages](#imagesandmedia)
		* [Creating Links in HTML](#links)
	* Intermediate
		* [HTML Lists and Tables](#listsandtables)
		* [HTML Forms and Input Elements](#formsandinputelements)
		* [Semantic Elements in HTML5](#semantic)
		* [HTML Styles and CSS](#stylesandcss)
		* [HTML Layout and Responsive Design](#layoutandresponsivedesign)
	* Advanced
		* [HTML APIs and Dynamic Web Content](#apisanddynamicwebcontent)
		* [Accessibility and Assistive Technologies in HTML](#accessibility)
		* [Best Practices and Maintenance of HTML Documents](#bestpractices)

<a name="html"></a>

## HTML

HTML stands for **HyperText Markup Language**. It is a **markup language** used to create and structure web pages. HTML is the **foundation** of all websites and provides the **structure** for displaying text, images, videos, and other types of content on the web. HTML can be written using a text editor and when we save the extension of the file must be `.html` and viewed in a web browser. When a web browser loads an HTML document, it displays the content and structure defined by the HTML code.

<a name="history"></a>

## History

It was first developed in 1990 by Tim Berners-Lee, the founder of the World Wide Web, as a way to share scientific information between researchers.

Here's a brief overview of the major versions of HTML:

`HTML 1.0 (1993)` - This was the first widely adopted version of HTML and was very basic, allowing only text and simple formatting.

`HTML 2.0 (1995)` - This version added new features such as forms, tables, and image support.

`HTML 3.2 (1997)` - This version added more advanced features such as tables, improved formatting, and support for multimedia.

`HTML 4.0 (1997)` - This version added new features such as style sheets, scripting, and support for more advanced multimedia.

`HTML 4.01 (1999)` - This was a minor revision of HTML 4.0 that added some bug fixes and clarification of some elements.

`XHTML 1.0 (2000)` - This was a reformulation of HTML 4.01 as XML, a more strict and well-formed markup language.

`HTML5 (2014)` - This is the latest version of HTML and adds many new features such as multimedia support, semantic elements for improved accessibility, and new form controls.

It's important to note that while these are the major releases, HTML is constantly evolving and there have been many smaller revisions and updates over the years.

## HTML5

We will be using `HTML5` in this tutorial. HTML5 is the latest version of HTML and is the version that is currently being standardized by the **World Wide Web Consortium (W3C) : an international organization committed to improving the web.** It is the version that all modern browsers support.


# BASIC

<a name="syntax"></a>

### HTML5 Document Syntax

HTML documents are made up of **elements** that are used to define the structure of the page. Elements are made up of **tags** that are enclosed in angle brackets (`<` and `>`). The first tag is the **opening tag** and the second tag is the **closing tag**. The closing tag is the same as the opening tag, but with a forward slash (`/`) before the tag name. The content of the element is placed between the opening and closing tags.

It is important to note that HTML is **case insensitive**, which means that the tags can be written in uppercase, lowercase, or a mixture of both. However, it is considered good practice to use lowercase tags in HTML documents. Here's an example of an HTML element:

```html
<p> <!-- Opening tag -->
	This is a paragraph. <!-- Content -->
</p> <!-- Closing tag -->
```

<a name="structure"></a>

### HTML5 Document Structure

Every HTML document has a basic structure that includes the following:

- `<!DOCTYPE html>` - This is the first line of the document and tells the browser that this is an HTML5 document.
- `<html>` - This is the main element of the HTML document that wraps around all of the other elements. It starts with `<html>` and ends with `</html>`.
- `<head>` - This element contains metadata about the document such as the page title, character set, styles, scripts, and other meta information. It starts with `<head>` and ends with `</head>`.
- `<title>` - This element specifies the title of the document, which is shown in the browser's title bar or on the page's tab. It starts with `<title>` and ends with `</title>`.
- `<body>` - This element contains the visible page content such as headings, paragraphs, images, hyperlinks, tables, lists, etc. It starts with `<body>` and ends with `</body>`.

Here's an example of a basic HTML5 document structure:

```html
<!DOCTYPE html>
<html>
	<head>
		<title> <!-- Page Title --> </title>
	</head>
	<body>
		<!-- Page Content -->
	</body>
</html>
```

<a name="elementsandattributes"></a>

### HTML5 Elements and Attributes

We have already discussed about HTML elements earlier [here](#syntax) . Now i will discuss about HTML attributes. HTML elements can have one or more attributes that provide additional information about the element. Attributes are specified in the opening tag and consist of a name and a value, separated by an equals sign (`=`). Here's an example of an HTML element with an attribute:

**First Example**

```html
<a href="https://www.amankhadka.com"> <!-- Opening tag -->
	Google <!-- Content -->
</a> <!-- Closing tag -->
```

In the above example, the `href` attribute specifies the URL of the page that the link goes to.

**Second Example**

```html
<img src="image.jpg" alt="Image" />
```

In the above example, the `src` attribute specifies the path to the image file and the `alt` attribute specifies an alternate text for the image, which is displayed if the image cannot be displayed.

<a name="listofelementsandattributes"></a>

### List of HTML Elements and Attributes

| HTML Element | Description | HTML Attributes |
| --- | --- | --- |
| `<html>` | Defines the root of an HTML document | `lang`, `dir` |
| `<head>` | Defines information about the document | |
| `<title>` | Defines a title for the document | |
| `<body>` | Defines the document's body | `onload`, `onunload` |
| `<h1>` to `<h6>` | Defines HTML headings | |
| `<p>` | Defines a paragraph | |
| `<br>` | Inserts a single line break | |
| `<hr>` | Defines a thematic change in the content | |
| `<pre>` | Defines preformatted text | |
| `<a>` | Defines a hyperlink | `href`, `target`, `download`, `rel`, `hreflang`, `type` |
| `<em>` | Defines emphasized text | |
| `<strong>` | Defines important text | |
| `<small>` | Defines smaller text | |
| `<mark>` | Defines marked/highlighted text | |
| `<sub>` | Defines subscripted text | |
| `<sup>` | Defines superscripted text | |
| `<blockquote>` | Defines a section that is quoted from another source | |
| `<q>` | Defines a short quotation | |
| `<abbr>` | Defines an abbreviation or an acronym | |
| `<address>` | Defines contact information for the author/owner of a document | |
| `<time>` | Defines a date/time | `datetime` |
| `<code>` | Defines a piece of computer code | |
| `<samp>` | Defines sample output from a computer program | |
| `<b>` | Defines bold text | |
| `<i>` | Defines italic text | |
| `<u>` | Defines underlined text | |
| `<s>` | Defines strikethrough text | |
| `<span>` | Defines a section in a document | |
| `<div>` | Defines a section in a document | |
| `<img>` | Defines an image | `src`, `alt`, `width`, `height`, `usemap`, `ismap`, `longdesc` |
| `<ul>` | Defines an unordered list | |
| `<ol>` | Defines an ordered list | |
| `<li>` | Defines a list item | |
| `<dl>` | Defines a description list | |
| `<dt>` | Defines a term/name in a description list | |
| `<dd>` | Defines a description of a term/name in a description list | |
| `<table>` | Defines a table | |
| `<caption>` | Defines a table caption | |
| `<th>` | Defines a header cell in a table | |
| `<tr>` | Defines a row in a table | |
| `<td>` | Defines a cell in a table | |
| `<thead>` | Groups the header content in a table | |
| `<tbody>` | Groups the body content in a table | |
| `<tfoot>` | Groups the footer content in a table | |
| `<col>` | Specifies column properties for each column within a `<colgroup>` element | `span` |
| `<colgroup>` | Specifies a group of one or more columns in a table for formatting | `span` |
| `<form>` | Defines an HTML form for user input | `action`, `method`, `name`, `target`, `enctype`, `autocomplete`, `novalidate`, `accept-charset`, `rel`, `target`, `novalidate` |
| `<input>` | Defines an input control | `type`, `name`, `value`, `checked`, `disabled`, `readonly`, `required`, `size`, `maxlength`, `min`, `max`, `step`, `pattern`, `placeholder`, `autocomplete`, `autofocus`, `form`, `formaction`, `formenctype`, `formmethod`, `formnovalidate`, `formtarget`, `list`, `multiple`, `spellcheck` |
| `<textarea>` | Defines a multiline input control (text area) | `name`, `rows`, `cols`, `disabled`, `readonly`, `required`, `placeholder`, `autocomplete`, `autofocus`, `form`, `maxlength`, `spellcheck` |
| `<button>` | Defines a clickable button | `type`, `name`, `value`, `disabled`, `autofocus`, `form`, `formaction`, `formenctype`, `formmethod`, `formnovalidate`, `formtarget`, `formnovalidate` |
| `<select>` | Defines a drop-down list | `name`, `size`, `multiple`, `disabled`, `required`, `autofocus`, `form` |
| `<optgroup>` | Defines a group of related options in a drop-down list | `label`, `disabled` |
| `<option>` | Defines an option in a drop-down list | `value`, `disabled`, `selected` |
| `<label>` | Defines a label for an `<input>` element | `for`, `form` |
| `<fieldset>` | Groups related elements in a form | `disabled`, `form`, `name` |
| `<legend>` | Defines a caption for a `<fieldset>` element | |

In the above table, i have only listed the most **commonly used** HTML elements and attributes. There are many more HTML elements and attributes that we can learn about from the official HTML documentation.

The official website for HTML (HyperText Markup Language) is maintained by the World Wide Web Consortium (W3C), which is the main international standards organization for the Internet. The URL for the HTML specification is: [Click Here](https://www.w3.org/TR/html/)

<a name="textformatting"></a>

## Text Formatting in HTML

HTML provides several elements and attributes for formatting text, including headings, paragraphs, bold text, italic text, and more.

Here are some of the most commonly used text formatting elements in HTML:

- `<h1>` to `<h6>` - Defines HTML headings of different sizes, with `<h1>` being the largest and `<h6>` being the smallest.
- `<p>` - Defines a paragraph.
- `<b>` and `<strong>` - Defines bold text. The `<b>` element makes text bold, but does not convey any extra importance. The `<strong>` element makes text bold and conveys extra importance.
- `<i>` and `<em>` - Defines italic text. The `<i>` element makes text italic whereas the `<em>` element gives text italic emphasis.
- `<u>` - Defines underlined text. It is used to underline text.
- `<s>` - Defines strikethrough text. It is used to indicate that the text is no longer correct or relevant.
- `<sup>` - Defines superscripted text. It is used to display characters that should be superscripted such as the suffixes of dates or mathematical concepts like raising a number to a power.
- `<sub>` - Defines subscripted text. It is used to display characters that should be subscripted such as chemical formulas, like H2O.
- `<br>` - Inserts a single line break. It is used for line breaks within a paragraph of text.
- `<pre>` - Defines preformatted text which preserves the spacing and line breaks of the text as it was entered.

Here is an example of how to use some of the above elements to format text:

```html
<h1>This is a heading</h1>
<p>This is a paragraph of text. <b>This text is bold</b>, and <i>this text is italic</i>.</p>
<p>This is another paragraph of text. <u>This text is underlined</u>, and this is <sup>superscript</sup> text.</p>
```

**When the above HTML code is rendered in a browser, it will look like this:**

![Text Formatting in HTML](https://github.com/amulifts/html-tutorial/blob/main/images/textformatting.png)


<a name="imagesandmedia"></a>

## Adding Images and Media to HTML Pages

HTML provides several elements for adding images and media to web pages. The `<img>` element is used to add images to a web page. The `<audio>` and `<video>` elements are used to add audio and video to a web page.

Here is an example of how to use the `<img>` element to add an image to a web page:

```html
<img src="image.jpg" alt="Image Description">
```

Here is an example of how to use the `<audio>` and `<video>` elements to add audio and video to a web page:

```html
<!-- audio -->
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<!-- video -->
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video element.
</video>
```

<a name="links"></a>

## Creating Links in HTML

HTML provides several elements for creating links in web pages. The `<a>` element is used to create links to other web pages, files, locations within the same page, email addresses, or any other URL.

Here is an example of how to use the `<a>` element to create a link to another web page:

```html
<a href="https://www.amankhadka.com">Aman</a>
```

Here is an example of how to use the `<a>` element to create a link to a file:

```html
<a href="file.pdf">Download File</a>
```

Here is an example of how to use the `<a>` element to create a link to a location within the same page:

```html
<a href="#top">Go to Top</a>
	and then add an id attribute to the element we want to link to:
<h1 id="top">Top of Page</h1>
```

Here is an example of how to use the `<a>` element to create a link to an email address:

```html
<a href="mailto:someone@example.com">Send Email</a>
```

Here is an example of how to use the `<a>` element to create a link to a phone number:

```html
<a href="tel:+1234567890">+1 234-567-890</a>
```

# INTERMEDITE

<a name="listsandtables"></a>

## Lists and Tables in HTML

HTML provides several elements for creating lists and tables, including:

- `Lists`:
	- `<ul>` - Unordered List, which creates a bullet-point list of items
	- `<ol>` - Ordered List, which creates a numbered list of items
	- `<li>` - List Item, which defines each item in a list

Here is an example of unordered and ordered lists:

```html
<!-- Unordered List -->
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

<!-- Ordered List -->
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

- `Tables`:
	- `<table>` - Defines a table
	- `<tr>` - Defines a table row
	- `<th>` - Defines a table header
	- `<td>` - Defines a table cell

Here is an example of a table:

```html
<table>
  <tr>
	<th>First Name</th>
	<th>Last Name</th>
  </tr>
  <tr>
	<td>Aman</td>
	<td>Khadka</td>
  </tr>
  <tr>
	<td>John</td>
	<td>Doe</td>
  </tr>
</table>
```

We can also use different attributes to customize the appearance of tables, such as: `border`, `cellpadding`, `cellspacing`, `width`, and `height`, `align`, `bgcolor`, `valign`, `colspan`, and `rowspan`, etc.

Here is an example of a table with attributes:

```html
<table border="1" cellpadding="10" cellspacing="0" width="100%" height="100%">
  <tr>
	<th>First Name</th>
	<th>Last Name</th>
  </tr>
  <tr>
	<td>Aman</td>
	<td>Khadka</td>
  </tr>
  <tr>
	<td>John</td>
	<td>Doe</td>
  </tr>
</table>
```

<a name="formsandinputelements"></a>

## Forms and Input Elements in HTML

HTML forms allow us to collect information from users, which can then be sent to a server for processing. The most basic form is created using the <form> element, along with various input elements such as text fields, checkboxes, radio buttons, and more.

Here's a list of some common input elements we might use in a form:

- `<input>` - Defines an input control
- `<textarea>` - Defines a multiline input control (text area)
- `<select>` - Defines a drop-down list
- `<option>` - Defines an option in a drop-down list
- `<button>` - Defines a clickable button
- `<label>` - Defines a label for an `<input>` element

Here is an example of a form with input elements:

```html
<form>
  <label for="fname">First Name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last Name:</label><br>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <select id="email" name="email">
    <option value="gmail">Gmail</option>
    <option value="yahoo">Yahoo</option>
    <option value="hotmail">Hotmail</option>
  </select>
  <button type="submit">Submit</button>
</form>
```

When a user submits the form, the data is sent to the server for processing. To specify where the form data should be sent, we can use the `action` attribute of the `<form>` element. To specify the HTTP method to use when sending the data, we can use the `method` attribute of the `<form>` element. The `method` attribute can be set to either `GET` or `POST`.

The `GET` method is the default method for sending form data, and is typically used for simple forms that don't contain sensitive information. With the `GET` method, form data is appended to the URL as query parameters. For example, if we have a form with two input fields named **name** and **email**, the form data would be sent to the server as follows:

```html
https://amankhadka.com/submit?name=Aman+Khadka&email=amankhadka%40gmail.com
```

The `POST` method is more secure than the `GET` method, as form data is not visible in the URL. Instead, the data is sent in the body of the HTTP request, where it is less susceptible to being intercepted or tampered with. The `POST` method is typically used for forms that contain sensitive information, such as login forms and forms that require a payment.

To specify the method used to send form data, we can use the **method** attribute on the **<form>** element, like this:

```html
<form action="submit" method="POST">
  <label for="fname">First Name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last Name:</label><br>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <select id="email" name="email">
	<option value="gmail">Gmail</option>
	<option value="yahoo">Yahoo</option>
	<option value="hotmail">Hotmail</option>
  </select>
  <button type="submit">Submit</button>
</form>
```

<a name="semantic"></a>

## Semantic elements in HTML

Semantic elements in HTML5 refer to a set of new HTML elements that have been introduced in HTML5 to provide meaning to the structure of web content. These elements are used to describe the type of content they contain, making it easier for both humans and machines to understand the structure of a web page.

Here is a list of some common semantic elements in HTML5:

- `<header>` - Defines a header for a document or a section
- `<nav>` - Defines a set of navigation links
- `<main>` - Specifies the main content of a document
- `<article>` - Defines an independent self-contained article
- `<section>` - Defines a section in a document
- `<aside>` - Defines content aside from the page content
- `<footer>` - Defines a footer for a document or a section
- `<details>` - Defines additional details that the user can view or hide
- `<summary>` - Defines a heading for the `<details>` element

By using semantic elements, we can make our HTML code more readable and understandable. For example, if we have a navigation menu, we can use the `<nav>` element to wrap the menu, like this:

```html
<nav>
  <ul>
	<li><a href="#">Home</a></li>
	<li><a href="#">About</a></li>
	<li><a href="#">Contact</a></li>
  </ul>
</nav>
```

<a name="stylesandcss"></a>

## HTML Styles and CSS

HTML styles refers to the inline styling of HTML elements. We can use the `style` attribute to add styles to HTML elements, like this:

```html
<p style="color: red; font-size: 20px;">This is a paragraph.</p>
```

We don't generally use `HTML` for styling, as it is not very efficient. Instead, we use `CSS` to style our HTML elements. CSS stands for **Cascading Style Sheets**, and it is a language used to style HTML elements. CSS is used to control the layout of multiple web pages all at once. CSS can be added to HTML documents in 3 ways:

- Inline - by using the `style` attribute inside HTML elements
- Internal - by using a `<style>` element in the `<head>` section
- External - by using a `<link>` element to link to an external CSS file

We will learn more about **CSS** later in another tutorial.

<a name="layoutandresponsivedesign"></a>

## HTML Layout and Responsive Design

HTML layout refers to the arrangement of elements on an HTML page and how they fit together to create a visual structure. With HTML, we can use various elements such as `<div>`, `<header>`, `<footer>`, `<nav>`, and `<section>` to define different areas of a page and control the layout of our content.

Responsive design is a technique used to create web pages that look good on all devices, such as desktop computers, tablets, and mobile phones. Responsive web design is achieved by using a combination of flexible layouts, flexible images, and media queries.

There are several different techniques for creating responsive web pages:

- **Media queries**: A media query is a CSS technique that allows us to apply different styles to our HTML elements based on the size of the screen or device. We can use media queries to create different styles for different screen sizes and orientations.
- **Flexbox and Grid**: Flexbox and Grid are CSS layout modules that allow us to create flexible and responsive layouts with ease. With these modules, we can control how elements are arranged on the page, how they adapt to different screen sizes, and how they respond to changes in the viewport.
- **Responsive images**: With responsive images, we can ensure that images are optimized for different devices and screen sizes, by serving different versions of an image based on the size of the screen. This helps to reduce the amount of data that needs to be downloaded, which can improve the loading speed of our pages on mobile devices.

Make our design responsive helps to create a better user experience for our users regardless of the device they are using to access our content.

We will learn deeply about **HTML Layout** and **Responsive Design** in CSS tutorial.

# Advance

<a name = "apisanddynamicwebcontent"></a>

## APIs and Dynamic Web Content

HTML APIs and dynamic web content are advanced concepts in HTML that allow us to create dynamic and interactive web pages. With HTML APIs and dynamic web content, we can create web pages that can update and change in real-time based on user interactions and data from other sources.

Some of the key concepts in HTML APIs and dynamic web content are:

- **HTML APIs** - An API (Application Programming Interface) is a set of protocols and tools for building software applications. With HTML APIs, we can access data from other sources and use it in our HTML pages. For example, we can use APIs to retrieve data from a database, fetch data from a web service, or retrieve information from social media platforms.

- **JavaScript** - JavaScript is a programming language that is commonly used to create dynamic and interactive web content. With JavaScript, we can manipulate HTML elements, change their properties, and add interactivity to our web pages.

- **AJAX** - AJAX (Asynchronous JavaScript and XML) is a technique that allows us to create dynamic web pages that can update content without reloading the entire page. With AJAX, we can send and receive data from a server asynchronously, which means that the page can update content without interrupting the user's experience.

- **WebSockets** - WebSockets is a protocol for real-time communication between a web browser and a server. With WebSockets, we can create real-time applications, such as chat apps and multiplayer games, that can update and change in real-time based on user interactions and data from other sources.

These are some of the most common concepts in HTML APIs and dynamic web content. We will learn more about these concepts in other tutorials.

These advanced concepts in HTML allow us to create dynamic and interactive web pages that provide a better user experience and can respond to changes in real-time. With HTML APIs, dynamic web content, and real-time communication, we can create engaging and dynamic web applications that can adapt to changing user needs and data.

<a name="accessibility"></a>

## Accessibility and Assistive Technologies in HTML

Accessibility and assistive technologies are an important aspect of HTML development that ensure that web pages and web applications can be used by people with disabilities. Accessibility in HTML refers to the practice of designing and developing web pages that can be easily used by people with disabilities, including those with visual, auditory, motor, and cognitive impairments.

Assistive technologies are tools and software that help people with disabilities use computers and the web. Some common examples of assistive technologies include screen readers, magnifiers, and alternative input devices.

To ensure that web pages are accessible to people with disabilities, HTML provides several elements and attributes that can be used to provide additional information and context to assistive technologies. Some of the key elements and attributes include:

- `alt` attribute - The `alt` attribute provides alternative text for images, which can be used by screen readers to describe images to visually impaired users.
- `title` attribute - The `title` attribute provides additional information about an element, which can be used by screen readers to provide additional context to users.
- `label` element - The `<label>` element provides a visible label for form elements, which can be used by screen readers to describe form controls to users.
- `aria` Accessible Rich Internet Applications (ARIA) attributes - ARIA attributes provide additional information about an element, which can be used by screen readers to provide additional context to users.

By incorporating these elements and attributes into our HTML pages and web applications, we can improve the accessibility of our web pages and ensure that they can be used by people with disabilities. This not only makes our web pages and applications more inclusive, but it can also help us reach a wider audience and improve the user experience for everyone who uses our web pages and applications.

<a name="bestpractices"></a>

## Best Practices and Maintenance of HTML Documents

By following best practices and maintaining our HTML documents, we can ensure that our web pages and web applications are well-structured, easy to read, and easy to maintain. Here are some of the best practices that we should follow when creating HTML documents:

- Validate HTML code: Verify that the HTML code is well-formed and complies with the latest standards.
- Use semantic elements: Structure the HTML pages using semantic elements for improved accessibility and context.
- Include alternative text for images: Provide a text description for images using the `alt` attribute for assistive technologies.
- Use descriptive headings: Use descriptive headings, such as `<h1>` through `<h6>`, to structure the HTML pages.
- Use CSS for styling: Separate the presentation from the content by using CSS for styling HTML pages.
- Use a clear naming convention: Adopt a clear and consistent naming convention for HTML files, images, and other resources.
- Keep HTML code organized and well-commented: Keep the HTML code organized and well-commented for improved maintainability.
- Use a code formatter: Use a code formatter to format the HTML code for improved readability.

## Authors

- [@amulifts](https://www.github.com/amulifts)