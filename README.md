# HTML Tutorial

In this tutorial, i'll start from the very beginning. You don't need to know anything about HTML or anything about code to start.

## Table of Contents

 * [HTML](#html)
 	* [History](#history)
	* Basics
		* [Basic HTML document syntax](#syntax)
		* [Basic HTML document structure](#structure)
		* [HTML Elements and Attributes](#elementsandattributes)
		* [List of HTML Elements and Attributes](#listofelementsandattributes)
		* [Text Formatting in HTML](#textformatting)
		* Adding Images and Media to HTML Pages
		* Creating Links in HTML
	* Intermediate
		* HTML Lists and Tables
		* HTML Forms and Input Elements
		* Semantic Elements in HTML5
		* HTML Styles and CSS
		* HTML Layout and Responsive Design	 	
		* Putting it all together so far
	* Advanced
		* HTML APIs and Dynamic Web Content
		* Accessibility and Assistive Technologies in HTML
		* Best Practices and Maintenance of HTML Documents

<a name="html"></a>

## HTML

HTML stands for **HyperText Markup Language**. It is a **markup language** used to create and structure web pages. HTML is the **foundation** of all websites and provides the **structure** for displaying text, images, videos, and other types of content on the web. HTML can be written using a text editor and when you save the extension of the file must be `.html` and viewed in a web browser. When a web browser loads an HTML document, it displays the content and structure defined by the HTML code.

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
<a href="https://www.google.com"> <!-- Opening tag -->
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

In the above table, i have only listed the most **commonly used** HTML elements and attributes. There are many more HTML elements and attributes that you can learn about from the official HTML documentation.

The official website for HTML (HyperText Markup Language) is maintained by the World Wide Web Consortium (W3C), which is the main international standards organization for the Internet. The URL for the HTML specification is: [Click Here](https://www.w3.org/TR/html/)

<a name="textformattingin"></a>

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

When the above HTML code is rendered in a browser, it will look like this:

![Text Formatting in HTML](https://github.com/amulifts/html-tutorial/blob/main/images/textformatting.png)



## Authors

- [@amulifts](https://www.github.com/amulifts)