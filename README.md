# HTML-Basics


### Table of Contents 


| No. | Questions | No | Questions |
| ----- | ------------------- | ---- | ------------------- |
| 1 | [What are the building blocks of HTML5?](#1) | 11 | [Svg and Canvas](#11) |
| 2 | [semantic tags](#2) | 12| [css selectors](#12) |
| 3 | [DOCTYPE](#3)| 13| [Pseudo-classes and pseudo-elements](#13) |
| 4 | [attributes](#4)| 14| [grid and flexbox](#14) |
| 5 | [span and div tag / block and inline elements](#5)| 15| [CSS BEM](#15) |
| 6 | [semantic and non-semantic elements](#6)| 16| [](#16) |
| 7 | [ `section`, `div` or `article`](#7)| 17| [](#17) |
| 8 | [Difference between Select and Datalist](#8)| 18| [](#18) |
| 9 | [How to make page responsive](#9)| 19| [](#19) |
| 10 | [iframe and how it works](#10)| 20| [](#20) |


### 1
## Q. What are the building blocks of HTML5?

* **Semantics**: allowing you to describe more precisely what your content is.
* **Connectivity**: allowing you to communicate with the server in new and innovative ways.
* **Offline and storage**: allowing webpages to store data on the client-side locally and operate offline more efficiently.
* **Multimedia**: making video and audio first-class citizens in the Open Web.
* **2D/3D graphics and effects**: allowing a much more diverse range of presentation options.
* **Performance and integration**: providing greater speed optimization and better usage of computer hardware.
* **Device access**: allowing for the usage of various input and output devices.
* **Styling**: letting authors write more sophisticated themes.

**[⬆ Back to Top](#table-of-contents)**

### 2
### What are the semantic tags available in html5?

HTML5 semantic tags define the function and the category of your text, simplifying the work for browsers and search engines, as well as developers.

HTML5 offers new semantic elements to define different parts of a web page:

* `<article>`
* `<aside>`
* `<details>`
* `<figcaption>`
* `<figure>`
* `<footer>`
* `<header>`
* `<main>`
* `<mark>`
* `<nav>`
* `<section>`
* `<summary>`
* `<time>`

**Syntax:**

```html
<!DOCTYPE html> 

<html>  
   <head> 
      <meta charset = "utf-8"/> 
      <title>...</title> 
   </head> 
  
   <body> 
      <header>...</header> 
      <nav>...</nav> 
      
      <article> 
         <section> 
            ... 
         </section> 
      </article> 
      <aside>...</aside> 
      
      <footer>...</footer> 
   </body> 
</html> 
```

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>

### Why you would like to use semantic tag?

* Search Engine Optimization, accessibility, repurposing, light code. 
* Many visually impaired person rely on browser speech and semantic tag helps to interpret page content clearly.
* Search engine needs to understand page content to rank and semantic tag helps.
* Semantic code aids accessibility. Specially, many people whose eyes are not good rely on speech browsers to read pages to them. These programs cannot interpret pages very well unless they are clearly explained.
* Help Search engines to better understand pages. Search engine need to understand what your content is about when rank you properly on search engines. Semantic code tends to improve your placement on search engines, as it is easier for the "search engine spiders" to understand.
* It\'s easier to read and edit, which saves time and money during maintenance.

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>


**[⬆ Back to Top](#table-of-contents)**

### 3

### What does a `<DOCTYPE html>` do?

* **<!DOCTYPE>** All HTML documents must start with a <!DOCTYPE> declaration. The declaration is not an HTML tag. It is an "information" to the browser the version and type of HTML being used in the document. In HTML 5, the declaration is simple: <!DOCTYPE html>
* **For Response need to add tag**  `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
* **Character Encoding** **<meta charset=”utf-8″>** is an HTML tag that is used to indicate the web page’s character encoding. In order to see the correct content, the tag’s function is used which let the browser know what character encoding was used in the HTML document.

**[⬆ Back to Top](#table-of-contents)**

### 4
### What are attributes?

Each tag can take in additional attributes that change the way the tag behaves. For example, an input tag has a type attribute img tag src attribute

**[⬆ Back to Top](#table-of-contents)**

### 5

## Q. What is difference between `span` tag and `div` tag?

The primary difference between div and span tag is their default behavior. By default, a `<div>` is a **block-level-element** and a `<span>` is an **inline element**.

* `<div>` is a block level element which means it will render it on it\'s own line with a width of a 100% of the parent element.
* `<span>` is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it\'s content.

```html
<div>Demo Text, with <span>some other</span> text.</div>
```

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>

## Q. What are optional closing tag?

`<p>, <li>, <td>, <tr>, <th>, <html>, <body>`, etc. don\'t have to provide end tag. Whenever browser hits a new tag it automatically ends the previous tag. 

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>

## Q. What is a self closing tag?

In HTML5 it is not strictly necessary to close certain HTML tags. The tags that aren\'t required to have specific closing tags are called “self closing” tags.

An example of a self closing tag is something like a line break (`<br />`) or the meta tag (`<meta>`). This means that the following are both acceptable:

```html
<meta charset="UTF-8">
...
<meta charset="UTF-8" />
```

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>

## Q. Explain the difference between block elements and inline elements?

* block elements `<h1>, <p>, <ul>, <ol>, <li>`,
* inline elements `<span>, <a>, <strong>, <i>, <img>`

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>

**[⬆ Back to Top](#table-of-contents)**

### 6
### What are semantic and non-semantic elements?

* **Semantic elements**: clearly describes its meaning to both the browser and the developer.
For example: `<form>`, `<table>`,  `<article>`, `<aside>`, `<details>`, `<figcaption>`, `<figure>`, `<footer>`, `<header>`, `<main>`, `<mark>`, `<nav>`, `<section>`, `<summary>`, `<time>` clearly defines its content.
  
* **Non-semantic elements**: `<div>` and `<span>` tells nothing about its content.


**[⬆ Back to Top](#table-of-contents)**

### 7
### When should you use `section`, `div` or `article`?

* `<section>`, group of content inside is related to a single theme, and should appear as an entry in an outline of the page. It\'s a chunk of related content, like a subsection of a long article, a major part of the page (eg the news section on the homepage), or a page in a webapp\'s tabbed interface. A section normally has a heading (title) and maybe a footer too.

* `<article>`, represents a complete, or self-contained, composition in a document, page, application, or site and that is, in principle, independently distributable or reusable, e.g. in syndication. This could be a forum post, a magazine or newspaper article, a blog entry, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.

* `<div>`, on the other hand, does not convey any meaning, aside from any found in its class, lang and title attributes.

<div align="right">
    <b><a href="#table-of-contents">↥ back to top</a></b>
</div>


**[⬆ Back to Top](#table-of-contents)**

### 8

### What is difference between Select and Datalist?

For the select element, the user is required to select one of the options you\'ve given. For the datalist element, it is suggested that the user select one of the options you\'ve given, but he can actually enter anything he wants in the input.

**1. Select:**

```html
<select name="browser">
  <option value="firefox">Firefox</option>
  <option value="ie">IE</option>
  <option value="chrome">Chrome</option>
  <option value="opera">Opera</option>
  <option value="safari">Safari</option>
</select>
```

**2. Datalist:**

```html
<input type="text" list="browsers">
<datalist id="browsers">
  <option value="Firefox">
  <option value="IE">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>
```


**[⬆ Back to Top](#table-of-contents)**

### 9
### How to make page responsive?

Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones).

**1. Setting the viewport:**

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

**2. Responsive Images:**

If the CSS width property is set to 100%, the image will be responsive and scale up and down

```html
<img src="img.png" style="width:100%;">
```

**3. Show different Images depending on Browser Width:**

The HTML `<picture>` element allows you to define different images for different browser window sizes.

```html
<picture>
  <source srcset="img_small.jpg" media="(max-width: 600px)">
  <source srcset="img_large.jpg" media="(max-width: 1500px)">
  <source srcset="img.jpg">
  <img src="img_small.jpg" alt="Image">
</picture>
```

**4. Responsive Text Size:**

The text size can be set with a "vw" unit, which means the "viewport width". That way the text size will follow the size of the browser window.

```html
<h1 style="font-size:10vw">Hello World</h1>
```

**5. Media Queries:**

Using media queries you can define completely different styles for different browser sizes.

```css
/* Use a media query to add a breakpoint at 800px: */
@media screen and (max-width: 800px) {
  .left, .main, .right {
    width: 100%; /* The width is 100%, when the viewport is 800px or smaller */
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

### 10
### What is an iframe and how it works?
The `<iframe>` HTML element represents a nested browsing context, embedding another HTML page into the current one. Each embedded browsing context has its own **session history** and **document**. The browsing context that embeds the others is called the parent browsing context. The topmost browsing context — the one with no parent — is usually the browser window, represented by the **Window** object.

**Example**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 iframe</title>
  </head>
  <style type="text/css">
  iframe {
    border: 1px solid #333;
    width: 50%;
  }
  .output {
    background: #eee;
  }
  </style>
  <body>
    <p>The Inline iFrame Example</p>
    <iframe id="inlineFrameId"
      title="Inline iFrame Example"
      width="300"
      height="200"
      src="https://www.openstreetmap.org/export/embed.html?bbox=-0.004017949104309083%2C51.47612752641776%2C0.00030577182769775396%2C51.478569861898606&layer=mapnik">
        Sorry your browser does not support inline frames.
    </iframe>
  </body>
</html>
```

**The Iframe Tag Attributes:**

|Attribute       | Description                |
|----------------|----------------------------|
|allow           |indicates what features the iframe is allowed to use (e.g. fullscreen, camera, autoplay)|
|allowfullscreen |grants or denies permission for the iframe to appear in full-screen mode|
|height           |sets the height of the iframe (if not specified, the default height is 150 pixels)|
|loading         |sets lazy loading or eager loading for the iframe|
|referrerpolicy  |sets what referrer information should be sent in the request for the iframe|
|src             |the address of the resource included in the iframe|
|width           |sets the width of the iframe (if not specified, the default width is 300 pixels)|

*Note: Because each browsing context is a complete document environment, every `<iframe>` in a page requires increased memory and other computing resources.*




**[⬆ Back to Top](#table-of-contents)**

### 11
## Q. What is difference between SVG and Canvas?

**1. SVG:**

The Scalable Vector Graphics (SVG) is an XML-based image format that is used to define two-dimensional vector based graphics for the web. Unlike raster image (e.g. .jpg, .gif, .png, etc.), a vector image can be scaled up or down to any extent without losing the image quality.

There are following advantages of using SVG over other image formats like JPEG, GIF, PNG, etc.

* SVG images can be searched, indexed, scripted, and compressed.
* SVG images can be created and modified using JavaScript in real time.
* SVG images can be printed with high quality at any resolution.
* SVG content can be animated using the built-in animation elements.
* SVG images can contain hyperlinks to other documents.

**Example:**

```html
<!DOCTYPE html>
<html>
   <head>
      <style>
         #svgelem {
            position: relative;
            left: 50%;
            -webkit-transform: translateX(-20%);
            -ms-transform: translateX(-20%);
            transform: translateX(-20%);
         }
      </style>
      <title>HTML5 SVG</title>
   </head>
   <body>
      <h2 align="center">HTML5 SVG Circle</h2>
      <svg id="svgelem" height="200" xmlns="http://www.w3.org/2000/svg">
         <circle id="bluecircle" cx="60" cy="60" r="50" fill="blue" />
      </svg>
   </body>
</html>
```

**2. Canvas:**

Canvas is a HTML element is used to draw graphics on a web page. It is a  bitmap with an “immediate mode” graphics application programming interface (API) for drawing on it. The `<canvas>` element is only a container for graphics. In order to draw the graphics, you are supposed to use a script. Canvas has several strategies when it comes to drawing paths, boxes, circles, text & adding images.

**Example:**

```html
<!DOCTYPE html>
<html>
   <head>
      <title>HTML5 Canvas Tag</title>
   </head>
   <body>
      <canvas id="newCanvas" width="200" height="100" style="border:1px solid #000000;"></canvas>
      <script>
         var c = document.getElementById('newCanvas');
         var ctx = c.getContext('2d');
         ctx.fillStyle = '#7cce2b';
         ctx.fillRect(0,0,300,100);
      </script>
   </body>
</html>
```

**Differences:**

|SVG	                |Canvas                                         |
|-----------------------|-----------------------------------------------|
|Vector based (composed of shapes)	|Raster based (composed of pixel)
|Multiple graphical elements, which become the part of the page's DOM tree|	Single element similar to <img> in behavior. Canvas diagram can be saved to PNG or JPG format|
|Modified through script and CSS	|Modified through script only
|Good text rendering capabilities	|Poor text rendering capabilities
|Give better performance with smaller number of objects or larger surface, or both	|Give better performance with larger number of objects or smaller surface, or both|
|Better scalability. Can be printed with high quality at any resolution. Pixelation does not occur	|Poor scalability. Not suitable for printing on higher resolution. Pixelation may occur |


**[⬆ Back to Top](#table-of-contents)**

### 12
### What are the css selectors?

A CSS selector is the part of a CSS rule set that actually selects the content you want to style.

**i) Universal Selector**: The universal selector works like a wild card character, selecting all elements on a page. Every HTML page is built on content placed within HTML tags. Each set of tags represents an element on the page.

```css
* {
   color: green;
}
```

**ii) Element Type Selector**: This selector match one or more HTML elements of the same name.

```css
ul {
   list-style: none;
   border: solid 1px #ccc;
}
```

```html
<ul>
  <li>Fish</li>
  <li>Apples</li>
</ul>
<div class="example">
  <p>Example paragraph text.</p>
</div>
<ul>
  <li>Maple Syrup</li>
</ul>
```

**iii) ID Selector**: This selector matches any HTML element that has an ID attribute with the same value as that of the selector.

```css
#container {
   width: 960px;
   margin: 0 auto;
}

// <div id="container"></div>
```

**iv) Class Selector**: The class selector also matches all elements on the page that have their class attribute set to the same value as the class.

```css
.box {
   padding: 20px;
   margin: 10px;
   width: 240px;
}
// <div class="box"></div>
```

**v) Descendant Combinator**: The descendant selector or, more accurately, the descendant combinator lets you combine two or more selectors so you can be more specific in your selection method.

```css
#container .box {
   float: left;
   padding-bottom: 15px;
}
```

This declaration block will apply to all elements that have a class of box that are inside an element with an ID of `container`. It’s worth noting that the `.box` element doesn’t have to be an immediate child: there could be another element wrapping `.box`, and the styles would still apply.

```html
<div id="container">
  <div class="box"></div>
  <div class="box-2"></div>
</div>
```

**vi) Child Combinator**: A selector that uses the child combinator is similar to a selector that uses a descendant combinator, except it only targets immediate child elements.

```css
#container > .box {
   float: left;
   padding-bottom: 15px;
}
```

The selector will match all elements that have a class of `box` and that are immediate children of the `#container` element. That means, unlike the descendant combinator, there can’t be another element wrapping `.box`—it has to be a direct child element.

```html
<div id="container">
  <div class="box"></div>

  <div>
    <div class="box"></div>
  </div>
</div>
```

**vii) General Sibling Combinator**: A selector that uses a general sibling combinator matches elements based on sibling relationships. The selected elements are beside each other in the HTML.

```css
h2 ~ p {
   margin-bottom: 20px;
}
```

In this example, all paragraph elements (`<p>`) will be styled with the specified rules, but only if they are siblings of `<h2>` elements. There could be other elements in between the `<h2>` and `<p>`, and the styles would still apply.


**viii) Adjacent Sibling Combinator**: A selector that uses the adjacent sibling combinator uses the plus symbol (+), and is almost the same as the general sibling selector. The difference is that the targeted element must be an immediate sibling, not just a general sibling.

```css
p + p {
   text-indent: 1.5em;
   margin-bottom: 0;
}
```

In this example will apply the specified styles only to paragraph elements that immediately follow other paragraph elements. This means the first paragraph element on a page would not receive these styles. Also, if another element appeared between two paragraphs, the second paragraph of the two wouldn’t have the styles applied.

```html
<h2>Title</h2>
<p>Paragraph example.</p>
<p>Paragraph example.</p>

<div class="box">
  <p>Paragraph example.</p>
  <p>Paragraph example.</p>
</div>
```

**ix) Attribute Selector**: The attribute selector targets elements based on the presence and/or value of HTML attributes, and is declared using square brackets

```css
input[type="text"] {
   background-color: #444;
   width: 200px;
}
//<input type="text">
```

The attribute selector can also be declared using just the attribute itself, with no value, like this:

```css
input[type] {
   background-color: #444;
   width: 200px;
}
```

**x) Pseudo-class**: A pseudo-class uses a colon character to identify a pseudo-state that an element might be in—for example, the state of being hovered, or the state of being activated.

```css
a:hover {
   color: red;
}
```

**xi) Pseudo-element**: A CSS pseudo-element is used to style specified parts of an element. For example, it can be used to:

* Style the first letter, or line, of an element
* Insert content before, or after, the content of an element 

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      p::first-line {
        color: #ff0000;
        font-variant: small-caps;
      }

      p::first-letter {
        color: #ff0000;
        font-size: xx-large;
      }

      h1::before {
        content: url(smiley.gif);
      }

      h1::after {
        content: url(smiley.gif);
      }

      ::selection {
        color: red;
        background: yellow;
      }
    </style>
  </head>
<body>
  <p>
     <h1>Heading.<h1>
  </p>
</body>
</html>
```

**[⬆ Back to Top](#table-of-contents)**

### 13
### What is the difference between Pseudo-classes and pseudo-elements?

A pseudo-class is a selector that assists in the selection of something that cannot be expressed by a simple selector, for example `:hover`. A pseudo-element however allows us to create items that do not normally exist in the document tree, for example `::after`.

**Pseudo-classes:**  

Pseudo-classes select regular elements but under certain conditions, like when their position relative to siblings or when they\'re under a particular state. Here is a list of pseudo-classes in CSS3:

**a) Dynamic pseudo-classes:**  

* :link
* :visited
* :hover
* :active
* :focus

**b) UI element states pseudo-classes:**  

* :enabled
* :disabled
* :checked

**c) Structural pseudo-classes:**  

* :first-child
* :nth-child(n)
* :nth-last-child(n)
* :nth-of-type(n)
* :nth-last-of-type(n)
* :last-child
* :first-of-type
* :last-of-type
* :only-child
* :only-of-type
* :root
* :empty

**d) Other pseudo-classes:**  

:not(x)
:target
:lang(language)

**Pseudo-elements:**  

Pseudo-elements effectively create new elements that are not specified in the markup of the document and can be manipulated much like a regular element. 

* ::before
* ::after
* ::first-letter
* ::first-line
* ::selection


**[⬆ Back to Top](#table-of-contents)**

### 14
## Q. When to use css grid and flexbox?

* CSS Grid Layout is a **two-dimensional** system, meaning it can handle both columns and rows, unlike flexbox which is largely a **one-dimensional** system (either in a column or a row).
* A core difference between CSS Grid and Flexbox is that — CSS Grid’s approach is **layout-first** while Flexbox’ approach is **content-first**. If you are well aware of your content before making layout, then blindly opt for Flexbox and if not, opt for CSS Grid.
* Flexbox layout is most appropriate to the components of an application (as most of them are fundamentally linear), and **small-scale** layouts, while the Grid layout is intended for **larger-scale** layouts which aren’t linear in their design.
* If you only need to define a layout as a row or a column, then you probably need flexbox. If you want to define a grid and fit content into it in two dimensions — you need the grid.


**[⬆ Back to Top](#table-of-contents)**

### 15
## Q. What is CSS BEM?

The BEM (**Block Element Modifier**) methodology is a naming convention for CSS classes in order to keep CSS more maintainable by defining namespaces to solve scoping issues. A Block is a standalone component that is reusable across projects and acts as a "namespace" for sub components (Elements). Modifiers are used as flags when a Block or Element is in a certain state or is different in structure or style.

```css
/* block component */
.block {
}

/* element */
.block__element {
}

/* modifier */
.block__element--modifier {
}
```


**[⬆ Back to Top](#table-of-contents)**

### 16

**[⬆ Back to Top](#table-of-contents)**

### 17

**[⬆ Back to Top](#table-of-contents)**

### 18

**[⬆ Back to Top](#table-of-contents)**

### 19

**[⬆ Back to Top](#table-of-contents)**

### 20




