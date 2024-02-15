
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

When using elements such as `<pre>`, `<code>`, or `<textarea>`, or adjusting whitespace handling via CSS, additional spaces and indentations can have significance. Typically, browsers don't concern themselves with more than a single space.

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

## Unit 4

### HTML Navigation and Linking
-------------------------------

Let's dive into the captivating realm of web links. Nowadays, we hardly pause to think about them, encountering them everywhere online — from navigation bars to menu options, enticing teaser cards, and clickable article titles. It's become second nature.

Now, let's wind back to the 1980s, when computer pioneers were pondering the groundbreaking concept of linking. They were captivated by hypertext, hypermedia, and the very idea of hyperlinks. Picture it: a special spot on a page that could whisk you away to a whole new world with just a click. Pretty mind-blowing, huh?

This fascination endured for over two decades, from the mid-1960s to the early 1990s, until the birth of the web. Even the term "web" reflects this obsession with connecting disparate elements, weaving a complex network of interconnected information. Creating a link may be straightforward in terms of code, but its impact on computing, information exchange, and our modern world is truly profound.

When creating a link, we use the A element, short for anchor, and include an href attribute with a URL enclosed in quotes. This URL determines where the link will take us. Between the opening and closing A tags, we can place text, images, or both to make them clickable. For instance, we can turn the phrase "this is a link" into a clickable link leading to example.com.

By default, the A element is inline and can be inserted within a paragraph or any other text. However, links aren't limited to just text; we can also wrap them around images or more complex elements like teaser cards, allowing us to create a group of linked elements.

URLs can be quite versatile. When linking to another website or a specific page on the web, you can use the entire URL, whether it has a trailing slash or not. These are called absolute URLs and must include the HTTP or HTTPS part, which stands for Hypertext Transport Protocol, defining the web's communication rules.

The difference between HTTP and HTTPS lies in security, with the "S" in HTTPS denoting "Secure." While HTTP was common in the past, experts now recommend HTTPS for improved security. Modern browsers automatically add HTTPS:// when a domain like example.com is entered, prioritizing security.

### HTML URL Pathways
--------------------

When making links, absolute URLs are just one choice. When linking to something within the same site and domain as the page with the link, you can opt for a relative URL instead. For instance, imagine you're working on a website called Awesome Dogs, set to launch at http://www.awesomedogs.com. However, you're currently tinkering with a local version of the site on your computer, adding a menu bar. Later, there will be copies of the site on various servers with different URLs for testing and review purposes.

Using absolute URLs for all links would cause the browser to constantly try accessing pages or files at http://www.awesomedogs.com, which isn't ideal. When working locally, we want links to point to the local files, and when the site's copied to a testing server, links should direct to pages and files there. To achieve this, we need a way to skip the http://www.awesomedogs.com part of the URL but still guide the browser to the files.

Creating a relative URL isn't just handy for the A element (linking); it's also a skill used for referencing image files, video files, CSS, JavaScript files, or any other file where a path is specified.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/65704da8-bd32-4fa0-8ed8-acaf39709736)

When crafting a URL from scratch, it's important to understand file organization. Picture files neatly arranged into different directories or folders. For example, to link to a blog post from March 9th, the browser needs to search inside the "blog" folder and locate the "March-9.html" folder. Filenames come with extensions like .html, .jpg, .css, .js, while folder names are simply named, such as "blog" or "people."

In a URL, slashes indicate delving deeper into the file structure or moving down a level. To create a relative URL, leave out the domain name but include the initial slash at the start. This signals the browser to start from the root level, the outermost top level. Alternatively, you can craft the path relative to the file where the link is written.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/39e19975-dd52-47b9-890f-f965fe369f67)

Here's an example to help grasp how URLs function. Picture a file named styles.css in a directory named CSS. Let's say we want to link to the logo.gif file, found in the images folder, from our CSS file. We've got two ways to write the URL:

1. /images/logo.gif
2. ../images/logo.gif

The first version, /images/logo.gif, crafts a URL relative to the root level, meaning the browser starts searching for the file from the website's root. The second version, ../images/logo.gif, forms a URL relative to the file's location where the URL is written. The ".." followed by a slash signifies going up one level in the directory structure.

So, the URL ../images/logo.gif means starting from the current location, moving up one level, finding the images folder, and then locating the logo.gif file inside it.

Now, let's discuss relative and absolute URLs. When you encounter a URL like http://www.awesomedogs.com/people, it's actually seeking an index.html file inside the people folder. In web development, when a browser receives a URL pointing to a folder, it automatically seeks an index.html file and loads it. This lets us create a clean URL structure using folders. However, this method only applies to HTML files, not images or CSS.

Crafting well-structured and graceful URLs for web pages is an art. Consider how your URLs affect user experience and search engine results. Carefully design URLs, just like any other content. Relative URLs can be incredibly useful, especially for projects shifting between servers.

To sum up, URLs can be relative or absolute. Relative URLs are based on the current file's location, while absolute URLs start from the website's root. Leveraging folders and index.html files allows for clean and user-friendly URLs.

### Navigation
--------------

Now that we've discussed links and URL structures, let's delve into popular methods for creating menus or navigation bars. Picture this: we want to craft a main menu bar for our website, comprising four links: home, people, prices, and contact.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/0f193867-f92c-4e45-9c7e-9c38f24583b5)

Each link is placed within an element containing the correct URL and enclosed in an "li" element to form a list of links. To maintain order, wrap the entire list in a "ul" element, representing an unordered list. Finally, enclose the entire menu in a "nav" element to signify it as the site's navigation.

To style the menu visually, apply CSS styling. Without styling, it appears as a plain list, but it's important for screen readers and assistive devices to recognize it as the main menu. Add attributes to convey its purpose: assign the role "navigation" to the "nav" element, indicating it represents the main navigation, and include an "aria label" for the main menu, offering a descriptive label for screen reader users. Remember, this isn't the only way to correctly markup a main navigation menu; there are various approaches depending on the situation.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/84ae754d-e26c-44ab-b303-fd7fd58d6279)

Let's look at another menu style called a breadcrumb trail. Like the main menu, enclose the breadcrumb links in a "nav" element, but this time use an ordered list ("ol") because the order of the links is important. However, don't label this menu as "navigation"; instead, add an "aria label" of "breadcrumb" to give context when read aloud.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/a596de76-25c8-4fed-85f7-eb5a58310f45)

Now, let's look at the links typically found in a page's footer. These links aren't part of the main site navigation. Simply mark each link as a link and wrap them in a "footer" element. No "nav" element or unordered list is needed here. It's a straightforward representation of two phrases linking to additional content.

As we combine HTML elements, there are numerous options to explore. By carefully considering actions and combining elements to add semantic meaning to our content, we can make the right choices for our projects. Remember, there's no one-size-fits-all approach; it all depends on the specific circumstances and how you want certain elements to appear.

## Unit 5

### HTML Working with Graphics and Images
-----------------------------------------

**Images**

Without images the internet wouldn't be as entertaining as it is today. To add an image to a webpage you use the image element `<img>` with added attributes.

The added attributes are crucial for the image element. We have four attributes and those attributes are the source (src) attribute, the alt attribute and lastly the width and the height attribute.

The source attribute tells the browser which image to load. The alt attribute provides a text description of the image. The width and height attribute determine the size of the image.

When adding an image you need to add an alt attribute. This is very important for people with visual impairment. They can use a screen reader that reads the ALT text aloud to them.

When writing the ALT text you need to of course describe the picture but make it interesting. You can even make it funny or poetic. Just don't decribe it as a photo or make it lengthy. 

Sometimes it is better to leave the alt blank if you gonna repeat yourself or the alt interferes with the picture. 

### Image Formats
-----------------

Image formats are very important when it comes to finding a file format that browsers can understand. New formats are constantly created to find the perfect balance between small file sizes and visually stunning images. We need a huge amount of data to make an image stunning but we also want to minimize the data to ensure faster downloads and prevent excessive data usage for users. Each file format has a different approach to achieve this but the goal is similar. Essentially, we aim for the highest possible quality with the smallest file size achievable.

There are four main file formats commonly used on the web with their own weaknesses and strengths. These formats are GIF, SVG, PNG and JPG.

GIFs (Graphics Interchange Format) are a type of image file commonly used for simple graphics and animations on the internet. They're great at compressing images that have large areas of the same color because they use a technique called palette-based compression. This means that instead of storing each individual color in the image, they create a palette of up to 256 colors and map each pixel in the image to one of those colors. This works well for illustrations with flat colors or simple animations because it keeps the file size small without sacrificing too much quality. However, when it comes to photographs or images with complex color gradients, GIFs fall short. 

SVGs are great for things like logos and icons. They're different from GIFs because they're not made up of tiny dots called pixels. Instead, they're made using instructions that tell the computer how to draw the picture. This means you can make them bigger or smaller without them getting blurry, and they don't take up much space on your computer. SVG stands for Scalable Vector Graphics, and it's like a language that computers understand for making pictures. If you want to learn more about it, there are classes you can take. You can make SVG files using programs like Illustrator or Sketch, and you can use them on the internet just like other picture files.

JPEG (Joint Photographic Experts Group) is a popular file format for storing digital images, especially photographs, due to its efficient compression algorithm. When photos are saved in the JPEG format, they're compressed to reduce file size while retaining visual quality. However, excessive compression can lead to a loss of image detail and quality, commonly referred to as "compression artifacts". When photos are uploaded to websites, it's important to resize and optimize them appropriately to ensure fast loading times. Large, uncompressed or poorly compressed JPEGs can significantly slow down website performance, leading to a negative user experience. To optimize JPEGs for web use, it's essential to strike a balance between image quality and file size. This can be achieved by manually adjusting compression settings or utilizing online tools and services that automatically optimize images for web use.

PNG (Portable Network Graphics) is a modern image format that supports transparency, making it suitable for images where transparency is required, such as logos with transparent backgrounds. It utilizes lossless compression, which means that image quality is not compromised during compression. PNG files can sometimes provide better compression for certain types of images compared to GIF or JPEG files. When manually compressing PNG files, it's advisable to experiment with different compression settings to find the optimal balance between file size and image quality.

### Responsive Images
---------------------

CSS provides a solution for adjusting image sizes to fit various screen sizes, but a challenge arises with large, high-resolution images that have hefty file sizes due to their data volume. This can be problematic for users with slow internet connections or limited data plans as it takes longer to download and can incur higher costs. To tackle this issue, one option is to reduce the size of all images by physically shrinking them, decreasing colored data, and further compressing them, which is effective for smaller screens. However, this approach affects all users, resulting in lower-quality, enlarged images for those with larger desktop monitors. Alternatively, you could opt to keep images small, which may limit your web design options.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/1b7bf596-529b-4a1d-9c33-01d02df580d9)


HTML enables the delivery of various image files to screens of varying sizes. By including multiple image options in the HTML code, browsers, in conjunction with the operating system, consider the device's hardware capabilities and network speed to determine the most suitable image to download. 

To begin, let's start with the basic HTML code for loading an image on a webpage. We use an image element with attributes like source (src), ALT text, width, and height to help identify the loaded image. The image we're using here is 480 pixels wide and looks good when displayed at that size or smaller on certain devices. However, many screens today have higher pixel densities, such as 2X, 3X, or 4X, which allow for more detailed displays. For example, older computers typically have a 1X screen, while newer ones have 2X screens, and cellphones often have 3X screens. Our goal is to ensure our photos look good on all of these screens.

To support these different screens, we create multiple copies of an image with varying resolutions and inform the browser about these options. Then, the device can choose which image to use based on factors like screen density, network connection, and user settings. Even if someone has a high-resolution screen, the browser might opt to download a lower-resolution image.

To illustrate this, let's consider four copies of a photo at different widths: 480, 960, 1440, and 1920 pixels. We duplicate the basic HTML code for displaying the image to make changes and compare the results. We write the code in the usual way, which works well for older browsers, including the source attribute pointing to the 1X version of the image, ALT text, width, and height.

To provide the browser with choices, we simply add a source set attribute. Inside it, we list the images on offer, separated by commas. Each entry includes a URL to the file, the resolution (e.g., 2X, 3X, 4X, 1.5X), and so on. The browser then swaps out one version of the image for another based on what it considers best. This technique is ideal for handling different image sizes for retina and high DPI screens.


### Responsive Width
--------------------

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/619ca3a5-d28e-4c8f-b14c-9baa069fe013)


In this scenario, we're continuing from the previous example where we listed four images in the src set attribute. However, instead of specifying pixel density like 1x or 2x, we're indicating the width of each file: 480w for an image 480 pixels wide and 960w for an image 960 pixels wide.

Now, the browser determines which image to display based on both the device density and the viewport width. However, this approach can pose a problem when the chosen image doesn't fit the desired layout. The browser makes this decision early in the loading process, before it has knowledge of CSS or layout details, and it's unaware of the size of the box where the image will be placed.

To address this issue, we can provide the browser with more information to make a better choice. We use the sizes attribute in HTML to specify which image to use at different breakpoints. This way, the browser can download the appropriately sized image for our layout.

HTML offers powerful options like src set, allowing us to provide a range of images for different resolutions or let the browser choose based on density and viewport width. The sizes attribute enables us to specify how much of the viewport's width the image will occupy at each breakpoint. By furnishing this information in the HTML, we assist the browser in making an informed decision, taking into account network conditions and user preferences.

### Responsive Pictures
-----------------------

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/b592751b-c2b7-41d8-bcba-f02246af85e1)

What if you want to display a different image on a small screen compared to a large screen? For instance, we might want the image to appear tall and narrow on mobile devices, while being short and wide on desktop computers. We could even opt to use an entirely different photo altogether.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/1967bd2e-fbfd-46ac-b588-d699fa292147)

Let's dive into another example. Imagine you have a photo that needs to be displayed differently on various screens: you want to show the whole scene on big screens but focus only on the person's face on smaller ones. Simply using the image element won't suffice, even with added attributes like source set or size. This is where the picture element comes into play.

First, use the image element with ALT text and a URL to the image file to ensure compatibility with older browsers like Internet Explorer 11. Then, wrap this image element with the picture element, acting as a wrapper for the setup. Within the picture element, list alternative options using the source element, providing two options by creating two source elements.

1. For the first source element, use the source set attribute to point to a mobile image file, a cropped version sized at 320 pixels wide. This version will load when the viewport is smaller than 600 pixels.
2. For the other source element, use a kind of media query to specify the image for larger screens, loading the landscape version when the viewport is at least 600 pixels wide. This allows you to optimize the image for different screen sizes efficiently.

In this explanation, we utilized the "source set" attribute in the source element, similar to how it's used in the image element. This means we can apply what we've learned from previous sections to this situation. Various techniques like picture, source, and source set were employed, providing multiple file options for each source set, indicating to the browser how wide each file is. The browser smartly switches between files, using larger ones only when necessary, considering both the viewport size and the retina screen. When the viewport reaches 600 pixels wide, it seamlessly switches from the cropped version to the wide version.

This is why we use these HTML techniques to make images look great on the web while keeping file sizes small.

You might think creating all these files sounds like a lot of work. It does involve some math, but on most websites, the process is automated. Content contributors upload one large image, and server robots handle creating the necessary image files and writing the code. Setting this up might be your responsibility, but once done, everyone benefits.

The effort is worth it. In this demo, image files range from 27k to 593k, saving half a megabyte per photo. If a web page has six photos, that's three megabytes of data saved for users. It's a significant improvement.

### Figcaption and Figures
--------------------------

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/afe227f2-f0f6-4d6d-92c6-94368d6a1665)

First, show a picture of the dog and add a caption to it. Use the figcaption element to wrap the text and designate it as a caption. Then, put the image and the caption together in a figure element. This gives the browser more information about the content, like the relationship between the image and the caption. It is not just a regular paragraph or a generic div. This way, search engines and AI can understand that these two pieces of content are connected. 

Figures can be used for more than just images, too. For example, use them for an interactive graphic. Place it in the same spot where the image element is in the code. The figure and figcaption elements are really useful for anything that serves as a visual illustration or a demonstration of a concept that needs a caption.

## Unit 6

### Working With Media
----------------------

**Working With Audio**

The audio element is different from the image element because it has both an opening and a closing tag. This makes it more modern and gives it more power and flexibility. Just like the image element, we use a source attribute to provide the URL of the audio file.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/19e274b5-960c-4943-896c-25dd0cdd97bc)

There are different audio file formats to choose from. For now, link to an MP3 file. But what does this actually do? Well, nothing useful yet. We need to let the browser know that we want it to provide some controls like a play button, timeline, and volume control. Using the browser's built-in controls is optional.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/d3ab9fca-b0bb-44aa-b779-bbfb276ab5b6)

Instead of using pre-built audio player controls, you have the option to create your own using JavaScript and the HTML media element API. However, for this exercise, we'll keep things simple and just add the "controls" attribute. When this attribute is present, it means we want the controls, so voila! Now there's an audio player on the page. This allows us to play, pause, adjust volume, see the time, and navigate through the timeline. The audio element showcases the power of HTML by providing a range of functionality without needing to build it from scratch.

You might wonder why there's both an opening and closing tag for the audio element. Well, that's because the source element can be used to specify multiple audio files, similar to how the picture element was used.

This can be helpful if a new file format is used that isn't supported in all browsers while providing a fallback for older ones. To achieve this, remove the source attribute from the audio element and place it on a separate source element. This achieves the same outcome as the previous example but allows for the addition of other source elements with alternative audio file formats.

MP3s are widely supported in modern browsers, while OGG had some advantages but didn't gain much popularity. There may be a new format on the horizon, similar to the AV1 video file format, but it's not widely available yet. For this reason, there's currently no recommended second audio format. Nevertheless, it's important to understand the syntax for supporting multiple formats, as it was crucial in the past and will likely be useful again in the near future.

Furthermore, you can provide fallback text within the audio element, which will only be displayed if the browser doesn't understand the audio element at all. This demonstrates the resilience of HTML, where a single set of code can cater to a wide variety of browsers and provide a suitable user experience. The audio element is an excellent tool for embedding audio files and a player on a webpage.

### Working With Video
----------------------

The internet has revolutionized how we connect and share content like movies, TV shows, and educational resources. With the power of the web, embedding videos onto web pages has become effortless using the HTML video element.

Similar to the audio element, the video element also consists of an opening and closing tag. To display a video, simply use the source attribute to specify the video file. Additionally, adding the controls attribute automatically generates a video player by the browser. Seems straightforward, doesn't it? However, there are a couple of considerations that need attention.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/907a7b09-8389-4af7-870d-819129a52a3f)

The first issue revolves around video encoding. In this example, a video file with 480p resolution has been created, compressed using the H.264 codec, and delivered as an MP4 file. 480p signifies the video's resolution of 720 pixels wide by 400 pixels tall, considered standard quality. H.264 was chosen due to its widespread browser support. 

Similar to image formats, such as PNG or JPEG, video files use different codecs for encoding. Since video files contain vast amounts of data, compression is necessary to efficiently transmit them over the internet. Various codecs, like Real Video, Sorenson, Windows Media, Flash, and H.263, have been developed over the years. Until recently, H.264 dominated the scene, despite being proprietary and subject to licensing fees. Efforts are underway to develop an open and non-patented video codec, with AV1 emerging as a promising contender. HTML's video element allows for the inclusion of multiple source files, enabling the use of different codecs like H.264, WebM, and eventually AV1.

The second challenge relates to accommodating users with varying screen sizes and network speeds. While HTML lacks a built-in mechanism for sending different video sizes based on network conditions, major streaming platforms use adaptive bitrate streaming to address this issue. This involves a server farm of transcoding robots that ensure seamless switching between different resolutions as users watch videos. Due to the complexity involved, websites often rely on embed codes from video hosting services instead of directly employing the video element, simplifying the process and leveraging the capabilities provided by such services.

### Working With Captions And Subtitles
---------------------------------------

It's incredible how we can add audio and video to websites, but not everyone can fully engage with this content. Some people may be deaf, while others may have intermittent hearing or difficulty understanding due to various factors. Additionally, even those who can hear may not always find it convenient to listen.

For instance, you might want to watch a video, but using speakers or headphones isn't feasible in certain locations. Alternatively, you might struggle to understand due to the speaker's accent or fast pace. Right now, you might be facing one of these challenges while using captions for a video. Fortunately, the web empowers us to provide content in multiple ways simultaneously.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/ad8adbdd-ebdc-4d3d-9ea5-7ae4cacf4686)

We'll utilize the track element to link it to a text file and add captions to the video. This enhances the video player's functionality, allowing viewers to toggle captions on and off or switch between different subtitle options. On the web, we'll use a file format called WebVTT (Web Video Text Tracks), a simple text file with a .vtt extension that follows a specific convention for providing information. Each line of text in the file is accompanied by a time code, indicating when it should be displayed in the video.

To display these captions on the video, insert a track element within the video element. Similar to the source element, it's one of the options the browser uses to render the video player. On the track element, use the source attribute to specify the file, the kind attribute to indicate that it contains captions, and a label attribute to display the caption option as "English" in the player. Additionally, use the source lang attribute to indicate the language and add a default attribute to make this track the default choice when captions are enabled.

Clicking on the captioning icon reveals options for turning captions off, enabling automatic captioning, or selecting English captions, based on the label set. To provide a different subtitle option like Spanish, create another vtt file for Spanish and add another track element to the video element. Set the kind attribute to "subtitles," the source lang attribute to "es" for Spanish, and the label attribute to "Español." Now, a second choice for subtitles appears in the list, including Spanish subtitles.

The kind attribute offers other options too. For example, using "descriptions" allows us to create a vtt file describing visual elements for visually impaired users. "Chapters" provide a text file listing different sections of the video, allowing users to jump to specific parts.

Platforms like YouTube or Vimeo allow uploading caption files and provide similar functionality. Captions and subtitles are not only powerful but also often legally required, making content more accessible and potentially expanding the audience base. Adding captions can lead to increased traffic!

### Embedding Media via Iframes
-------------------------------

There's a wide array of content that can be embedded on a webpage, such as maps from Google or Mapbox, code demos from CodePen or Glitch, or slide decks from Speaker Deck or Notist. It's common to embed complex content from a service that manages the technical aspects. Rather than creating a mapping service, slide deck system, code demo platform, or adaptive bitrate server from scratch, you can leverage someone else's toolkit and embed the results onto your website. So, what HTML knowledge is required to facilitate this process?

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/f05e8162-02ee-4705-a3e1-e1269e2fbbdb)

Understanding every detail isn't necessary because YouTube's engineers have handled it. However, with HTML knowledge, you can recognize key elements. For instance, the iframe element has attributes like height and width that you can adjust, and the src attribute specifies the video file's source. Although iframes are powerful, we must consider security concerns when embedding code from other websites.

![image](https://github.com/MihlaliKota/Intro-To-HTML-CSS/assets/133135575/1d8affcc-bc84-4199-bc27-dc2bc67f67f1)

When working with a content management system (CMS) like WordPress or Drupal, set up by someone else, copying and pasting random embed codes from other websites might not be straightforward. These CMS platforms typically have specific methods for allowing URLs or shortcodes from trusted sources. For embedding items like YouTube videos, it's advisable to seek guidance from someone proficient in using the CMS.

When constructing a website, it's crucial to consider security implications related to the iframe element. If multiple individuals will be contributing content to the system, it's important not to indiscriminately allow all iframes without considering security measures. However, if you're the sole contributor posting videos on the website, security concerns are less pressing.
