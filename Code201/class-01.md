# Code 201 - Reading 1

## Getting Started

1. Compose a short poem describing how HTTP sends data between computers.

    Who is this?  
    This is who.  
    I'd like to get something,  
    I'd like to send something,  
    And here it is.

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.  

    According to [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Glossary/Parse):  

    ''The browser parses HTML into a DOM tree. HTML parsing involves tokenization and tree construction. HTML tokens include start and end tags, as well as attribute names and values.''

    By order - the HTML is parsed first, and sources like images are loaded asynchonously, but scripts (usually JavaScript) encountered will pause HTML parsing unless directed otherwise, and then finally, CSS is applied.

3. How can you find images to add to a Website?

    Besides your own images, sites like Unsplash have high quality images free to use commercially, and in a draft stage, there are sites with free filler images. Google images, when set to a Creative Commons license, and sites like Wikimedia are other possible sources, but in any case, you must be careful to have the rights to publish.

4. How do you create a String vs a Number in JavaScript?

    - Numbers use numerals and optionally decimals, like 2.
    - Strings use single or double quotes, like "2".  

    I tend to use double quotes to make inner quotes within a string easier to read, using inner single quotes rather than escape characters.  

5. What is a Variable and why are they important in JavaScript?

    Variables can store data that changes - without it, implementing any change via a script would be much more difficult, or in practical terms, impossible.

## Introducing HTML

1. What is an HTML attribute?

    Attributes are properties that modify HTML elements.

2. Describe the Anatomy of an HTML element.

    HTML Elements are surrounded by related tags, for opening and closing, unless an Empty Element, which uses two of the same tags.  The elements may have attributes for styling or function, as well as inner text values.

3. What is the Difference between \<article> and \<section> element tags?

    Google's top result from [StackOverFlow](https://stackoverflow.com/questions/7549561/section-vs-article-html5#:~:text=A%20section%20is%20basically%20a,document%20can%20be%20an%20article.) had this to say:

    "A section is basically a wrapper for h1 (or other h tags) and the content that corresponds to this. An article is essentially a document within your document that is repeated or paginated... like each blog post on your document can be an article, or each comment on your document can be an article."

    Elsewhere, like GeeksForGeeks, has similar ideas.  Sections are a semantic div for a new area, while articles tend to designate the content of that area.

    Unlike a generic div (I believe - still need to confirm this), it's notable that both section and article will likely change how the browser shows other contained elements. For example, an \<h1> within a \<section> may be much smaller than an \<h1> alone.

4. What Elements does a “typical” website include?

    - Head: helps browsers and search engines read the file, can include a page title, icon, language, script and styling sources, along with metadata such as a page description.
    - Body: all content, including headers and navlinks, main content, including graphics, lists, and input boxes, and footers, with data such as copyright and contact info - the body may also have inline styling and scripts.

5. How does metadata influence Search Engine Optimization?

    Metadata is intended to help Search Engine Optimazation, and meta data tags should be used carefully, as they can  raise or lower a site's ranking.

6. How is the \<meta> HTML tag used when specifying metadata?

    The meta tag is used for metadata that isn't covered by other more semantic metadata tags like \<title>. It is an empty element, so there's no child elements or closing tags. Meta tags often denote the "charset" of text, such as the HTML5 standard "utf-8".

## Miscellaneous

### How to Start to Design a Website

1. What is the first step to designing a Website?

    Wireframing (using rough outlines, iteratively made more detailed) is a common first step, although this assumes that certain important questions have been answered, as discussed next.

2. What is the most important question to answer when designing a Website?

    Who is using the site and for what? - this is the most important question, and the "For what?" or "Why?" of the site is the central question upon which everything must be designed. Of course, in the end, a basic answer to all questions of who, what, when, where, why, and how should be considered.

### Semantics

1. Why should you use an \<h1> element over a \<span> element to display a top level heading?

    The \<h1> element is explicitly designed to mark top level headings, while \<span> is a more generic tag used to mark any group for styling.

    Explicit code is usually good practice.

2. What are the benefits of using semantic tags in our HTML?

    Semantic tags are more human-friendly when used correctly, and this can be important for code maintenance or even security.

### Javascript

1. Describe 2 things that require JavaScript in the Browser?

    Handling user input, especially from the keyboard, and creating dynamic elements generally relies on JavaScript.

2. How can you add JavaScript to an HTML document?

    Designate a script source file in the heading, or add script tags inline - this is how to add JS to HTML.

## What I Want to Know More About

Everything. :smiley: No seriously, since we're pretty early in the full-stack web dev journey, I'll stick to the core documents and vanilla methods, but soon enough I would like to dive into common industry frameworks and coding practices.  

[Back to Home](../index.md)
