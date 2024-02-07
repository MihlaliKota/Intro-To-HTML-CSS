# Intro-To-HTML-CSS

## WEEK 1

## Unit 1

### Introduction To HTML
-------------------------

<u>**What Is HTML?**</u>

HTML stands for HyperText Markup Language. It is used in all froms of web technology. It is used for content output such as words, images, video, audio, forms and interactive experiences. It is a solid foundation for everything in the digital realm.

The same way humans can communicate with each other through language, computers can also speak to each other through, what we call, programming languages. These programming languages are very consistent and logical in nature. Through practice and methodical learning, humans can learn these programming languages and create websites, applications, software and all sorts of creations. The internet is where computers and humans intersect and communicate with each other. 

Even though we can learn what programming languages are, how to understand them and how to even use them, computers can't necessarily fully understand humans due complex languages, nuances and countless words that are being created on a daily. Artificial intelligence (AI) is the solution to this problem. AI allows computers understand human communication on the web. 

Now HTML is somewhat the same as AI in the function to minimize complexity between humans and computers. HTML allows us to bridge the gap between human and programming languages. Think of it like a skeleton on a human body. Without bones none of us would be able to walk, run or do anything for that matter. We need bones for our bodies to function and perform the way it does, the same way we need HTML for websites, applications and software. 

### The Function of HTML
----------------------------

The World Wide Web consists of three programming languages: HTML, CSS, JavaScript. These programming languages all have a different function.

**HTML** 

HTML is used to markup the contents of a website and letting the user know about the various elements on the page/pages of a website.

HTML is known as a declarative language. This means it has a very straightforward structure without any programming logic, loops, or functions.
The magic lies in using the right vocabulary and declarations.

HTML is very simple and because of that it is very resilient and robust. Even when you misspell and/or forget to add certain elements, HTML will still display your page and and try to guess what you meant with your mistakes.

HTML can take a lot of abuse and still produce results.

**CSS**

CSS stands for Cascading Style Sheets and is responsible for the styling of the web page and how everything looks.

CSS is responsible for the colors, fonts and the size of various elements. Animations and interactions can also be added to web pages to have a much cooler or just better appeal.

CSS has some complexity to it though. If you have an error within your code the browser will skip that error and try to make the rest of your code work. So when you have errors it will still compile the best it can.

**JavaScript**

JavaScript is a programming language that creates interactivity within web pages. Websites that usually have cool and fancy complex interfaces are mostly/usually programmed in JavaScript.

JavaScript is a bit complex compared to HTML and CSS but that complexity is all worth it when it comes to the functions that you can create with JavaScript. The only drawback with JavaScript is that, unlike HTML and CSS, if it encounters an error within it's code it won't compile or try to guess what you mean by the code you've inputted. For this reason, it is more fragile than HTML and CSS.

You might be asking why we need multiple programming languages to create a website. The reason is because when you create a website it has to work for at least several years without any updates. The web runs on different platforms such as Mac, Windows, iOS, Android, Linux and even more platforms and devices. The web was specifically created to be as diverse as possible across many different platforms to allow us all to share content.



To make all of this possible, three programming languages are needed and that's HTML, CSS and JavaScript. Each language has a role to play to contribute to the resilience, robustness and power of the programmed website. Most programmers will try to use the most robust and simple features of this combination of programming languages and leave out any complexity. For instance, if something can be done in HTML, most will only use HTML for that certain use case to minimize complexity and take advantage of the robustness of HTML. If there's a need for another programming language then it will be used if HTML can't satisfy the particular function.


## Unit 2

### Text Formatting
--------------------

<u>**HTML Syntax**</u>

HTML is a programming language used to bring structure to a web page, as previously touched on. To mark different elements, we use tags which are enclosed in greater-than and less-than symbols. These tags come in two types: opening tags and closing tags. For example, the opening tag for a paragraph is `<p>` and the closing tag is `</p>`.

These tags are like packages enclosing the content and essentially work together to define the element. There are special cases though where an element won't need an opening and closing tag. For example, a line break `<br>` is used to create a new line and doesn't require a closing tag.

It is entirely possible to also have elements within elements and have them function. This called nesting. It allows you to apply multiple elements on one piece of content.

When looking at HTML documents you'll start to realize that most HTML documents are just HTML elements nested within each other. If you look at the structure you will mostly find that it looks like a tree with parents, children and siblings when looking at. 

The browser can identify when such a structure is setup and will build a big family tree and show how it all relates to one another. This is called a DOM Tree. The DOM stands for Document Object Model. The DOM becomes very important when working with CSS and JavaScript.

The DOM Tree is quite important when it comes to the user experience. 

How we nest elements is very importants as it conveys what we are doing and how we will do it. Silly mistakes like not closing tags can have a huge impact on your HTML document.

<u>**HTML Paragraphs**</u>

The HTML `<p>` element defines a paragraph. This element has an opening tag of `<p>` and `</p>`.

Paragraphs are usually shown as blocks of text but can also be any structural grouping of related content, such as images or form fields.

Paragraphs are regarded as block-level elements.

**HTML Headlines**

HTML Headlines are usually used for various titles, headlines, and subheadings. Headlines play a crucial role into dividing the content into smaller and more digestible chunks for people to comprehend the content and structure of how the content is laid out.

HTML Headlines come in six different types from `<h1>` to `<h6>`. These headlines will come in different sizes. The higher the number the smaller the size of the headline.

**HTML Bold and Italics**

There are four elements related to this, two for bold and two for italics. The aim for the bold and italics is to essentially emphasize words in paragraphs.

For the italics, the elements being used are `<i>` and `<em>`. The `<i>` element is used to define a part of the text in an alternate voice or mood. The `<em>` is used to to define emphasized text.

For the bold, the elements being used are `<b>` and `<strong>`. The `<b>` element is used to define bold text without any extra importance. The `<strong>` element is used to to define text with strong importance.

**HTML Lists**

We use three different types of lists in HTML for different purposes. The types of lists are unordered lists, ordered lists, and definition lists or description lists.

*Unordered Lists*

The use case for unordered lists is exactly as it sounds. The list does not exactly follow a specific order. It is the most commonly used list out of the three.

To use this element we usually enclose any item of the list with an `<li>` element and once we are done enclosing all the texts with that element we nest all the items in a `<ul>` element which stands for unordered list.

*Ordered Lists*

The ordered list is quite similar to the unordered list with a slight difference. Instead of using the previous element to wrap all our items in a list, we use the `<ol>` element which displays a specific order and will show a numbered list to define this.

*Definition Lists*

The definition list is quite different to the unordered and ordered list in that it is used to define terms and shows their description.

To create a definition list we need to wrap all the terms/headings in a `<dt>` element, which stands for definition term. After that, we wrap all descriptions in a `<dd>` element which stands for definition description. When you done wrapping all these elements in the correct order you gonna nest it in a `<dl>` element which stands for definition list.   

**HTML Quotes**

*Cite and Blockquotes*

The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

The HTML `<blockquote>` element defines a section that is quoted from another source. Browsers usually indent these elements.

To use these elements together we usually wrap a quote from another source or from a quote in the original context of the content  in a `blockquote` element and use the `<cite>` element to credit the person the quote is attributted to.

*Inline Quotes*

The `<q>` HTML element indicates that the enclosed text is a short inline quotation. Most modern browsers implement this by surrounding the text in quotation marks. This is like blockquotes with the slight difference of only using it on quotes that are short and don't need paragraph breaks.

*The (Date) Time element*

The `<time>` HTML element represents a specific period in time. It may include the datetime attribute to translate dates into machine-readable format, allowing for better search engine results or custom features such as reminders.

**HTML Superscripts, Subscripts and Small Text**

## Unit 3

### HTML Capabilities
---------------------

**Troubleshooting and Debugging HTML Code**



