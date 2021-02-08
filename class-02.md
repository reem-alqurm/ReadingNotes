# HTML & JavaScript 

## HTML Text


* When you creat a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

* we have to types of markup :
  - Structural markup: the elements that you can use todescribe both headings and paragraphs.
  - Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.

## Structural Markup 

### Headings

  * HTML has six "levels" of headings:
- `<h1>` is used for main headings
- `<h2>` is used for subheadings If there are further sections
under the subheadings then the `<h3>` element is used, and so on...
* Browsers display the contents of headings at different sizes. The contents of an `<h1>` element is the largest, and the contents of an `<h6>` element is the smallest.

### Paragraph

* To create a paragraph, surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag.

* The browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

### Bold & Italic

* By enclosing words in the tags `<b>` and `</b>` we can make
characters appear bold.

* By enclosing words in the tags `<i>` and `</i>` we can make
characters appear italic.

### Superscript & Subscrip

* The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like
raising a number to a power such as 22 .

* The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.
### Line Breaks & Horizontal Rules 

* if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`.

* To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the `<hr />` tag.

## Semantic Markup

* There are some text elements that are not intended to affect the
structure of your web pages, but they do add extra information to the
pages — they are known as semantic markup.

### Strong & Emphasis

* The use of the `<strong>`element indicates that its content has strong importance.
For example, the words contained in this element might be said with strong emphasis. By default, browsers will show the contents of a `<strong>` element in **bold**.
* The`<em>` element indicates emphasis that subtly changes
the meaning of a sentence.
By default browsers will show the contents of an `<em>` element
in *italic*.
### Quotations

* There are two elements commonly used for marking up
quotations:
   - The `<blockquote>` element is used for longer quotes that take
up an entire paragraph. 
   - The `<q>` element is used for shorter quotes that sit within
a paragraph.

### Abbreviations & Acronyms 

* If you use an abbreviation or an acronym, then the `<abbr>`
element can be used. A title attribute on the opening tag is
used to specify the full term.

### Citations & Definitions 

* When you are referencing a piece of work such as a book,
film or research paper, the `<cite>` element can be used to indicate where the citation is
from.
* The `<dfn>` element is used to indicate the defining instance of
a new term.
### Author Details

* The `<address>` element has quite a specific use: to contain
contact details for the author of the page.

## Introducing CSS 

* CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

* The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

* Using CSS, you could add a border around any of the boxes, specify its width and height, or add a background color. You could also control text inside a box — for example, its color, size, and the typeface used.

* CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

![Image](https://images.slideplayer.com/32/9811421/slides/slide_5.jpg)

* The `<link>` element can be used in an HTML document to tell the
browser where to find the CSS file used to style the page. It is an
empty element (meaning it does not need a closing tag), and it lives inside the `<head>` element.

* You can also include CSS rules within an HTML page by placing
them inside a `<style>` element, which usually sits inside the `<head>` element of the page.

### CSS Selectors 
* There are many different types of CSS selector that allow you to
target rules to specific elements in an HTML document. 
- Here are some :
![Image](https://cf.ppt-online.org/files/slide/k/Kbp3XcismqFREgGuz9OBIWY1vDx6MwHVeZQjC5/slide-8.jpg) 


### CSS rules usually appear in a separate document, although they may appear within an HTML page.


*****************************************************************

## Basic JavaScript Instructions 

* A script is a series of instructions that a computer can follow one-by-one.
* Each individual instruction or step is known as a statement. Statements should end with a semicolon.
* JavaScript is case sensitive so hourNow means something different to HourNow or HOURNOW. 
* A statement is an individual instruction that the computer should follow. Each one should start on a new line and end with a semicolon. This makes your code easier to read and follow. 
* Some statements are surrounded by curly braces; these are known as code blocks. The closing curly brace is not followed by a semicolon.

* You should write **comments** to explain what your code does.

* A script will have to temporarily store the bits of information it
needs to do its job. It can store this data in **variables**. 

* JavaScript distinguishes between numbers, strings, and true or false values known as Booleans. 
* An array is a special type of variable. It doesn't just store one value; it stores a list of values. 
   - ex: `colors= ['white',black','custom'];`

* JavaScript contains the following mathematical operators, which you can use with numbers.
![Image](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Arithmatic-Operators.png) 

## Decisions and Loops 

### USING COMPARISON OPERATORS :
At the most basic level, you can evaluate two variables using a
comparison operator to return a true or false value. 

![Image](https://4.bp.blogspot.com/--zckn2RyLhU/V8--sd4WHlI/AAAAAAAAES8/Dztqu2tWZL8zleQ5lBLyLOapkCwxX64LwCLcB/s640/Capture.PNG)

### USING LOGICAL OPERATORS : 
* see the below table to understand what is a logical opratoer :
![Image](https://miro.medium.com/max/1270/1*SX5-E0EOlfb-HfuttEblHw.png)

![Image](https://res.cloudinary.com/practicaldev/image/fetch/s--AaxWL-V---/c_imagga_scale,f_auto,fl_progressive,h_720,q_auto,w_1280/https://cl.ly/7d9cf8370380/Image%25202018-11-15%2520at%25209.59.47%2520AM.png)
## Loops 
#### Here are some points to consider when you are working with loops.
* break : This keyword causes the termination of the loop and tells
the interpreter to go onto the next statement of code outside
of the loop.
* continue : This keyword tells the interpreter to continue with the current iteration, and then check the condition again. 
![Image](https://pbs.twimg.com/media/ClQlhDRWYAAunF8.jpg)

*****************************************************************


## [ Home ](https://reem-alqurm.github.io/ReadingNotes/)
