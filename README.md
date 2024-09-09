# Front-end-Class3

Front-end Crash course for Kadoos Private educational Institute. (HTML, CSS, and Bootstrap)

## <span style="color: #ebce14;">Basics of the Web Applications</span>

### <span style="color: #44cecc;">Internet and Network Foundations</span>

- <span style="color: Red;">Basics</span>

  - Network History
  - All kinds of Applications
  - Web Applications
  - ![](Images/6.png)

- <span style="color: Red;">Web Applications</span>

  - Static
  - Dynamic

- <span style="color: Red;">Two Important aspects of Web Applications</span>

  - Front-end
  - Back-end
  - Server and apps

- <span style="color: Red;">Front-end Basics</span>

  - Blocks
  - Design
  - Functionalities

- <span style="color: Red;">Technologies</span>

  - HTML (Hyper Text MarkUp Language)
  - CSS (Cascaded Style Sheet)
  - JavaScript

### <span style="color: #44cecc;">HTML</span>

- <span style="color: Red;">What is the HTML?</span>

  - Browsers can Handel all things (inspect)
  - You can Work on A single text file
  - Talk about editors and IDEs
  - Browsers can paly a lot of different things like `HTML`, `SVG`, end etc.
  - Talk about postfix and extensions
  - The first version of HTML was written by `Tim Berners-Lee` in `1993`
  - What creates a Html file (open a notepad and save as file)
  - Talk about tags(Basics) angle brackets `<>`
  - A tag with its closing tag is a markup element
  - Four Important basic Tags `<!Doctype html>`, `<HTML>`, `<Head>`, and `<Body>`
  - Talk about Browser developer tools like `inspect`
  - Markup elements
  - Heading tags
  - Paragraph tag
  - Line Break tag (Empty element)
  - Line tag (self clos tag) is a empty element
  - Comment Tag `<!-- -->`
  - &nbsp mark for space

- <span style="color: Red;">Lists</span>

  - Unordered lists `<ul>`
  - Ordered lists `<ol>`
  - List items `<li>`

- <span style="color: Red;">Tables</span>

  - Table tag `<table>`
  - Row tag `<tr>`
  - Data tag `<td>`
  - Column tag `<th>`

- <span style="color: Red;">Links</span>

  - Link to outside tag `<a href="www.google.com">`<span style="color: Red;">Google</span>`</a>`
  - Define Attributes `href`
  - Link to inside tag `<a href="#Birds">` and `<a name=Birds>`

- <span style="color: Red;">Images</span>

  - Image tag `<img>`
  - Source attribute
  - Size Attributes
  - Use optimize size for your images
  - Alt Attributes

- <span style="color: Red;">Nested Elements</span>

  - `<html>` is root elements
  - Child elements
  - Parent elements
  - Mismatch Elements

- <span style="color: Red;">HTML Forms</span>

  - To collect data to do something
  - Implement a textbox element/ control (`type="text"`)
  - Attributes are belong to CSS and JavaScript courses
  - Change your textbox size (`size="50"`)
  - Implement a label element
  - `placeholder` attribute show a guid and default value inside your textbox or textarea elements
  - Add a Multi line textbox (textarea)
  - We can use just simple text as label
  - Implement a submit button (`type="submit"`)
  - Implement a Radio button (`type="radio"`)
  - Radio's name should be the same
  - Implement a CheckBox button (`type="checkbox"`)
  - Use `checked="checked"` for checked a box by default
  - Implement a Numbers field (`type="number"`)
  - For restrict user from entering random number we need JavaScript
  - Set `min=""` and `max=""` for your Numbers input
  - Implement a DropDownList using `select` tag
  - For Items we use `<option>` tag
  - Implement a date element `type="date"`
  - Use `<fieldset` tag to give a nice style to your page
  - `<legend>` tag add a nice title to your fieldset

- <span style="color: Red;">HTML Attributes</span>

  - Differences between tags and elements
  - A specific attribute gives extra information about a particular element
  - Place attributes only in opening tag
  - Some attributes can be placed in every HTML elements tag, Like `class=""` attribute
  - On the other hand some attributes comes with a specific element, like `for=""` attribute

- <span style="color: Red;">Meta Tags</span>
  - Is always put inside `<head>` elements
  - These elements give more information to search engines about your page
  - Meta tags is self-content tags and don't need close tag
  - Description Meta tag uses only 155 character
  - Keywords used for demonstrate the content of page to some search engin (Except Google)
  - Meta tags also give extra information about Author or language
- <span style="color: Red;">Special Characters</span>

  - There is scape characters in HTML5
  - ![](Images/2.png)

- <span style="color: Red;">Bold and Italic style</span>

  - Use `<b>` tag to make a text bold
  - Use `<Strong>` tag to make a text bold
  - `<strong>` tag has special uses (ex: text speech programs) but ` <b>` tag is only for styling
  - Special features can be add to `<strong>` tag in `HTML6`
  - Use `<i>` tag to make a text italic
  - Use `<em>` tag to make a text bold
  - `<em>` tag has special uses (ex: text speech programs) but ` <i>` tag is only for styling

- <span style="color: Red;">Iframe Element</span>

  - Use this element to embed content of another page to your page (for adverts, navigation, or images)

- <span style="color: Red;">Super & Sub Script</span>

  - Its about topography and placing text and symbols at the top or bottom of other text

- <span style="color: Red;">Title and Alternative</span>

  - In HTML5 we can use `title` attribute in every elements to show information about them when mouse hover over them
  - `alt` attribute show information about absence of an element

- <span style="color: Red;">Audio Tag</span>

  - To place an audio in your page ypu can use `<audio>` tag
  - It support three different format file (`.mp3, .wav, and .ogg`)
  - It's important that you should place a `control` attribute for your audio element but you can choose arbitrary name for it
  - For placing different format of a file we can use `<source>` tag
  - By `autoplay` attribute you can play your file automatically
  - By `loop` attribute you can play your file in infinite loop
  - By `draggable="true"` attribute you can drag your player everywhere

- <span style="color: Red;">Video Tag</span>

  - To place an audio in your page ypu can use `<video>` tag
  - It support two different format file (`.mp4 and .ogg`)
  - For placing different format of a file we can use `<source>` tag

- <span style="color: Red;">DOCTYPE</span>

  - It's not a actual HTML tag
  - It shows the version of HTML that we use in our document

- <span style="color: Red;">Document Object Model (DOM)</span>

  - It's a model that present HTML elements in our document
  - When a web page is loaded, the browser creates a Document Object Model of the page
  - The HTML DOM model is constructed as a tree of Objects
  - ![](Images/3.png)
  - Use w3 validator to check your HTML codes
  - https://validator.w3.org/

- <span style="color: Red;">HTML Semantic Elements</span>

  - A semantic element clearly describes its meaning to both the browser and the developer
  - A semantic Web allows data to be shared and reused across applications, enterprises, and communities
  - ![](Images/4.png)
  - ![](Images/5.png)

- <span style="color: Red;">Additional HTML Tags</span>

  - Use `<pre>` tag for preformatted text
  - Use `<blockquote cite="">` tag for A section that is quoted from another source
  - Use `<code>` tag for code snippets
  - Use `<dl>` tag for present a description list (`<dt>`, `<dd>`)

- <span style="color: Red;">Exercise</span>
  - Section1: ![](Images/ex1.png)
  - Section2: ![](Images/ex2.png)
  - Section3: ![](Images/ex3.png)

<br>
<br>

### <span style="color: #44cecc;">CSS</span>

- <span style="color: Red;">What is the CSS?</span>

  - <span style="color: #0099ff;">CSS</span> is `Cascading Style Sheet` for describing look and formatting documents written in a markup language
  - Adds style to your HTML
  - By CSS you can have control on your website look without changing your HTML
  - Talk about another HTML tag: `<style>`
  - select a tag in your HTML document ex:`h1 {  ...  }`
  - Each one of these style is a CSS `property`
  - Statement of changing in CSS : `Property : value`

- <span style="color: Red;">Changing font color, type, and size</span>

  - Use `color`, `font-size`, and `font-family` property to change respectively color, size, and font type of your text
  - `px` stands for `pixel`
  - Selecting by `p` type change all paragraphs in our page

- <span style="color: Red;">Multi Selecting Tags</span>

  - `h1, h2 {   ....  }`
  - By writing another selector you can change one of your multiple selected tags

- <span style="color: Red;">Border Property</span>

  - `border-bottom`, `border-top` ...
  - Imply to the combine values

- <span style="color: Red;">CSS Inheritance and Overriding</span>

  - What you get with hierarchy is inheritance
  - ![](Images/7.png)
  -
  - Child inherit their properties from their parents
  - To change something individually you should change that in the child tag using overriding rule
  - By define a property for a child individually an override happens and it's `overriding`

- <span style="color: Red;">Using Classes</span>

  - Create two paragraph with different classes (`blue`, `red`) and define classes in style tag
  - Definition class statement : `class="class_name"`
  - It don't need it to put class attribute closing tag and remember attribute always comes in opening tag
  - By removing tag name before dot notation it can be apply on all tags which have a specific class attribute
  - You can use multiple class name in your class attribute
  - Apply it by using `text-decoration` property

- <span style="color: Red;">Font Family</span>

  - You can define which font apply on your text
  - If none of those fonts don't exist in the client computer system default font apply on your text
  - It's better to put font family property in your `body` tag

- <span style="color: Red;">Font Weight Property</span>

  - Use `normal`, `bold`, `bolder`, and `lighter` for check this property
  - Some font families belongs to specific computers like `Mac`

- <span style="color: Red;">External Style Sheet</span>

  - There is three way to apply stylesheet on HTML
  - `internal style sheet`, `external style sheet`, and `inline style sheet`
  - Internal stylesheet is good if you have only one page
  - It's more realistic to use external stylesheet
  - In a real world developing a website it is possible that you use all three way for styling
  - Create a separate file for your stylesheet `.css`
  - Transfer your code to your new file
  - Create a link tag in your head element
  - Define true address for your link

- <span style="color: Red;">Text Decoration</span>

  - Talk about `text-decoration` property and `line-through`, `underline`, and `overline` values (`none`)
  - Talk about italic style by `font-style` and creating three different paragraph and classes
  - To make a word italic it's better to use HTML tags

- <span style="color: Red;">Web Colors</span>

  - T
