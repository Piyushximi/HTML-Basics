# HTML-Basics


### Table of Contents 


| No. | Questions | No | Questions |
| ----- | ------------------- | ---- | ------------------- |
| 1 | [What are the building blocks of HTML5?](#1) | 11 | [](#11) |
| 2 | [semantic tags](#2) | 12| [](#12) |
| 3 | [DOCTYPE](#3)| 13| [](#13) |
| 4 | [What are attributes](#4)| 14| [](#14) |
| 5 | [span and div tag / block and inline elements](#5)| 15| [](#15) |
| 6 | [What are semantic and non-semantic elements](#6)| 16| [](#16) |
| 7 | [](#7)| 17| [](#17) |
| 8 | [](#8)| 18| [](#18) |
| 9 | [](#9)| 19| [](#19) |
| 10 | [](#10)| 20| [](#20) |


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
* **<meta charset=”utf-8″>** is an HTML tag that is used to indicate the web page’s character encoding. In order to see the correct content, the tag’s function is used which let the browser know what character encoding was used in the HTML document.

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

**[⬆ Back to Top](#table-of-contents)**

### 8

**[⬆ Back to Top](#table-of-contents)**

### 9

**[⬆ Back to Top](#table-of-contents)**

### 10

**[⬆ Back to Top](#table-of-contents)**

### 11

**[⬆ Back to Top](#table-of-contents)**

### 12

**[⬆ Back to Top](#table-of-contents)**

### 13

**[⬆ Back to Top](#table-of-contents)**

### 14


**[⬆ Back to Top](#table-of-contents)**

### 15

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




