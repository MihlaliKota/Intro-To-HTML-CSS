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

Superscripts, subscripts and small text are used to mark up text that has a different meaning to the overall content. Usually used to mark up copyright in the footer.

For superscripts we use the `<sup>` element to display inline text as superscript. Usually used for mathematical formulas, ordinal numbers and superior lettering.

For subscripts we use `<sub>` element to display inline text as subscript. Usually used for footnote numbers, mathematical formulas and chemical formulas.

The `<small>` HTML element represents side-comments and small print, like copyright and legal text, independent of its styled presentation. 

## Unit 3

### HTML Capabilities
---------------------

**Troubleshooting and Debugging HTML Code**

HTML code, like any other code, will encounter errors and this is where debugging comes in. Popular browsers like Firefox offer tools that can assist you further by creating it's own version of your code and finding out the errors you have within your code.

It will be displayed to you in different screens. These three screens hold different information about your code. When you open inspect or developer tools there will be HTML on the left and first screen, CSS on the middle screen and more options on the right screen.

The left screen will showcase the HTML but more importantly it will showcase the Document Object Model (DOM) Tree created by the browser and will try to fix any mistakes you've made along the way. When these errors have been found, you simply head over to your code and fix it. 

### HTML Attributes
-------------------

HTML also contains attributes. These attributes are used on elements and add more power to any of these elements.

Certain attributes are specific to particular elements. While others work with some elements and not all of them. For example, the daytime attribute, which we only use with the time element. While some attributes work with most elements, they won't be able to work with all of them. 

The most used attributes are the "class" and "id" attributes. 

The class attribute allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class.

The id attribute is similar to the class attribute, but we can only use unique names once on an entire HTML page. IDs can be used for CSS targeting, but are more specific, which can sometimes cause issues. As a result, CSS developers usually prefer using classes.

However, IDs come in handy when we need to address specific elements in JavaScript or targeted links. The uniqueness of an ID name ensures that there will always just be one element with that ID, making it useful for interacting with JavaScript or links. Regardless of the use case, class and ID attributes provide a way to name HTML elements and reference them in other parts of the code stack.

HTML offers many attributes that enhance user interaction and provide hooks into browser power. These attributes, such as "content editable," allow interaction with the screen, keyboard, and assistive devices. They facilitate the editing capability within the browser.

### ARIA Roles
--------------

ARIA Roles serve as additional attributes for HTML elements, enhancing their significance and aiding browsers in understanding their representation. The aim is to prioritize the use of appropriate HTML elements to accurately convey the content's meaning, minimizing the reliance on ARIA Roles.

Nevertheless, there are instances where real-world situations diverge from ideal scenarios, necessitating compromises in coding. It becomes problematic if these compromises render a website challenging or impossible for individuals with disabilities to access. In fact, in many jurisdictions, having an inaccessible website for people with disabilities is unlawful. This underscores the substantial influence HTML has on human rights.

ARIA Roles become relevant when we aim to offer crucial details to assistive technologies such as screen readers, braille displays, and magnifiers, ensuring complete accessibility of a website. ARIA emerged as the web started supplanting native applications, proving particularly beneficial in guaranteeing that all users can access the complete functionality of a complex interface within an application.

The accessibility tree serves as a counterpart to the DOM tree, generated by the browser based on the website's content. While the DOM tree outlines the HTML's structure, the accessibility tree plays a vital role for assistive devices such as screen readers, enhancing the user experience. It enables them to navigate through the content more effectively.

Upon examining the accessibility tree, it's evident that it treats content as distinct text containers. However, this approach can lead to suboptimal experiences, such as individual letters of a word like "hello" being pronounced separately. To address this issue, we can employ ARIA to enhance accessibility.

ARIA stands as a potent asset, significantly boosting web accessibility. It merits further exploration, especially for teams grappling with semantic HTML or constructing intricate application interfaces. ARIA Roles equip you with essential tools to ensure universal accessibility for your website.

### Formatting HTML
-------------------

When using elements such as <pre>, <code>, or <textarea>, or adjusting whitespace handling via CSS, additional spaces and indentations can have significance. Typically, browsers don't concern themselves with more than a single space.

Programmers believe that code readability improves when comments are added to explain its purpose, typically inserted in HTML by typing `"<!--" at the start and "-->"` at the end. Although browsers ignore these comments, code editors like Notepad++ can display them or remarks in a grayed-out style, facilitating quick identification of commented-out code and reducing confusion when it behaves unexpectedly.

The debate on whether to use uppercase or lowercase in HTML is pretty interesting. Back in the day, folks tended to capitalize all their HTML elements. But as HTML evolved, lowercase became the norm. Surprisingly, browsers handle both styles just fine. You can still find old-school websites with all-caps HTML and newer ones rocking lowercase. Nowadays, lowercase is the usual way to go, though some still stick to all caps. Personally, lowercase is easier on the eyes for us.

You might've noticed that some HTML tags are super short, like `<p>` or `<i>`, while others are longer, like `<article>` or `<video>`. The deal is, back when HTML was born in the late '80s and early '90s, computer whizzes were all about saving space because computers had limited resources. Think one measly megabyte of RAM and a puny 20 megabytes of hard drive space! So, every character in a file mattered.

As tech got better and computers got more memory, saving a few characters wasn't as crucial as making code easy for humans to read and understand. So, newer HTML tags started using full words instead of short forms. This switch made it simpler for English speakers to grasp the code. Nowadays, the length of a tag can tell us how old it is.

The newer elements always have both tags, like the video element, but some of the older ones don't have a closing tag. Take the image element, for instance. Back in the '90s, folks were like, "Why bother with a closing tag if we don't need one?" But things changed, and it became best practice to add a slash at the end of elements without a closing tag, making them self-close. For years, everyone insisted on using the slash. But around 2010, people started caring less about it. Browsers are cool with different formatting options. Ultimately, it's up to you how you want to do it.

### Unusual Characters
----------------------

So, what about those `<`, `>`, and & symbols in HTML? Well, when we want to include them in our content, things get interesting. If we put spaces around them, they show up as regular content. But if we start writing something that looks like an HTML element, poof, it disappears! The browser thinks it's part of the HTML code and hides it. Now, if you're using WordPress or markdown, no worries – they usually handle these symbols for you. But sometimes, you might need to watch out for them yourself.

n HTML, we've got something called character entities. They look like this: an ampersand, a short code, and a semicolon. When we toss them into an HTML file, they magically turn into the specific characters we want. We've used this trick to swap out every "greater than" or "less than" symbol with its character entity equivalent.

The W3C has this neat chart with all these character entities listed, which can be super helpful. These entities also come to the rescue when you need to type characters that aren't on your keyboard. For example, if you need a copyright symbol, just type ampersand, copy, semicolon. Sure, you could copy and paste the character or learn the keyboard shortcut, but using HTML character entities is another way to get the job done.

Let's talk about the non-breaking space, which serves a special purpose. Normally, spaces in text let lines break and keep words together. But when there's not enough room for a whole sentence, the browser tries to find a good place to wrap the text. It checks for any regular space where words have a gap between them.

Instead of relying on a regular space, HTML offers a special type known as a non-breaking space. This instructs the browser to keep words together without breaking the line. For example, if we want "Lebron" and "James" to stick together in a sentence, we can use " " to insert a non-breaking space between them, ensuring they stay on the same line.

Additionally, non-breaking spaces can be used to insert multiple spaces between words. While multiple spaces are typically ignored by the browser, non-breaking spaces are recognized, allowing for consistent spacing. HTML character entities, like non-breaking spaces, ensure precise display of desired characters on webpages.






