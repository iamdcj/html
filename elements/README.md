# HTML elements

The elements in an HTML document are the building blocks of a webpage; the building blocks of the building block.

They wrap around the content; text or multimedia; image, video or audio present in a document, providing meaning and structure to the page.

Some HTML elements are specific to the content they contain, others are more general purpose, usually wrap related elements in a common container.

### Structure

HTML elements consist of an opening tag `<div>`, some content, and a closing tag `</div>`;

`<div>content</div>`

### Nesting Elements

HTML elements can be placed inside other elements - this is called nesting.

Example
The following example consists of a paragraph<p> tag and a nested <em> tag:

<p>My name is David, however I <em>love</em> being called <strong>Dave </strong></p>

Rules of nesting
In the above example you can see that nested elements must be closed first; the <em> element is closed, then the <strong> element, finally the <p> element.

It is essential to close the nested elements in the correct order, else the browser’s error handling will take effect, and dependant on the browser engine you could get unexpected, and usually negative results.

### VOID / Self-closing Elements

There are some elements which deviate from the standard structure; they only consist of a single tag, and this tag makes up the element - these are referred to as empty/void/self-closing elements.

The most common 'void' element is arguably the image element; <img> - there is a least one of these present in most web pages on the WWW.

The lack of closing tag prevents them from wrapping/containing content, so the content is instead provided to the element via an [attribute](../attributes)

<img src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png">
