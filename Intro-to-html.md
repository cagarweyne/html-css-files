# Introduction To HTML


## What is HTML?

Whenever you access a website, the webserver will send you the resource that you requested. This means that you will receive at a bare minimum two documents, a HTML and CSS file. The HTML file contains the structure of the website, just like you would give any document structure such as a title, heading, and paragraphs, while a HTML document contains the same structure that tells your browser how to render the web page. 

The second file that you will most certainly receive when you make a request for a website is a CSS file. Whilst the HTML file species the structure of the document, the CSS file tells the browser how that documents looks like from colors to layout. Many years ago, it was quite normal to receive just one file that contained both the HTML and CSS, but those days are long gone and it is best practice to separate the structure of a webpage from its styling. This means that whenever you are looking at a website, your browser has received both HTML and CSS files from a web server that hosts the site being accessed.

The web browser, this could be any web browser such as Google Chrome, Internet Explorer, Firefox etc, interprets the HTML and CSS code to create the page that you see. Small websites are created using just HTML and CSS, but larger websites make use of other technologies such as databases and advanced server side programming languages. However, HTML and CSS are the gateway to any website or app online, as without these two technologies, no one will be able to use the website.

## HTML Tags, Attributes and Elements 

As I’ve mentioned already, HTML is the structure of a website. Think of it like a house, the bricks that form the structure and its shape. HTML describes the structure of web pages and HTML stands for Hyper Text Mark-up Language. As the name suggests, it’s a markup language that dictates how the information is marked up on a web page. If you have ever used word processing software such as Microsoft Word, you will be familiar with headings, subheadings, lists, and paragraphs. 

When you want to add any of these features in word processing software, for example a heading, you can simply highlight the text that you wish to use as a heading and select the appropriate heading such as heading 1 from the dropdown menu and the text you selected will now be a heading 1. With a word processor, there is an underlying program that interprets your selections and makes the changes that you can see on the screen. You can replicate the same structure on a web page, but you don’t have the luxury of drop down menus, instead you have to tell the browser how to structure the web page using HTML code.

## HTML terms 

Whilst creating your first web page, you will likely encounter a few terms being used constantly. Once you understand what they are, you will become familiar with all of them, but the most common terms that you will hear about all the time are elements, tags, and attributes.

# Elements 

Elements are the backbone of any web page, and you’ll see these elements in the source code for all web pages after the `<!DOCTYPE html>` declaration, we’ll learn about the `<!DOCTYPE html>` soon. Elements define the structure and content of objects within a page. Some of the more frequently used elements include multiple levels of headings, identified as `<h1>` through `<h6>` elements, and paragraphs identified as the `<p>` element. Elements are identified by the use of less-than and greater-than angle brackets, `<>`, surrounding the element name. Thus, an element will look like: `<body>`.

## Tags

When you use the less-than and greater-than angle brackets and surround them over an element, this creates what is known as a tag. Tags most commonly occur in pairs of opening and closing tags. Opening tags mark the beginning of an element, this consists of a less-than sign followed by an element’s name, and then ends with a greater-than sign; for example, `<body>`. The content that falls between the opening and closing tags is the content of that element. For example, a paragraph will have an opening tag of `<p>` and a closing tag of `<p>`. What falls between these two tags will be the content of the paragraph.

## Attributes 

Elements can have attributes; these are additional values that configure the elements or adjust their behavior in various ways to meet a certain criteria. The most common attributes include the id attribute, which identifies an element; the class attribute, which is used for styling a group of elements using CSS; the src attribute, which specifies a source for embeddable content such as the source for an image; and the href attribute, which provides a hyperlink reference to a linked resource. Attributes are defined within the opening tag, after an element’s name, and include a name and a value. The format for these attributes consists of the attribute name followed by an equals sign and then the attribute value surrounded by quotes.

For example, an `<a>` element including an href attribute would look like: `<a href="http://fullstackstudent">Fullstackstudent</a>`. This piece of HTML code will display the text “link” on the web page and will take users to http://fullstackstudent.com/ upon clicking the “link” text. The anchor element is declared with the opening `<a>` and closing `</a>` tags encompassing the text, along with the hyperlink reference attribute and value that are declared with href="http://fullstackstudent" in the opening tag.
  
## Tools of the trade 

HTML documents are plain text documents saved with an .html file extension rather than a .txt file extension.  So, really, almost any text editing tool will suffice. However, authoring websites is an iterative process, and you will be running multiple languages like HTML, CSS, and later on, JavaScript. Therefore, writing everything by hand will be very time consuming. A good text editor will help you speed up the development process and catch any syntax errors, (these are typos and characters or strings incorrectly placed) that you might miss.

Text or code editors, as they are sometimes called, come in all shapes and sizes and you have many different options both paid and free. However, at minimum, you will need a text editor that has: 

- Line Numbers 
- Formatting options 
- Syntax highlighting 
- Code support for other languages – HTML, CSS, and JavaScript

If you’re new to web development, and you don’t have experience with text editors, I highly recommend that you try out several different types of text editors before settling on a favorite. This is because choosing a text editor is an important decision that will impact your workflow and productivity when it comes to building websites. It’s worth mentioning that a text editor that works for one developer might not be the best solution for another, so it really comes down to personal, workflow, and productivity factors in choosing a text editor. 

When you’re starting out in web development, it is highly recommended to start with a code editor that is easy to set up and use. Not only will this allow you to be productive from the very start, but it also means that you don’t have to spend a tremendous amount of time learning the specifics of the text editor. With text editors, nothing is set in stone and as you gain more experience, you can always move to a more complex text editor if you find that your current one is limited in features that you need. 

In web development, speed is an integral part of the creation process, and this is something that you will need to consider when choosing a text editor. Text editors should be lightweight and fast. This is an important feature that you should carefully look for. So, in your quest to find your ideal text editor, if you find that the text editor feels sluggish and unresponsive at times, then this is a sign that it might not be a suitable text editor for you. Slow and sluggish text editors can add hours or even days to your development time.  

Now we’ve talked a lot about the different features that a text/code editor should have and you’re probably wondering what are some of the popular text editors that are in use in the industry since there are so many to choose from. The most popular text editors, not in any order, are: 

- Sublime Text - (sublimetext.com)
- Brackets - (brackets.io)  
- Atom - (atom.io)  
- Coda - (panic.com/coda) 
- Notepad++ - (notepad-plus-plus.org)
- BBEdit - (barebones.com/products/bbedit)

Most of these text editors are available on all major operating system platforms, Windows, Mac, and Linux/Ubuntu except for Coda, BBEdit which are only on MAC, and Notepad++ which is only for Windows. Atom, Brackets and Notepad++ are fully free and open source text editors that you can download and use without paying anything. Sublime Text is also free, however, the unregistered version will have a constant pop up that will ask you to purchase a license. The other text editors all have trial periods, which means that you can download them and try out the text editor for free. 

Personally, I use a combination of text editors depending on the project that I am working on. So, go ahead and try out a few text editors and see which one you feel the most comfortable using. 

