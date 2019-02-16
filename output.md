**[HTML & CSS IN A WEEK ...OR LESS]{.smallcaps}**

![](./images/media/image1.png){width="6.773611111111111in"
height="0.8020833333333334in"}

[**www.fullstackstudent.com**](http://www.fullstackstudent.com)

**\
**

IntroductionHow to use this book & exercise filesDay OneHow the web
worksThe World Wide WebThe big pictureURLsIP AddressesThe Domain Name
SystemHTTP and HTTPSWhat is HTML & CSS?HTML Tags, Attributes and
ElementsHTML termsElementsTagsAttributesTools of the tradeHTML
Foundations: your first web pageHTML TagHead TagTitle TagBody TagSave as
a HTML documentComments in HTMLHeadingsParagraphsWhite SpaceLine Breaks
& Horizontal rulesHorizontal linesEmphasis & Strong EmphasisHTML
Parent/Child StructureDay TwoHyperlinksLink to an external web page or
another page within the same siteLinking to another region within the
same pageRelative and absolute pathsOpening links in a new
windowListsOrdered ListsUnordered ListsImagesTypes of
imagesTablesStructuring TablesTable Head and Body ElementsTable Foot
ElementTable Caption ElementFormsForm ElementInput ElementsText Area
ElementButton ElementLabels and FieldsetsFieldset and LegendSelect
MenusRadio ButtonsCheckboxesHTML Special CharactersIDs & ClassesID's are
unique and classes are notSpan & DivHTML5 Web Page
StructureHeaderNavigationSectionArticleWhen to use \<section\> or
\<article\>AsideFooterAbbreviations, Acronyms & QuotesDay ThreeGetting
started with CSSIntroduction to CSSUser agent stylingInline
StylesInternal stylesExternal StylesheetsImporting stylesheet with
\@importCSS resourcesDay FourBasic selectorsIntro to selectorsType
selectorsID selectorsClass selectorsReusing classesDescendant
selectorsPseudo classesHover pseudo classCSS commentsDay
FiveUnderstanding values and unitsCommon data typesPixel
unitsPercentagesEm unitsRem unitsColor valuesText stylesText
alignmentText TransformFont propertiesFont FamilyFont StyleLine
heightDay SixThe box modelPaddingBordersMarginsNegative margin
valuesCenter Body ContentDisplay ValuesDay SevenBasic LayoutWidth and
height propertiesBox-sizing and max-widthBackgrounds: color and
imagesBackgrounds: size and positionFloatsClearing
FloatsListsFundamental ConceptsThe CascadeImportanceSpecificity & Source
OrderConclusion

Introduction 
=============

HTML & CSS are the building blocks of the web and without these two core
technologies, there wouldn't be any websites or web apps. This book,
*HTML & CSS In A Week ...Or Less*, intends to do exactly what the title
implies. You will learn the core web technologies in less than one week,
or less. In our digital age today, it is quickly becoming an important
requirement to be digitally well versed. In fact, many jobs require you
to be "tech savvy" and learning how to code with HTML & CSS can do
wonders for our personal and career development. Even if you don't
intend to become a web designer or web developer, learning how to code
with HTML & CSS will no doubt add a fantastic tool to your skillset.§

My name is Abdi Cagarweyne, and I have been in the field of Software
Development for the best part of my life. Currently, I'm a full-stack
JavaScript developer based in London, UK. I know that there are many
excellent programming books available and all have their place. But, I
wrote this book because it is written in a way that I feel makes
understanding these two core technologies easier from a beginner's
perspective. Essentially, the book is comprised of two parts, the first
part focuses on the HTML only without any CSS. The second part focuses
entirely on how to apply styles to the HTML using CSS.

I enjoyed writing this book very much and I sincerely hope that it
enables you to learn an excellent tool and that you enjoy reading it!

**\
**

How to use this book & exercise files
=====================================

The book is organized into seven days, meaning that we will tackle
different topics on each given day. I would like to emphasize the
importance of practically typing out the HTML and CSS code using a code
editor and following along. I go through the most popular code editors
in use today -- so be sure to download one and use it as the editor to
write your code. Accompanying this book are working exercise files, one
for the HTML section and the other CSS. I would highly encourage you to
download the files, as I will be referring to them extensively
throughout the book. You can download the files from here:

[fullstackstudent.com/html-css-in-a-week-exercise-files/](http://fullstackstudent.com/html-css-in-a-week-exercise-files/)

When you download the exercises files, you will see two folders. One
titled *css-section* and the second *html-section*. The CSS folder
contains all of the sections for each topic that is covered, and the
names of the folders correspond with each heading in the book in the CSS
section. It is important that you download these files, as you will get
the starter code for the landing page that we will build in the CSS
section. All of the exercises files in the *css-section* are organised
into 'start' and 'final' code. The code in the *start* folder contains
all of the HTML & CSS code that we will start with in that section. The
*final* folder contains all of the code that is written for that section
once we have covered all of the tasks for the topic in question.

Day One
=======

How the web works 
------------------

In order to surf the World Wide Web, you need an application called a
web browser. You\'re probably familiar with this, as you might already
be using one already such as Google\'s Chrome, Microsoft\'s Internet
Explorer, Mozilla\'s Firefox, or Apple\'s Safari. To fully appreciate
how the web works, we\'ll briefly talk about URLs, domain names, IP
addresses, the domain name system, and the HTTP protocol to be fully
prepared for web development.

### The World Wide Web

A domain name is part of a URL, which is just a human-friendly IP
address. Domain name servers connect domain names with IP addresses so
you don\'t have to. Clients and servers communicate using the HTTP
protocol over an application called a web browser.

### The big picture

What actually happens in between typing in google.com and seeing
Google\'s website? In short, there are a lot of complex things happening
and I\'ll describe this process briefly. In between each browser request
and server response are one or multiple pieces of software, most of them
speaking to each other using a common protocol called HTTP, or the
Hypertext Transfer Protocol. Let\'s start with an overview of how the
Web works, and then explore each step individually. Every website
you\'ve visited started with a client sending a request to a server. A
client is anything that can request a resource on the web and these
include desktop computers, laptops, phones, and tablets. But even
software programs themselves can be clients.

Be it a human user or a software program, the entity making the request
is called a client. When you type a URL into the address bar, you are
sending a request to a computer server, in particular, a web server. The
Internet is a network of computers all connected together by various
cables. It\'s made up of wires, routers, switches and satellites that
connect the network of servers together. These servers can perform a lot
of tasks. Web servers host web sites, domain name servers connect domain
names with IP addresses, and mail servers send and accept email
messages.

All of these things are considered part of the Internet. The files,
folders and media that make up webpages are housed on the servers. These
files, folders and media are all software and are what we\'re talking
about when we say the web. The web is the software that makes up
websites, applications, games, wikis and videos that you can access on a
web browser. As I\'ve already mentioned, there are a lot of different
web browsers out there. There are also many types of clients, mobile
phones, apps, and games. In order for everyone to play nicely together,
they have to speak the same language, and that language is called HTTP,
or Hypertext Transfer Protocol.

Nearly all HTTP requests start with you typing in a domain name like
google.com. Servers however, use numbers to locate each other, not
words. These numbers are called IP addresses and work similarly to how
phone numbers work, with each IP address pointing to a particular server
on the Web. The service in the middle, between the domain name you type
in and the IP address used by the server, is called a Domain Name
Server, or DNS. Once the DNS finds the IP address you asked for with the
domain name, it rushes your request along to the server hosting the
website.

For now, we can think of this request as a stamped, self-addressed
envelope sent to the website\'s IP address with a return address of your
computer\'s IP address. When the envelope is delivered to the server
hosting the website, the server sends the envelope back to you with the
website you wanted. When this happens, the HTTP trip is over and you
have the thing you asked for, which is the web page of the website that
you requested. In our example, it is the Google home page but this could
be anything such as an image, text, application or video.

That took a long time to explain! But this happens so quickly that you
don\'t even realize that the website you just visited has its server
located on the other side of the planet! When you request a web page, it
usually takes less than a couple of seconds and it\'s getting faster all
the time. Now that we\'re somewhat familiar with the process of what
happens when we surf the web, let\'s break down each step in more
detail.

### URLs

URL\'s, domain names, IP addresses and DNS are all quite closely tied to
one another. The web consists of so many interconnections and we will
discuss each of the main parts in more detail. The term URL stands for
Uniform Resource Locator. Back in the late 1980s, Sir Tim Berners Lee
invented the concept of the World Wide Web and in doing so, he
standardized many of the processes needed to make computers talk to each
other. A URL is one of those processes and it is the way that the web is
interconnected. Whenever you want to access something on the web, be it
on your mobile device or desktop, you will need to provide a URL for
that resource. This resource could be text, audio, video etc.

For instance, you might want to watch some videos on YouTube and to get
there, you will type http://www.youtube.com in the address bar in your
browser. This is a URL. It shows the method that your browser will use
to retrieve this resource, which is the http protocol. It also shows the
network location, in human friendly form, of the resource that you wish
to access. One of the most wonderful parts of the web is how everything
is connected. Web pages are connected using what\'s called hyperlinks,
and behind every hyperlink is a URL. Hyperlinks often look like the
blue, underlined words on the page, but they can also look like a lot of
things these days, such as images or buttons.

If the URL starts with http, the next bit in the URL, after the colon
and two slashes, is the domain name. Like http://**www.youtube**.com.
Everything after a domain name describes the full path to the resource.
However, more and more URLs are becoming shorter. Nowadays, nearly
everything is omitted in the address bar, including the http://, and you
are left with what is often called the 'naked' URL or clean URLs.
However, just because you can\'t see these details, it doesn\'t mean
that they\'re not there. Modern browsers have built in features that
hide these details from you, but in actuality, they are needed to access
any resource on the web. The one detail that\'s always left is the
domain name, like youtube.com. While this domain name will help users
find resources on the web, computers don\'t use names to find things.
They use numbers, and these numbers are called IP addresses.

### IP Addresses

Since the Internet is comprised of a global network of computers, there
needs to be a way to identify each computer and device connected the
Internet. This is where the Internet Protocol address (or IP) comes into
play. Everything connected to the Internet has an IP address. This
includes computers, servers, cell phones and any other equipment that is
connected to the Internet.

All of these devices have a unique IP address that identifies them and
enables them to connect to the Internet. Think of an IP address like
your home address, so if someone wants to send you a letter, they need
to know your full address to post the letter to you. Likewise, all
devices that communicate with each other on the Internet use an IP
address to send and receive data. An IP address takes the form of four
sets of numbers. Each of these numbers must be between 0 and 255 - for
example, 77.121.147.234.

### The Domain Name System

A domain name system is a special type of server that connects domain
names with IP addresses, in other words it's like a giant telephone book
that connects an IP address with a domain name. This means that you
don\'t have to keep your own address book of IPs to your favorite
websites. Instead, all you have to do is remember the domain name and
you just connect through DNS, which manages a massive database that maps
domain names to IP addresses. As you might be aware, there are millions
and millions of websites and it is impossible for one computer server to
contain the entire list of websites and their respective IP addresses.
The DNS system is a distributed database. This means that portions of
the database are divided and spread to many different servers on the
Internet. So, if a DNS server does not contain the domain requested, it
will redirect the request to another server.

As we've already seen, a web address is referred to as a URL, and this
URL is divided up into various levels. These levels are: the top-level
domain, domain name and host name. So, if you wanted to go to the
Wikipedia website, you would type in www.wikipedia.org -- the .org part
is the top-level domain, the Wikipedia is the domain and the www is the
host name. There are several top-level domain names that you've probably
come across before, these include: .com, .edu, .gov, .me etc. The inner
workings of the DNS system is quite complex, but what is important to
understand is that the DNS is the address book for the Internet, and
it's what connects domain names with IP addresses.

**\
**

### HTTP and HTTPS

Every request that you make on the web is sent using the HyperText
Transfer Protocol or more commonly called HTTP. HTTP is like the
language that clients and servers use to speak to each other. This is a
standard way for all devices to communicate, because there are so many
different types of clients and servers. HTTP defines the rules that
every device, be it a client or server, must conform to in their
communication. In every HTTP communication, there are two pieces of
information that are sent back to the client. The first is the status
code, and then the requested resource such as a web page or a file. The
status code helps identify the cause of the problem when a web page or
other resource doesn't load properly. There are a whole host of status
code numbers, each with a different meaning. When you request a web page
and that page loads into your browser, the server would have a sent a
status code equal to 200. This means that everything is OK and the
resource requested has been sent. You can get a detailed breakdown of
all the different status codes here on the Wikipedia page.

Sometimes, in your travels around the web, you\'ll see a lock icon in
the address bar. The lock will usually be all the way to the left and
the URL will start with https not http. The **s** stands for secure and
it means that communication between the client and the server is private
and encrypted. When surfing the web, don\'t use sites that require
sensitive information, like medical records, banking details or even
just username and passwords if they don\'t have the lock.

**\
**

What is HTML & CSS? 
--------------------

As you have seen from how the web works, whenever you access a website,
the webserver will send you the resource that you requested. This means
that you will receive at a bare minimum two documents, a HTML and CSS
file. The HTML file contains the structure of the website, just like you
would give any document structure such as a title, heading, and
paragraphs, while a HTML document contains the same structure that tells
your browser how to render the web page.

The second file that you will most certainly receive when you make a
request for a website is a CSS file. Whilst the HTML file species the
structure of the document, the CSS file tells the browser how that
documents looks like from colors to layout. Many years ago, it was quite
normal to receive just one file that contained both the HTML and CSS,
but those days are long gone and it is best practice to separate the
structure of a webpage from its styling. This means that whenever you
are looking at a website, your browser has received both HTML and CSS
files from a web server that hosts the site being accessed.

The web browser, this could be any web browser such as Google Chrome,
Internet Explorer, Firefox etc, interprets the HTML and CSS code to
create the page that you see. Small websites are created using just HTML
and CSS, but larger websites make use of other technologies such as
databases and advanced server side programming languages. However, HTML
and CSS are the gateway to any website or app online, as without these
two technologies, no one will be able to use the website.

### HTML Tags, Attributes and Elements

As I've mentioned already, HTML is the structure of a website. Think of
it like a house, the bricks that form the structure and its shape. HTML
describes the structure of web pages and HTML stands for Hyper Text
Mark-up Language. As the name suggests, it's a markup language that
dictates how the information is marked up on a web page. If you have
ever used word processing software such as Microsoft Word, you will be
familiar with headings, subheadings, lists, and paragraphs.

When you want to add any of these features in word processing software,
for example a heading, you can simply highlight the text that you wish
to use as a heading and select the appropriate heading such as heading 1
from the dropdown menu and the text you selected will now be a heading
1. With a word processor, there is an underlying program that interprets
your selections and makes the changes that you can see on the screen.
You can replicate the same structure on a web page, but you don't have
the luxury of drop down menus, instead you have to tell the browser how
to structure the web page using HTML code.

**\
**

### HTML terms

Whilst creating your first web page, you will likely encounter a few
terms being used constantly. Once you understand what they are, you will
become familiar with all of them, but the most common terms that you
will hear about all the time are elements, tags, and attributes.

### Elements

Elements are the backbone of any web page, and you'll see these elements
in the source code for all web pages after the *\<**!DOCTYPE html**\>*
declaration, we'll learn about the *\<**!DOCTYPE html**\>* soon.
Elements define the structure and content of objects within a page. Some
of the more frequently used elements include multiple levels of
headings, identified as *\<**h1**\>* through *\<**h6**\>* elements, and
paragraphs identified as the *\<**p**\>* element. Elements are
identified by the use of less-than and greater-than angle brackets,
*\<\>*, surrounding the element name. Thus, an element will look like:
*\<**body**\>*.

### Tags

When you use the less-than and greater-than angle brackets and surround
them over an element, this creates what is known as a tag. Tags most
commonly occur in pairs of opening and closing tags. Opening tags mark
the beginning of an element, this consists of a less-than sign followed
by an element's name, and then ends with a greater-than sign; for
example, *\<**body**\>*. The content that falls between the opening and
closing tags is the content of that element. For example, a paragraph
will have an opening tag of *\<**p**\>* and a closing tag of
*\<**p**\>*. What falls between these two tags will be the content of
the paragraph.

### Attributes

Elements can have attributes; these are additional values that configure
the elements or adjust their behavior in various ways to meet a certain
criteria. The most common attributes include the *id* attribute, which
identifies an element; the *class* attribute, which is used for styling
a group of elements using CSS; the *src* attribute, which specifies a
source for embeddable content such as the source for an image; and the
*href* attribute, which provides a hyperlink reference to a linked
resource. Attributes are defined within the opening tag, after an
element's name, and include a name and a value. The format for these
attributes consists of the attribute name followed by an equals sign and
then the attribute value surrounded by quotes.

For example, an *\<**a**\>* element including an *href* attribute would
look like: *\<**a**
href=\"http://fullstackstudent\"\>Fullstackstudent\</**a**\>*. This
piece of HTML code will display the text "link" on the web page and will
take users to http://fullstackstudent.com/ upon clicking the "link"
text. The anchor element is declared with the opening *\<**a\>*** and
closing *\</**a\>*** tags encompassing the text, along with the
hyperlink reference attribute and value that are declared with
*href=\"http://fullstackstudent\"* in the opening tag. The following
figure puts all of the different parts that we have just looked at into
perspective:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image2.png){width="5.339511154855643in"
height="1.1814512248468942in"}

Tools of the trade 
-------------------

HTML documents are plain text documents saved with an ***.html*** file
extension rather than a ***.txt*** file extension.  So, really, almost
any text editing tool will suffice. However, authoring websites is an
iterative process, and you will be running multiple languages like HTML,
CSS, and later on, JavaScript. Therefore, writing everything by hand
will be very time consuming. A good text editor will help you speed up
the development process and catch any syntax errors, (these are typos
and characters or strings incorrectly placed) that you might miss.

Text or code editors, as they are sometimes called, come in all shapes
and sizes and you have many different options both paid and free.
However, at minimum, you will need a text editor that has:

-   Line Numbers

-   Formatting options

-   Syntax highlighting

-   Code support for other languages -- HTML, CSS, and JavaScript

If you're new to web development, and you don't have experience with
text editors, I highly recommend that you try out several different
types of text editors before settling on a favorite. This is because
choosing a text editor is an important decision that will impact your
workflow and productivity when it comes to building websites. It's worth
mentioning that a text editor that works for one developer might not be
the best solution for another, so it really comes down to personal,
workflow, and productivity factors in choosing a text editor.

When you're starting out in web development, it is highly recommended to
start with a code editor that is easy to set up and use. Not only will
this allow you to be productive from the very start, but it also means
that you don't have to spend a tremendous amount of time learning the
specifics of the text editor. With text editors, nothing is set in stone
and as you gain more experience, you can always move to a more complex
text editor if you find that your current one is limited in features
that you need.

In web development, speed is an integral part of the creation process,
and this is something that you will need to consider when choosing a
text editor. Text editors should be lightweight and fast. This is an
important feature that you should carefully look for. So, in your quest
to find your ideal text editor, if you find that the text editor feels
sluggish and unresponsive at times, then this is a sign that it might
not be a suitable text editor for you. Slow and sluggish text editors
can add hours or even days to your development time.

Now we've talked a lot about the different features that a text/code
editor should have and you're probably wondering what are some of the
popular text editors that are in use in the industry since there are so
many to choose from. The most popular text editors, not in any order,
are:

-   [Sublime Text](http://www.sublimetext.com/) - sublimetext.com

-   [Brackets](http://brackets.io/) - brackets.io

-   [Atom](https://atom.io/) - atom.io

-   [Coda](https://panic.com/coda/) - panic.com/coda

-   [Notepad++](https://notepad-plus-plus.org/) - notepad-plus-plus.org

-   [BBEdit](http://www.barebones.com/products/bbedit/) -
    barebones.com/products/bbedit

Most of these text editors are available on all major operating system
platforms, Windows, Mac, and Linux/Ubuntu except for Coda, BBEdit which
are only on MAC, and Notepad++ which is only for Windows. Atom, Brackets
and Notepad++ are fully free and open source text editors that you can
download and use without paying anything. Sublime Text is also free,
however, the unregistered version will have a constant pop up that will
ask you to purchase a license. The other text editors all have trial
periods, which means that you can download them and try out the text
editor for free.

Personally, I use a combination of text editors depending on the project
that I am working on. So, go ahead and try out a few text editors and
see which one you feel the most comfortable using.

HTML Foundations: your first web page
-------------------------------------

Coding up your first web page is a straightforward process, and we can
get this done in less than 15 lines of HTML code. The following is all
you need to construct your first web page using HTML. This might look a
little different to anything you've seen before, but we'll go through
each line in detail.

   

*\<**!DOCTYPE html**\> *

*\<**html** lang=\"en\"\> \
\<**head**\> *

*\<**meta** charset=\"utf-8\" /\> *

*\<**title**\>My First Web Page\</**title**\> *

*\</**head**\> \
\<**body**\> *

*\<**h1**\>Hello World\</**h1**\> *

*\<**p**\>My first web page.\</**p**\> *

*\</**body**\> \
\</**html**\>*

The first line *\<**!DOCTYPE html**\>* informs the browser
about the type of HTML version that is being used and is called the
document type declaration. This simple statement means that HTML5 is the
version of the markup that will be used for the rest of this
document. The document declaration is always placed at the beginning of
the file before writing any HTML markup. 

HTML Tag
--------

The next piece of HTML code is the *\<**html** lang=\"en\"\> *and
this signifies the beginning of the document. As you will soon see, most
elements come in pairs.

The *\<**html**\>* element comes in a pair and encapsulates all the
other elements. The pairs of elements have an opening, and this element
is closed right at the end of the document with *\</**html**\>*.  The
opening *\<**html**\>* element has an attribute that specifies the
language of the document; in our case we are setting the language as
English with *en*.

This is not something that you have to do to every single HTML document,
but it is one of those things that strictly specify which language will
be used. It's also useful for screen readers in terms of how they
enunciate the text, and is also very helpful for online translators,
so that they know which language they\'re dealing with.  You can find
all the ISO language codes here:
<http://www.html.am/reference/iso-language-codes.cfm>. 

Head Tag
--------

The next element is the *\<**head**\>,* which is inside *\<**html**\>*.
This is a required tag that should only be used once on the web page.
The elements that reside inside the head tag aren't displayed on the web
pages and are hidden from visitors. 

Inside this element, you can place metadata -- this is accompanying
information about the page. In our web page, the *\<**meta**\>* element
has an attribute called charset that is set to utf-8. 

This simply specifies the character encoding for the HTML document. This
is something you should do for each of your HTML documents. You always
want to set the character encoding, and unless you\'re going to be using
Russian, Japanese, and the Persian alphabet, or other types of
characters, you\'re probably going to use utf-8. What this does is
inform the browser which encoding to use - that way, it\'s going to use
the proper characters when rendering content to the page. You also want
to set this encoding as the very first thing after the head tag,
so it\'s immediately set.

Meta tags don't actually do anything to the content that is presented in
the browser window, but they are used by the likes of search engines to
catalogue information about the web page. You will notice that the
*\<**meta**\>* tag doesn't have a corresponding closing tag. In HTML
there are some tags that are self-closing, and the *\<**meta**\>* tag is
one of them.

  

Title Tag
---------

The next element that sits inside *\<**head**\>* is
the *\<**title**\>.* This element sets the title of the document. The
text inside the pair of opening and closing tags of
the *\<**title**\>* element doesn't actually appear in the main body of
the document, instead the title appears in the tab or window of the
browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image3.jpg){width="4.336872265966754in"
height="1.7457075678040246in"}

The closing tag for the *\</**head**\>* element comes after closing the
title tag, and this just closes the corresponding tag that was opened. 

Body Tag 
---------

The next element in the document is the *\<**body**\>* element, and
inside this tag is where the main content of the document will actually
be viewable to the user when the file is opened in a browser. Most of
the markup tags will actually go inside the ***body*** element. There
are two elements inside the main ***body*** element, ***h1,*** which
specifies the type of heading -- much like the heading 1 selection from
a Word document, and the ***p*** element that signifies the beginning of
a paragraph.

You could simply just write your text out inside the ***body*** element,
but to follow good semantics and to make it easier to style different
elements, it is best practice to wrap all paragraph text inside
a ***p*** element. Finally, the ***body*** and ***html*** elements are
closed off with closing tags.  

           

Save as a HTML document
-----------------------

Now that we have coded our first web page, we can save this as an HTML
file. First, make sure that you save the file with an appropriate name.
I'm saving mine as *first-web-page.html*. Please note it is important to
save your file with an **.***html* file extension, otherwise you won't
be able to open the file as a web page in your browser. Once you have
saved the file, just navigate to its location in your computer and
double click it to open -- it should open in your default browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image4.jpg){width="4.5in"
height="2.3215660542432195in"}

While it may not look exciting, you have just created your first web
page! HTML is the building blocks of all websites on the web, and
without HTML, there wouldn't be any websites.

**\
**

Comments in HTML
----------------

In HTML, and generally in software development, we have the ability to
leave comments within our code, and any content wrapped within a comment
will not be displayed on the web page. Comments play an important role
in helping us organize our code, allow us to convey our thinking and
reasoning behind what we have written to others, and provide a way for
us to more effectively manage our code. Comments become especially
useful when there are multiple people working on the same files. In
HTML, comments start with ***\<!\--*** and end with ***\--\>***. If you
create a new file in your chosen text editor and enter the following
markup:

*\<**!DOCTYPE html**\>*

*\<**html** lang=\"en\"\>*

*\<**head**\>*

*\<**meta** charset=\"utf-8\" /\>*

*\<**title**\>Comments in HTML\</**title**\>*

*\</**head**\>*

*\<**body**\>*

*\<!\-- this is a paragraph tag\--\>*

*\<**h1**\>Comments in HTML\</**h1**\>*

*\<**p**\>Comments are really useful in HTML web pages and also in
Software Development in general\</**p**\>*

*\</**body**\>*

*\</**html**\>*

Then save the file as *comments.html*. When you open the file in the
browser, you will see that we have a simple web page along with some
comments:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image5.jpg){width="4.5in"
height="1.814096675415573in"}

As you can see, comments are ignored by the browser and not displayed to
the users. In most code editors, you can use a keyboard shortcut to add
comments into your code, simply highlight the text that you wish to turn
into a comment, on a Mac, simply hold down the command button and press
the forward slash key on your keyboard. For Windows, or Linux users,
hold down the Ctrl key and then press the forward slash key, and the
editor will automatically make the highlighted text a comment for you.
This works in Atom, Sublime, and pretty much most code editors.

**\
**

Headings 
---------

Just like in Word processed documents, headings play an important role
in the structure of your web page. Users can see what the headings are
for your document and can skim your pages according to its headings.
Search engines use the headings to index the structure of the web page.
In HTML, there are six levels of headings. The h1 heading should be used
for main headings, h2 is used for subheadings, and if there are further
sections under the subheadings, then you can use h3 up to h6. In your
code editor, type up the following and save as *headings.html*:

*\<**!DOCTYPE html**\> *

*\<**html** lang=\"en\"\> \
\<**head**\> *

*\<**meta** charset=\"utf-8\" /\>*

*\<**title**\>HTML Headings\</**title**\> *

*\</**head**\> \
\<**body**\> *

*\<**h1**\>Main Heading -- level 1\</**h1**\>*

*\<**h2**\>Subheading -- level 2\</**h2**\>*

*\<**h3**\>level 3 Heading\</**h3**\>*

*\<**h4**\>level 4 Heading\</**h4**\>*

*\<**h5**\>level 5 Heading\</**h5**\>*

*\<**h6**\>level 6 Heading\</**h6**\>   *

*\</**body**\> \
\</**html**\>*

Browsers will display the sizes of the headings slightly differently
from others. However, what you should see is that content of the h1
should be the largest of the six and as the level goes up, the size of
the contents should decrease in size:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image6.jpg){width="4.171692913385827in"
height="2.5in"}

 Paragraphs
----------

Paragraphs are one of the most basic tags that you will use in HTML. The
following is a simple HTML document that I've created with two
paragraphs. You can type up the following markup to get the same file,
and then save as *paragraphs.html*:

*\<**!DOCTYPE html**\> *

*\<**html** lang=\"en\"\> \
\<**head**\> *

*\<**meta** charset=\"utf-8\" /\>   *

*\<**title**\>Hello World\</**title**\> *

*\</**head**\> \
\<**body**\> *

*\<**h1**\>Understanding HTML\</**h1**\>*

*HTML is the building blocks of web pages*

*It specifies the structure of documents. *

> *HTML plays an important part in web documents along with Cascading
> Style Sheets. *

\*  *

*\</**body**\> \
\</**html**\>*

However, when you view this in the browser, it is formatted differently:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image7.jpg){width="5.763888888888889in"
height="1.2944444444444445in"}

The browser has clumped together the two paragraphs into one, so the
visual structure that we see in the code is not what is reflected in the
output from the browser. For us to get the desired effect, we have to
tell the browser that each sentence is a single paragraph. We can do
that by wrapping each sentence with an opening and closing *\</**p**\>*
tag:

*\<**!DOCTYPE html**\> *

*\<**html** lang=\"en\"\> \
\<**head**\> *

*\<**meta** charset=\"utf-8\" /\> *

*\<**title**\>Hello World\</**title**\> *

*\</**head**\> \
\<**body**\> *

*\<**h1**\>Understanding HTML\</**h1**\>*

*\<**p**\>HTML is the building blocks of web pages*

*It specifies the structure of documents.\</**p**\> *

> *\<**p**\>HTML plays an important part in web documents along with
> Cascading Style Sheets.\</**p**\> *

\*  *

*\</**body**\> \
\</**html**\>*

Now when we save the document and reload the web page in the browser, we
get our desired effect:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image8.jpg){width="4.75in"
height="1.912590769903762in"}

We have the same code as before, but only this time we have wrapped our
sentences with the ***p*** tag. Pretty much all browsers will display
each paragraph on a new line with some space between it and any other
paragraphs that are on the page.

White Space 
------------

Web developers use white space liberally to help make the code easier to
read and understand. White space does not affect the rendering of web
pages in the browser. In fact, you can have as much space between
elements and content and the browser will ignore the extra spaces. Using
our paragraphs from the last example, we can add white space:

*\<**p**\>HTML is the building blocks of web pages*

*It specifies the structure of documents.\</**p**\> *

*\<p\>HTML plays an important part in web documents along with Cascading
Style Sheets .\</**p**\>*

Let's save this and refresh the browser to see if anything changed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image8.jpg){width="4.656641513560805in"
height="1.875in"}

As you can see, this has no effect on the output. The browser has
collapsed all extra white space in the output. When the browser sees two
or more spaces next to each other, it will simply collapse the space
into just one space. You can also have a line break and the browser will
also treat that as a single space on output. This means that web
developers can make use of this to add indentations and extra white
space where necessary to make the code tidier and easier to comprehend.

Line Breaks & Horizontal rules 
-------------------------------

As we just saw, the browser will ignore any line breaks and collapse the
extra white space into a single one. However, what if you wanted a line
break within your paragraph? You can use the *\<**br**/\>* tag to
achieve this. Notice that the *\<**br**/\>* tag is self-closing just
like the meta tag we saw previously. Let's place a line break after the
first word in our first paragraph:

*\<**p**\>HTML \<**br** /\> is the building blocks of web pages*

*It specifies the structure of documents.\</**p**\>*

Save your changes and then refresh the browser to see the changes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image9.jpg){width="5.061264216972878in"
height="2.0604833770778654in"}

As you can see, the line break has been inserted exactly where we
specified in the HTML. The line break tag is useful when you want to add
a line break inside a paragraph.

Horizontal lines
----------------

Horizontal lines have been used as separation between items both in
print and on web documents. In HTML, you can use the *\<**hr /**\>* tag
to add a simple horizontal line in your web page. Let's add a line
between the two paragraphs that we currently have:

*\<**p**\>HTML is the building blocks of web pages*

*It specifies the structure of documents.\</**p**\> *

*\<**hr /**\>*

*\<**p**\>HTML plays an important part in web documents along with
Cascading Style Sheets.\</**p**\>*

Now, let's save this change in our text editor then switch over to the
browser and see the result:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image10.jpg){width="5.210725065616798in"
height="2.1169356955380576in"}

A solid horizontal line has now been added to the web page between the
two paragraphs. You can use this tag to separate different areas of the
page which can be useful in structuring your documents.

Emphasis & Strong Emphasis 
---------------------------

In writing, we generally emphasize certain words, sentence and headings
to make them stand out, or to help the reader to understand a point of
emphasis. You can do the same with web pages using four different tags:
bold, strong, italic and the emphasis tag.

I have created a page with four short paragraphs about the HTML tags
that are used to format text. Let's say that we want to make the words
*represents* and *emphasis* bold. We can achieve this using either bold
or strong, we will discuss the difference soon -- let's first make the
words bold using the *\<**b**\>* tag:

*\<**p**\>HTML is the building blocks of web pages*

*It specifies the structure of documents.\</**p**\> *

*\<**hr /**\>*

*\<**p**\>HTML plays an important part in web documents along with
Cascading Style Sheets.\</**p**\>*

*\<**h2**\>The Bold Tag\</**h2**\>*

> *\<**p**\>The bold tag (⟨b⟩) \<**b**\>represents\</**b**\> a span of
> text that you wish to highlight from the rest of the text without
> inferring any type of special relevance or meaning. As you would
> expect, browsers typically bold this text.\</**p**\>*

*\<**h2**\>The Strong Tag\</**h2**\>*

> *\<**p**\>By using the strong tag (⟨strong⟩)
> \<**b**\>represents\</**b**\> a string of text as having strong
> importance. The text should be considered to be more important than
> the text surrounding it. This is displayed as bold, just like the
> using the bold tag.\</**p**\>*

*\<**h2**\>The Italic Tag\</**h2**\>*

> *\<**p**\>Like the bold tag, the italic tag (⟨i⟩)
> \<**b**\>represents\</**b**\> a string of text that is highlighted
> from the text around it. No particular meaning is attached to the text
> when you use the (⟨i⟩) tag, it is just rendered in italics. Helpful
> for phrases, terms, or any text that is normally displayed in
> italics.\</**p**\>*

*\<**h2**\>The Emphasis Tag\</**h2**\>*

> *\<**p**\>The \<**b**\>emphasis\</**b**\> tag (⟨em⟩), or \"em\" tag,
> denotes text that is emphasized more than the text around it. Although
> this tag is usually rendered in italics, it shouldn\'t be used in
> place of the italics tag, rather it should be used for text that needs
> to be emphasized for some reason.\</**p**\>*

Save the changes and switch to your browser then refresh to see the
results:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image11.jpg){width="4.657688101487314in"
height="2.5in"}

The words *represent* and *emphasis* now stand out as bold. Adding the
bold tag has not added anything except the visual representation of the
bold text on the web page. We can achieve the same effect with the
strong tag by merely replacing it with the bold tag for each word
*\<**strong**\>represents\</**strong**\>* and
*\<**strong**\>emphasis\</**strong**\>.* We get exactly the same result
as before.

Try this out. You may be wondering: what is the difference between the
two tags? In terms of visual representation, there is no difference
whatsoever, they both highlight the text in question by making it bold.

However, there is a difference when it comes to semantic meaning. When
you use the bold tag, you are merely adding a visual stylistic element
to a piece of text and you are not inferring any type of special
relevance or meaning. You just want to make a piece of text bold.

However, when you use the strong tag, you are giving that piece of text
a semantic meaning, in other words these words in between the strong tag
have a strong importance. So, when a screen reader reads the text that
is in between a strong tag, if it is capable of doing a different vocal
inflection, it will know to emphasize that piece of text to get that
importance across to the listener.

The italic and emphasis tags both do the same thing. Let's italicize the
headings for each heading that describes the two tags using the
\<**i**\> and \<**em**\> tags respectively:

*\<**h2**\>\<**i**\>The Italic Tag\</**i**\>\</**h2**\>*

*\<**h2**\>\<**em**\>The Emphasis Tag\</**em**\>\</**h2**\>*

We need both an opening and closing tag for each of the tags to
italicize the words, so make sure to nest them inside the opening and
closing *\<**h2**\>* tags. Save and switch over to your browser, and you
will notice that both the headings are now italicized:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image12.jpg){width="4.130648512685914in"
height="1.9314512248468942in"}

In the same way that adding a bold tag visually highlights a word,
adding an *\<**i**\>* just italicizes the word without adding any
semantic meaning. Using *\<**em**\>* on the other hand, adds semantic
meaning to your markup. It's telling screen readers, for example, that
this piece of text needs to be emphasized.

HTML Parent/Child Structure 
----------------------------

All HTML documents follow a structured parent child relationship. As
we've already created a web page, we did so by making sure the first
line in the document was the *\<**!DOCTYPE html**\>*, then the html
element then the head and so on. The following is a diagram of the
parent and child relationship of a simple web page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image13.jpg){width="5.285592738407699in"
height="2.4148151793525807in"}

The very first element is the *\<**!DOCTYPE html**\>*, which specifies
the version of HTML that the document will be using. The root element is
the html tag and everything in the document from there onward is nested
inside this element. The elements are also called nodes and all the
nodes together are called a node tree -- as the structure looks like an
inverted tree with the root at the top.

So, the head and body nodes are siblings since they both share one
parent, which is the html node. The head node has two children inside
it, the meta and the title tags. So, the term parent/child relationship
comes from the fact that the containing element is referred to as the
parent of the element that is contained within it. In this structure,
the meta and the title tags are the children of the head tag and both
are descendants of the html tag.

In the example webpage shown in the diagram, the body node has several
*\<**p**\>* elements as children. Similar to the meta and the title
tags, all of these *\<**p**\>* tags are siblings. If the *\<**p**\>*
tags had any nested elements inside them, like an em or strong tag, then
they would become parents to these nested elements.

To show the parent-child relationships of nodes in the code, web
developers make use of the white space by indenting the children inside
their parent containers. We have been doing this already with our code:

*\<**!DOCTYPE html**\> *

*\<**html** lang=\"en\"\> \
\<**head**\> *

*\<**meta** charset=\"utf-8\" /\> *

*\<**title**\>Hello World\</**title**\> *

*\</**head**\> \
\<**body**\> *

*\<**h1**\>Understanding HTML\</**h1**\>*

*\<**p**\>HTML is the building blocks of web pages*

*It specifies the structure of documents.\</**p**\> *

> *\<**p**\>HTML plays an important part in web documents along with
> Cascading Style Sheets.\</**p**\> *

\*  *

*\</**body**\> \
\</**html**\>*

**\
**

Day Two
=======

Hyperlinks
----------

One of the core components of web pages is the hyperlink. The World Wide
Web as we know it today is built on hyperlinks with millions of pages
interlinked on the Internet. The hyperlink provides the ability to link
from one web page or resource to another. Linking your web page to
another external page is just one part of the linking system in HTML.
There are several types of links. These include:

-   Links from one website to an external one

-   Link to another page within the same site

-   Link to another region on the same web page

The first time that you encounter the anchor element, it might be a bit
confusing because when you think of the logical naming for linking web
pages, it would be the link element. Well, that would seem to make
sense, but it\'s not what the link element is used for. Instead, the
link element is used to request external resources for the page such as
a CSS or JavaScript file. To create a link on the page, we use the
anchor element or *\</**a**\>* tag. This tag is at the center of all
linking on the World Wide Web. The anchor tag element takes both an
opening and closing tag. Let's explore the way you would create a link
using an anchor tag:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image14.jpg){width="4.870653980752406in"
height="1.1745374015748031in"}

The above shows how you would create a link using the anchor
*\</**a**\>* element. You would write the opening a tag and the word
*href* as an attribute, and this is the hyper link reference. Then, you
would write the equals symbol followed by the URL, the location of the
page that you are linking to.

In this case, it's Google's home page. It's important to wrap the URL
inside the quotes otherwise the link will not work. Next you have the
text that will actually be the link which is clicked, in this example it
is *Google* -- however this can be whatever you like, usually it's a
reference to the name of the web page or resource that you are linking
to. Creating links will always follow this pattern.

Link to an external web page or another page within the same site
-----------------------------------------------------------------

Let's now create a link to one of the most visited pages on the web,
Wikipedia. In particular, we will link to the Wikipedia page for the
anchor tag element. I have added a short description of what the anchor
tag does as a paragraph and then we will add a link using the word
anchor tag:

*\<**h2**\>Anchor tag\</**h2**\>*

*\<**p**\>In computing, a hyperlink is a reference to data that the
reader can directly follow either by clicking. A hyperlink points to a
whole document or to a specific element within a document. Hypertext is
text with hyperlinks. \<**a**
href=\"https://en.wikipedia.org/wiki/Hyperlink\"\>An anchor
tag\</**a**\> is used to link web pages\</**p**\>*

Make sure to add the above HTML content in your HTML file or open the
*9\_hyperlinks.html* file from the exercise files:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image15.jpg){width="3.6123239282589674in"
height="2.1008059930008747in"}

Linking to another region within the same page 
-----------------------------------------------

In addition to linking to external pages on the web, anchor tags allow
you to jump to a specific section within a document. This type of
linking within a single page can be extremely helpful in enhancing your
site's navigation, especially when you have a page with lots of content
that needs scrolling. Linking to sections on your site follows the same
process for linking to external pages. I have a page with some dummy
text separated into three sections. If you open the file
*9a\_hyperlinks.html*:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image16.jpg){width="3.875in"
height="3.3595778652668415in"}

I have created three paragraphs that will act as the link for each
section, so next we will create a link to section 1, 2 and 3. In order
make these three paragraphs links, we need to follow a two-step process.
The first step is to create an ID for each section that we want to
create a link for. So, in the HTML for the web page, scroll to the first
*\<**h2**\>* tag heading that says *Section 1* that will act as the
anchor text for the first section and add an *id* attribute with the
value one:

*\<**h2** id=\"one\"\>Section 1\</**h2**\>*

We have added an *id* attribute with a value of *one*. We will look at
IDs in more detail later on, but essentially, ID's are unique attributes
that you can assign to elements. This means that if you give an element
an ID, that will be unique to that element only. In this case, we have
given the ID of 'one' to the first h2 heading title of the sections.

The second step is to now use this unique ID to create a link using the
a tag on the text that we have already created to act as the link for
each section. To do that, just scroll to where it says *Link to section
1* and then we're going to add a link using the a tag as before, but
only this time we will precede the link with a pound or hash symbol as
follows:

*\<**p**\>\<**a** href=\"\#one\"\>Link to section 1\</**a**\>\</**p**\>*

We can repeat this two-step process to create links for the two other
sections on the page. Create an ID attribute for each h2 title heading
with values of two and three respectively:

*\<**h2** id=\"two\"\>Section 2\</**h2**\>*

*\<**h2** id=\"three\"\>Section 3\</**h2**\>*

Then use the unique IDs to create links on the two remaining paragraphs
that act as the text, which will become links:

*\<**p**\>\<**a** href=\"\#one\"\>Link to Section 1\</**a**\>\</**p**\>*

*\<**p**\>\<**a** href=\"\#two\"\>Link to Section 2\</**a**\>\</**p**\>*

*\<**p**\>\<**a** href=\"\#three\"\>Link to Section
3\</**a**\>\</**p**\>*

Let's save the changes and switch to the browser to see the results:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image17.jpg){width="4.35378280839895in"
height="2.2419356955380576in"}

As you can see from the screenshot above, all the paragraph texts have
now become links to each respective section. Clicking on each link will
take you to that section further down the page.

### Relative and absolute paths

The two most common types of links are links to other pages on the same
website, and links to external resources on other websites on the web.
Both of these types of links use the ***a*** tag to create the link
between the web pages, and the only difference is how you link to them
using the *href* attribute values, which are also known as paths.

When linking to another page on the same website, you will use a
relative path. This means that the URL or path does not include the
domain. For example, if you want to link to the about page on your site
and it happens to be called [www.mysite.com](http://www.mysite.com),
then you wouldn't include the domain name as in:
[www.mysite.com/about](http://www.mysite.com/about). Instead, your
*href* attribute would have a value of just the name of the page so it
would be: *\<**a*** *href* =''*about.html"\>About Us\</**a**\>*, because
the link is pointing to another page on the same website which you are
already on. So, there is no need to give the full *URL* address to get
to the page you are just accessing another page on the same website.

Also, the about page could be inside another directory called pages, for
example. This will also be reflected in the href value: *\<**a** href*
*="pages/about.html"\>About Us\</**a**\>*.

If the page you are linking to is on an external location, then you will
need to use an absolute path. In this instance, the *href* attribute
value must include the full domain. For example, if I want to link to
the about page of Facebook, the path would include the full domain plus
the name of the about page, which they have just called facebook:
*<http://www.facebook.com/facebook>. *

### Opening links in a new window

So far, all of the links that we have created open on the same window or
tab in the browser. But sometimes the user wants to open the link on a
new window or tab, so that they can come back to it after going to the
link. This is a feature that is available in hyperlinks that can be done
easily by adding another attribute after the *href* called *target*. To
open the links in a new window or tab, just use this attribute along
with the value of blank. So, if we wanted to open the about page of
Facebook in a new window or tab, we would just add the target attribute
with a value of underscore followed by the word blank:

*\<**a** href* *="http://www.facebook.com/facebook"
target="\_blank\>About Us\</**a**\>*

The *target* attribute determines exactly where the link will be
displayed, and the *\_blank* value specifies a new window.

**\
**

Lists 
------

There will be many different situations where you will need to use
lists. In HTML, there are three types of lists: ordered, unordered,
definition. We will explore the most common used lists, which are
ordered and unordered lists.

### Ordered Lists 

As the name suggests, these are lists where each item in the list is
ordered with a number. For example, if you had a set of instructions
that need to follow a particular order, you would use an ordered list.
You can create an ordered list using the *\<**ol**\>* tag element, which
acts as a container for all the items in the list. The individual list
items that live inside the *\<**ol**\>* tag will be placed between an
opening *\<**li**\>* and closing *\<**li**\>* list element. Note that li
has been shortened from list. Let's create an ordered list of
directions:

*\<**ol**\>*

*\<**li**\>Go straight on main road\</**li**\>*

*\<**li**\>At the first traffic light turn right\</**li**\>*

*\<**li**\>Keep going straight until you see a large building on the
left\</**li**\>*

*\</**ol**\>*

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image18.jpg){width="4.370049212598425in"
height="1.9596773840769903in"}

With ordered lists, you can create a list that is numbered, this means
that you don't have to explicitly specify each number on the list item.
Each ordered list will start from one and count upwards up to the number
of *\<**li**\>*elements that you add in between the *\<**ol**\>* tag. In
our example, we only have three list elements, which means that the
numbering will start from one and end at three.

### Unordered Lists 

These are lists that begin with a bullet point instead of number like
its ordered list counterpart. Creating an unordered list is almost
identical to ordered lists, the main difference is that instead of using
the *\<**ol**\>* ordered list tag element, you use the *\<**ul**\>*
unordered list tag. In the same way that the *\<**ol**\>* tag was used
as the container for the list elements, the *\<**ul**\>* acts as the
container for each of the unordered list items that reside in between
the opening and closing tags. We will use an unordered list to list the
different technologies used to create websites on the web:

*\<**ul**\>*

*\<**li**\>HTML\</**li**\>*

*\<**li**\>CSS\</**li**\>*

*\<**li**\>JavaScript\</**li**\>*

*\</**ul**\>*

Add this to the *10\_lists.html* file after the ordered lists and see
the result in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image19.jpg){width="3.875in"
height="2.679352580927384in"}

Lists are primarily a way of grouping things together, and lists are not
just to display a series of items. You can use lists to group similar
items together. The navigation links that you see on websites is an
unordered list that has been set to display as inline using CSS. We will
explore how we can style lists in the CSS section.

Images 
-------

Media files play an integral part in making the web interesting and
engaging for users. Rich media complements plain text in many ways and
images are at the heart of making the web what it is today. Images have
been included on websites for a long time, but support for different
types of images has improved over the years.

As you would expect, HTML lets you add images to your web pages using
the *\<**img\>*** element. The *\<**img\>*** tag is one of the few
self-closing tags in HTML and this also means that it doesn't wrap any
other content besides an image.

I have created a new file called *11\_images.html* and this is a
standard web page like the ones that we have been using with the
previous examples. Now in order for the image to display using the
*\<**img\>*** tag, we need to use an attribute *src* whose value is a
URL, and this URL is usually relative to the server where a website is
hosted.

To add an image to the web page, we will use the *\<**img\>*** and give
it a *src* attribute which stands for source, i.e. the location of the
image resource. We will also add another attribute, which will specify
the width of the image in pixels. Although you can control this with
CSS, you can also control the height and width using this inline-style
format, as our image is very big:

*\<**img** src =\"images/beach.jpg\" width=\"600px\" /\> *

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image20.jpg){width="4.28546697287839in"
height="2.8588713910761157in"}

Along with the *src* and *width* attributes, we can add an *alt*
attribute, which stands for *alternative text* and this describes the
content of an image. This alt attribute is picked up by search engines
like Google, and also screen readers to help convey the purpose of the
image. Simply add this after the width attribute in your code:

*\<**img** src=\"images/beach.jpg\" width=\"600px\" alt=\"relaxing on
the beach\" /\> *

Note that this attribute does not add anything to the visual image, it
is only used by search engines and screen readers.

### Types of images 

Images come in a variety of different formats, and the most common
formats are *gif*, *jpg* and *png* images. All major browsers, Chrome,
Firefox, Internet Explorer and Safari, support these file formats. The
jpg format provides the most quality with high color counts while
maintaining an appropriate file size. The gif and the *png* format are
used for images with low color counts or large areas with the same
color.

Tables 
-------

The web is made of rich media including text and images, but another
important element that is used to present information is a table. Tables
are used to present information in a structured and visually appealing
way. Things like sports scores, list of employee names, email addresses,
and recipes can be presented with tables. HTML gives you the option to
display information in a tabular format, using columns and rows. So, if
you want to represent data from a spreadsheet on a web page, you can
easily display this using HTML tables. There are many uses for using
tables to present data, so we'll explore how to display information
using tables.

It's worth mentioning that tables are little bit more involved than
other HTML elements like paragraphs and images, because in order to
construct a table, we need to use elements to represent the individual
table, the rows that contain those cells, as well as the table itself.

You start out creating an HTML table by using the *\<**table**\>*
element. This element has an opening *\<**table**\>* and closing tag
*\</**table**\>*, and it wraps all the table rows and table cells,
inside of it much like a container. I have the file *12\_tables.html,*
and inside this file we will create our table element, which acts as a
container for all of the other elements that make up a table:

*\<**table**\> \</**table**\>*

This is the first thing that we need to do when creating a table.
You\'ll also notice that I have not typed any attributes. That\'s
because tables have no attributes. Previous versions of HTML had
attributes, however, these have all now been removed, and you shouldn't
add any attributes to the table element.

Next, we need to add a table row. Tables are made up of rows of
information, that go across the page. There are no columns that go up
and down. Columns in HTML are implicit and come about as result of any
number of cells that we add to each row. To add a table row, we add an
opening and closing *\<**tr**\>*tag inside of the table element:

*\<**table**\>*

*\<**tr**\>\</**tr**\>*

*\</**table**\>*

Now that we have a table row, we need a table cell to contain our data.
There shouldn\'t be any content outside of a table cell, such as inside
a row, for example. To add a table cell, we simply insert a pair of
opening and closing *\<**td**\>* tags inside our table row element:

*\<**h1**\>Most Popular Programming Languages\</**h1**\>*

*\<**table**\>*

*\<**tr**\>*

*\<**td**\>Position\<**/td**\>*

*\<**/tr**\>*

*\</**table**\>*

Now that we have a table cell, we can add some data inside it. We will
be creating a table of popular programming languages. If you save what
you have added so far and view it in the browser, you will see that we
have a column, which is the heading for the position of the programming
language:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image21.jpg){width="5.0in"
height="1.8783136482939633in"}

We can create more columns by listing multiple *\<**td**\>* elements one
after the other inside the first row. So, we can add two more columns
using the *\<**td**\>*tag, one for the name of the language and the
other will contain the year when the language first came out:

*\<**table**\>*

*\<**tr**\>*

*\<**td**\>Position\</**td**\>*

*\<**td**\>Name\</**td**\>*

*\<**td**\>Year\</**td**\>*

*\</**tr**\>*

*\</**table**\>*

If we now preview our table so far, we will see that we have added two
more columns:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image22.jpg){width="4.508999343832021in"
height="1.6895166229221348in"}

You will notice that our table does not have any borders and the text
for each column is not highlighted. As with anything in HTML, you can
control the styling, and layout with CSS. We will use another table
element called table head denoted by *\<**th**\>*. The *\<**th**\>*
element has an opening and closing tag just like the table cell, we can
add our data inside this element and it would display it like the table
cell. However, the main difference is that the *\<**th**\>*element acts
as a header column for the data values that come below it. So, if we
replace our *\<**td**\>* cells with *\<**th**\>* tags:

*\<**table**\>*

*\<**tr**\>*

*\<**th**\>Position\</**th**\>*

*\<**th**\>Name\</**th**\>*

*\<**th**\>Year\</**th**\>*

*\</**tr**\>*

*\</**table**\>*

Then save our changes and switch to the browser to see the result:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image23.jpg){width="4.740647419072616in"
height="1.552419072615923in"}

We now have three column headings that have been emboldened, which will
act as our headings for the table. Now that we have added all the
columns, we will add four more rows along with table cells for each
position number, name and year:

*\<**table**\>*

*\<**tr**\>*

*\<**th**\>Position\</**th**\>*

*\<**th**\>Name\</**th**\>*

*\<**th**\>Year\</**th**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>1\</**td**\>*

*\<**td**\>JavaScript\</**td**\>*

*\<**td**\>1995\</**td**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>2\</**td**\>*

*\<**td**\>Java\</**td**\>*

*\<**td**\>1995\</**td**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>3\</**td**\>*

*\<**td**\>Ruby\</**td**\>*

*\<**td**\>1995\</**td**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>4\</**td**\>*

*\<**td**\>Python\</**td**\>*

*\<**td**\>1991\</**td**\>*

*\</**tr**\>*

*\</**table**\>*

We have added four more rows to the table to show the most popular
programming languages. Once you've added the rows and the table cells,
save and preview the table in the browser. Depending on your browser, it
should look something like this:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image24.jpg){width="4.701983814523184in"
height="1.6088713910761154in"}

### Structuring Tables 

There is more to tables than just table rows and table cells. We can add
extra structure for search engines and screen readers. Also, adding
extra structure will come in useful when you want to apply styling, as
you can target the additional elements with CSS.

### Table Head and Body Elements 

Similar to the structure of an HTML document, where we have a head and a
body, we can also add a head and a body to our table. Now, we can\'t use
the same HTML elements, we can use another HTML element called the table
head element or *\<**thead**\>*. This element will wrap around the first
table row that contains our three *\<**th**\>* tags:

*\<**thead**\>*

*\<**tr**\>*

*\<**th**\>Position\</**th**\>*

*\<**th**\>Name\</**th**\>*

*\<**th**\>Year\</**th**\>*

*\</**tr**\>*

*\</**thead**\>*

The table head elements are not required to create a table, but it\'s
nice to define it for search engine crawlers and screen readers, and
it\'s also helpful for styling. When you save and preview this change,
you'll notice that it doesn't actually add anything to the visual
representation, however we can now target this element using CSS and
apply styling.

Next we will add a table body element *\<**tbody**\>*. The table body
will wrap all of the content of our table, except anything that actually
labels our columns, like the table head. Here is our table with a table
head and table body elements added:

*\<**table**\>*

*\<**thead**\>*

*\<**tr**\>*

*\<**td**\>Position\</**td**\>*

*\<**td**\>Name\</**td**\>*

*\<**td**\>Year\</**td**\>*

*\</**tr**\>*

*\</**thead**\>*

*\<**tbody**\>*

*\<**tr**\>*

*\<**td**\>1\</**td**\>*

*\<**td**\>JavaScript\</**td**\>*

*\<**td**\>1995\</**td**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>2\</**td**\>*

*\<**td**\>Java\</**td**\>*

*\<**td**\>1995\</**td**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>3\</**td**\>*

*\<**td**\>Ruby\</**td**\>*

*\<**td**\>1995\</**td**\>*

*\</**tr**\>*

*\<**tr**\>*

*\<**td**\>4\</**td**\>*

*\<**td**\>Python\</**td**\>*

*\<**td**\>1991\</**td**\>*

*\</**tr**\>*

*\</**tbody**\>*

*\</**table**\>*

Once again, adding this element will not add anything visual to our
table, however it will add meaning to our table structure and we can now
target different parts of the table easily with CSS for styling.

### Table Foot Element 

We have a table head and a table body. So, the next logical element to
have would be a table footer element, and that's exactly what we're
going to add next. However, you may be wondering why we would need a
table footer if we already have table headers that label columns and
rows? As with the table head and body elements, there isn't a strict
requirement for the table footer.

It's a nice element to have that should contain a summary of the table.
This could be some final cells that are sums, totals, and averages for
each column, or, meta-information about the table, such as how
frequently the table is updated, copyright information or perhaps the
source of the data within the table.

Now, you would think that the table footer would go at the bottom of the
table. However, the table footer element *\<**tfoot**\>* is placed right
after the table head element and just before the table body element. In
order to get content inside the table footer element, we will need to
add a table row and table cell tags inside it:

Let's add it to our table:

*\<**tfoot**\>*

*\<**tr**\>*

*\<**td**\>*

*Source: Wikipedia *

*\</**td**\>*

*\</**tr**\>*

*\</**tfoot**\>*

Add this piece right after the closing table head tag and just before
the opening table body tag, then save the changes and view the results
in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image25.jpg){width="4.875in"
height="1.7009634733158354in"}

**\
**

### Table Caption Element 

Another nice structural element for tables is the caption element. This
element is basically a title for the table, and it should come
immediately after the opening table tag. This is a really useful element
to include in your table, as it quickly summarizes what a table might
contain. Also, some screen reading software and search engines will pick
up the caption and so will have an idea of what the table is about.

To add the table caption element, just place an opening and closing
caption tag *\<**caption**\>* just after the opening table tag:

*\<**caption**\>Most Popular Languages\</**caption**\>*

This will add a nice table title at the top of the table, so save and
switch to the browser and refresh the page to see the results:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image26.jpg){width="5.122503280839895in"
height="1.927419072615923in"}

Forms 
------

Forms are an essential part of the web, as the web is a two-way
communication medium. As we've seen, there are lots of HTML elements for
displaying information, and conversely, there are also lots of HTML
elements for accepting input. The term 'form' usually refers to a
printed document that contains spaces for you to fill in information. In
HTML, forms are used to accept input from the user. This could be for
contacting someone, buying a product or even registering to vote. Forms
are an important part of web pages, and we'll learn about all of the
most important form elements that web developers use on a daily basis.

To learn about forms, we're going to create a simple sign up form for a
web app. We are going to focus on creating the form layout and not worry
about where the form will submit to and how to process the submitted
information, because we will need server processing to achieve this. For
this part, I will be starting with the file 13\_*forms.html* and we will
be building out the form one step at a time.

### Form Element 

The first element that we will learn about is the form tag element
*\<**form**\>*. This element acts as the container for all the other
form related elements that go inside the form. So, let's start by typing
this out into the file:

*\<**form**\>*

*\</**form**\>*

If you save and preview this on the browser, you will not actually see
anything, as this element is the starting point for forms. Something
worth noting about forms is that you cannot have forms nested inside
other forms because this will simply not work. We mentioned previously
that our form won't actually submit anywhere for processing, however
this can be achieved using a server side language such as Node.js, PHP,
Ruby, or Python.

Part of processing the data involves two important attributes that are
added to the opening form tag and they are the action and method
attributes. The action attribute specifies the address to which this
form will be sent to, but since we don't have any server side program
that can process this form, I will just insert form.html as the value.

The method attribute specifies the method that I would like the browser
to use to submit the form. There are several different methods that we
can use, but usually when submitting a form to a serve,r the post method
is used. Here is how the table element looks like when we've added the
attributes:

*\<**form** action**=**\"**form.html**\" method**="post"**\>*

*\</**form**\>*

Another possible value that we could have used for the method is a GET.
POST corresponds to the HTTP POST method. This means that data from the
body of the form is sent, or posted, to the server. The GET corresponds
to the HTTP GET method, and in this case, the data is sent inside of the
URL, and parameters are separated with a question mark. Most of the
time, you\'ll use the POST method.

### Input Elements 

Now that we have created the containing form element, we will add an
input element *\<**input\>***. The input element is the most commonly
used form element and we\'ll start out with some simple text fields but
later on, we\'ll reuse the input element again in other ways for other
types of input. We're going to make a simple text field where the user
can type in their name. So, let's type it out and then go through the
code:

*\<**form** action=\"form.html\" method=\"post\"\> *

*\<**input** type=\"text\" id=\"name\" name=\"user\_name\" /\> *

*\</**form**\>*

We have created a self-closing input element and added three attributes.
The type attribute indicates what kind of input we want. There are many
possible values for this particular attribute, such as *email*, *tel*
for telephone, and *password* just to name a few. We\'ll be working with
more input types a bit later on.

The *id* attribute is not required, but it\'s a good idea to add one. In
some cases, this is helpful for targeting elements with CSS or
JavaScript. However, in our examples, we\'ll need the *id* attributes so
that we can associate labels to specific form controls. We\'ll learn
more about the label element very soon.

The name attribute is needed so that, when a form is submitted to
server-side code, the server can understand the form data and process
the values appropriately. We\'re going to prefix all our name values
with user and an underscore so that it\'s easier to tell the difference
between the name and the ID. Let's save changes and then switch to the
browser, refresh and see the result:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image27.jpg){width="4.795378390201225in"
height="1.1612904636920385in"}

Let's add a few more text input fields, one for the email address and
one for the password:

*\<**form** action=\"form.html\" method=\"post\"\>*

*\<**input** type=\"text\" id=\"name\" name=\"user\_name\"/\>*

*\<**input** type=\"email\" id=\"email\" name=\"user\_email\" /\> *

*\<**input** type=\"password\" id=\"password\" name=\"user\_password\"
/\>*

*\</**form**\>*

Notice how we are reusing the input element, but for each instance we
are specifying a different value for the type attribute. There are many
more values that we can use to get different input values. For a
comprehensive list of all these values, visit this link
<https://goo.gl/3sQgYC>. Now we can save, switch to the browser refresh
and view the results so far:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image28.jpg){width="4.75in"
height="1.3368678915135608in"}

So, here we have three input elements. The first one is for our name,
the second one is for an email address, and the last one is a password.
You will notice that in the final input element, when you start typing
into the field, you\'ll see that it automatically blocks out the
password that is typed in. Using different values for the type attribute
will produce different results.

As I\'ve mentioned previously, there are many use cases for the input
element and we will be using it again in a different way soon. A quick
note on the layout of the input fields: you will have noticed that they
are horizontally positioned next to each other. This is because we have
no CSS styling applied that dictates how they are positioned.

### Text Area Element 

The input element is great for entering names, usernames and passwords,
however, sometimes a single line of text isn\'t enough and a simple
input element won\'t work. For example, maybe you have a contact form
and you need a place for people to type a message. In this case, it's
best to use the ***textarea*** element *\<**textarea**\>*.

In our form, we will add a text area so that users can type in
sentences. So, after the password input element, add the following code
for a textarea:

*\<**textarea** id=\"bio\" name=\"user\_bio\"*\>

*\</**textarea**\>*

If we save and switch back to the browser and refresh, you can see that
the text area allows us to type in multiple lines:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image29.jpg){width="4.516128608923885in"
height="1.3912937445319336in"}

On the bottom right corner of the text area element is a little
triangle. What this means is that we can resize the text area if we
wanted to. As you can see, the ***textarea*** element is different from
the input element, in that it isn't a self-closing tag. You need to type
an opening and a closing tag for it to work.

In most browsers, a text area is resizable by the user. There are ways
to prevent this if you like, but it is highly recommended to leave this
default behavior unmodified. That way, if the user would like more space
to type in any direction, they can adjust it however they want.

### Button Element 

A form is not complete without a submit button and in HTML, there are a
couple of ways for creating a button, and you will likely see one or the
other when you look at the source code of other web pages. We're going
to look at both ways of creating a button starting with using the input
element again. As you've already seen, the input tag can be used to
create different elements on the web page simply by specifying a
different type value.

When using the input tag to create a button, we give the *type*
attribute a value of *button*, and we add another attribute called
value, whose value will be the text for the button. Let's code this out.
Put the following markup after the text area element:

*\<**input** type=\"button\" value=\"Submit\" id=\"submit\"\>*

As you can see, we have used the input tag again. Along with specifying
button as the type, we need to also specify a value attribute and the
value for this attribute will be the text that is displayed on the
button. Let's save this, switch to the browser and refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image30.jpg){width="4.625in"
height="1.2292465004374453in"}

The second way that we can create a button is using the button element
*\<**button**\>*. Unlike the input element, the button element has a
closing tag. To add a button using the *\<**button**\>* is
straightforward:

*\<**button** type=\"submit\" id=\"submit\"\>Submit\</**button**\>*

The type value in this particular case is *submit*. But there are two
other types called Reset and Button. The Reset type will automatically
clear all form data when it\'s clicked. The Button type has no default
behavior, and it\'s mostly intended to be used in combination with
JavaScript. The type value we\'ve used here is *submit*. As the name
implies, the default behavior of the *submit* type is to submit the form
and send all the data over to the server. Let's save this and switch to
the browser and refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image31.jpg){width="5.127878390201225in"
height="1.3629035433070866in"}

You will notice that there is no change in the output on the web page.
You can use either the input element or the button element to create a
button in HTML.

### Labels and Fieldsets 

At the moment, it's difficult for the user to tell which form control
does what. There's no way to know if the bio field is for their email or
if the email field is for their password. As you have already seen, a
form can be created with just the form element and input tags. However,
it's helpful to the user if the form is organized with labels and
fieldset elements.

Let's start by adding a label for the name field. We will use the label
tag \<label\>. This tag requires an opening and closing, so we're going
to add a label just before the input field for the name:

*\<**label** for=\"name\"\>Name:\</**label**\>*

*\<**input** type=\"text\" id=\"name\" name=\"user\_name\" /\>*

For the label to be added to the correct field, we need to specify a
*for* attribute and the value for this will be the id of the name field,
which happens to be called name. This is why we added IDs to our form
controls so that we can add labels and reference each field with an id.
Save your changes then switch to your browser and refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image32.jpg){width="4.457646544181977in"
height="1.2701607611548555in"}

As you can see, this has now added a label for the name field. The user
can distinguish what needs to be entered in this field. Let's add a
label for each of the form controls:

*\<**label** for=\"name\"\>Name:\</**label**\>*

*\<**input** type=\"text\" id=\"name\" name=\"user\_name\" /\>*

*\<**label** for=\"email\"\>Email:\</**label**\>*

*\<**input** type=\"email\" id=\"email\" name=\"user\_email\" /\>*

*\<**label** for=\"password\"\>Password:\</**label**\>*

*\<**input** type=\"password\" id=\"password\" name=\"user\_password\"
/\>*

*\<**label** for=\"bio\"\>Your bio:\</**label**\>*

*\<**textarea** id=\"bio\" name=\"user\_bio\"\>*

*\</**textarea**\>*

Now that we have added labels for each of the form controls, we can save
our changes and switch to the browser and refresh to see the result:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image33.jpg){width="4.072580927384077in"
height="1.0691754155730533in"}

Our form is starting to take shape and the user can now fill out the
form and know what is required in each form field. Let's now look at how
we can use ***fieldset*** to group similar form controls together.

### Fieldset and Legend

The main purpose of a ***fieldset*** is to group together form controls.
Sometimes, certain form controls belong together in a logical grouping.
In our case, we will create two groups, one for basic information and
one for information that will show up in the user's profile. Wrapping
our form controls using the ***fieldset*** element can do this.

We'll wrap all the input fields and the labels in a ***fieldset***
element and the text area and its label can be wrapped in another
***fieldset***:

*\<**fieldset**\>*

*\<**label** for=\"name\"\>Name:\</**label**\>*

*\<**input** type=\"text\" id=\"name\" name=\"user\_name\" /\>*

*\<**label** for=\"email\"\>Email:\</label\>*

*\<**input** type=\"email\" id=\"email\" name=\"user\_email\" /\>*

*\<**label** for=\"password\"\>Password:\</label\>*

*\<**input** type=\"password\" id=\"password\" name=\"user\_password\"
/\>*

*\</**fieldset**\>*

*\<**fieldset**\>*

*\<**label** for=\"bio\"\>Your bio:\</**label**\>*

*\<**textarea** id=\"bio\" name=\"user\_bio\"\>*

*\</**textarea**\>*

*\</**fieldset**\>*

*\<**button** type=\"submit\" id=\"submit\"\>Submit\</**button**\>*

This creates a logical grouping of the form controls, all the input
elements and their labels are grouped into one ***fieldset*** and the
***textarea*** element and its label are put into another logical group.
If you had more fields, you could use more ***fieldset*** to group them
together. If we save and switch over to the browser, then refresh, we
can see these logical groupings applied visually:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image34.jpg){width="4.5in"
height="1.8227712160979876in"}

The default user agent or browser CSS applies a border to each
***fieldset*** to show that they are grouped together in a
***fieldset***. We can use CSS to override the default styling and apply
our own custom CSS.

In addition to grouping the form elements into ***fieldset***, we can
also label the different logical groupings and we can achieve this using
the HTML legend element. The legend element has both an opening and
closing tag and we place this just after the first opening
***fieldset*** tag for each logical grouping:

*\<**fieldset**\>*

*\<**legend**\>Basic Info\</**legend**\>*

*\<**label** for=\"name\"\>Name:\</**label**\>*

*\<**input** type=\"text\" id=\"name\" name=\"user\_name\" /\>*

*\<**label** for=\"email\"\>Email:\</label\>*

*\<**input** type=\"email\" id=\"email\" name=\"user\_email\" /\>*

*\<**label** for=\"password\"\>Password:\</label\>*

*\<**input** type=\"password\" id=\"password\" name=\"user\_password\"
/\>*

*\</**fieldset**\>*

*\<**fieldset**\>*

*\<**legend**\>Profile\</**legend**\>*

*\<**label** for=\"bio\"\>Your bio:\</**label**\>*

*\<**textarea** id=\"bio\" name=\"user\_bio\"\>*

*\</**textarea**\>*

*\</**fieldset**\>*

*\<**button** type=\"submit\" id=\"submit\"\>Submit\</**button**\>*

The legend element will label each ***fieldset***. I have labelled the
first ***fieldset*** basic info and the second one profile. Let's save
our changes and then switch to the browser and refresh to see the
results:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image35.jpg){width="4.669354768153981in"
height="1.7889818460192477in"}

As you can see once again, the default browser styling is being applied
to the legend element. You can easily change this using CSS. If you
think back to the last time you filled out a form, it is more than
likely you were presented with predefined options to choose from at some
point. We can add predefined options using menus, radio buttons, or
checkboxes.

### Select Menus 

Depending on the type of predefined options that you are presenting to
your user, you will at some point have the need to list several options
for the user to choose from. In this situation, it's best to go with a
select menu. Let's say that in our form we want to capture the job title
of the person filling out our form. For this we are going to list four
job titles: Web Designer, User Experience, Front-end Developer, and
Back-end Developer. We will present these options as a select menu.

So, under the biography, which is represented by the ***textarea***
element, we will add our select menu options using the \<select\>
element. Just before adding the select menu, we will create a label for
the select menu and then the select menu itself:

*\<**label** for=\"job-title\"\>Job Title\</**label**\>*

*\<**select** id=\"job-title\" name=\"user\_job-title\"\>*

*\<**option** value=\"web-designer\"\>Web Designer\</**option**\>*

*\<**option** value=\"user-experience\"\>User Experience\</**option**\>*

*\<**option** value=\"front-end-developer\"\>Front-end
Developer\</**option**\>*

*\<**option** value=\"backend-developer\"\>Back-end
Developer\</**option**\>*

*\<**option** value=\"business-owner\"\>Business Owner\</**option**\>*

*\<**option** value=\"freelancer\"\>Freelancer\</**option**\>*

*\</**select**\>*

We create the label just like we have done previously, so there is
nothing new there. The select element acts as the container for each of
the options that the user will be able to choose from a drop-down menu.
I have given the select element an ID of job-title as this should match
the value for the *for* attribute and we have also added a *name*
attribute with the value of *user\_job-title*. To actually get options
listed in a select menu, we need to add option elements, and these are a
pair of opening and closing tags.

Inside each option element we need to add a *value* attribute, which
corresponds to the option that is presented to the user. The idea here
is that when you submit the form to the server side code, each form
element has an associated value for text inputs and text areas, and this
value is whatever the user types into the field. Since we're creating
these predefined options, we need to specify what the value should be
when selected by the user and the form is submitted. Let's save what we
have added, then switch over to the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image36.jpg){width="5.625382764654418in"
height="2.072580927384077in"}

As you can see, we have a nice select menu along with its label. If you
click on the drop down, you will see that all our job titles are listed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image37.jpg){width="2.432014435695538in"
height="1.6088713910761154in"}

We can further organize our list of job titles, just like we organized
the form controls using ***fieldset***, by using the *\<**optgroup**\>*
element, which stands for option group. Just like the fieldset element,
the *\<**optgroup**\>* tag wraps around a group of option tags. We will
add two *\<**optgroup**\>* tags, one for development roles and the other
for business related roles:

*\<**label** for=\"job-title\"\>Job Title\</**label**\>*

*\<**select** id=\"job-title\" name=\"user\_job-title\"\>*

*\<**optgroup** label=\"Development\"\> *

*\<**option** value=\"web-designer\"\>Web Designer\</**option**\>*

*\<**option** value=\"user-experience\"\>User Experience\</**option**\>*

*\<**option** value=\"front-end-developer\"\>Front-end
Developer\</**option**\>*

*\<**option** value=\"backend-developer\"\>Back-end
Developer\</**option**\>*

*\</**optgroup**\>*

*\<**optgroup** label =\"Business\"\> *

*\<**option** value=\"business-owner\"\>Business Owner\</**option**\> *

*\<**option** value=\"freelancer\"\>Freelancer\</**option**\>*

*\</**optgroup**\>*

*\</**select**\>*

We have now created two option groups, one for development and one for
business. You will note that the *\<**optgroup**\>* element has an
attribute of *label*. This is not the same as the label element, and the
role of this attribute is to display a label inside the dropdown menu
for each respective group. Save everything, and the switch to the
browser and refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image38.jpg){width="2.3826388888888888in"
height="1.6692300962379703in"}

You can see that our options are organized neatly into two groups:
Development and Business. The actual labels themselves are not
selectable, as they are not part of the options. You can also further
style this using CSS to add maybe a horizontal line after the labels to
make it look more visually appealing.

### Radio Buttons 

We have quite a few options when it comes to presenting our users with
predefined options. The select menu is great for lots of options,
however, if you have something like five or less options, then it's
better to use radio buttons. Just like select menus, the user can only
pick from the options given. In our form, let's say that we have some
terms and conditions and we want to know whether the person signing up
has read and agrees to them. For this we will use radio buttons.

Just after the select menu we will add two labels, and inside these
labels we will add *I agree to T&Cs* and *I disagree* respectively.
After each label, we will add our radio button for each option:

*\<**label**\>I agree to T&amp;Cs\</**label**\>*

*\<**input** type=\"radio\" id=\"agree\" value=\"agree\"
name=\"user\_agree\" /\>*

*\<**label**\>I disagree\</**label**\>*

*\<**input** type=\"radio\" id=\"disagree\" value=\"disagree\"
name=\"user\_agree\" /\>*

You will notice that the labels do not have a *for* attribute, and to
create radio buttons I am using the input element once again, only this
time the type value is radio. We have also created id attributes that
correspond to user choices, whether they agree or disagree. If we now
save this and switch over to the browser and refresh, we can see our two
radio buttons:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image39.jpg){width="4.707650918635171in"
height="1.6612904636920385in"}

In the HTML markup, the name value is the same for both radio buttons.
This is to prevent the user from selecting both radio buttons. At the
moment, when you select one radio button and then try to select another
option, you\'ll see that

the browser deselects the previous option, and the way that it knows to
do that is because we have the name attribute exactly the same. So, it
knows that these two radio buttons are part of the same group.

We have not added any new markup besides the type value for the input to
create the radio buttons. All of the other attributes are pretty much
self-explanatory.

### Checkboxes 

Forms can contain a variety of options. Sometimes, you might have a
group of predefined options, but you want the user to be able to select
multiple options and not just one of them. HTML gives us the option to
use checkboxes, and that's what we will be adding to our form next. In
our sign up form, let's say that we wanted the user to be able to tell
us which major topic areas are interesting to them. They might be
interested in more than one topic, and this is perfectly acceptable as
we can use checkboxes to receive this input. I'll add some checkboxes
just after the closing select menu element and before the radio buttons
inside a new third ***fieldset*** element:

*\<**fieldset**\>*

*\<**label**\>Interested to learn about:\</label\>\<**br** /\>*

*\<**input** type=\"checkbox\" id=\"development\"
value=\"interest\_development\" name=\"user\_interest\" /\>*

*\<**label** for=\"development\"\>Development\</**label**\>\<**br** /\>*

*\<**input** type=\"checkbox\" id=\"design\" value=\"interest\_design\"
name=\"user\_interest\"\>*

*\<**label** for=\"development\"\>Design\</**label**\>\<**br** /\>*

*\<**input** type=\"checkbox\" id=\"business\"
value=\"interest\_business\" name=\"user\_interest\" /\>*

*\<**label** for=\"business\"\>business\</**label**\>\<br /\>*

*\<**label**\>I agree to T&amp;Cs\</**label**\>*

*\<**input** type=\"radio\" id=\"agree\" value=\"agree\"
name=\"user\_agree\" /\>*

*\<**label**\>I disagree\</label\>*

*\<**input** type=\"radio\" id=\"disagree\" value=\"disagree\"
name=\"user\_agree\"\>*

*\</**fieldset**\>*

Let's go through the code line by line. The first thing that I added
right after the closing ***fieldset*** tag for the text area and select
menu is a third ***fieldset*** group that will house the checkboxes and
the radio buttons. To do this, I created a new ***fieldset*** element
with opening and closing tags. Then I added a label, again without a
*for* attribute, to act as a title for the checkboxes. Inside the label,
I added the text *Interested to learn about*.

You will also see that I added a *\<**br** /\>* tag. This is to create a
new line for the checkbox and is something that I have added to the end
of each label for the checkboxes, so that we can have the checkboxes and
the labels positioned vertically.

Now it's time to actually add the checkboxes, and to do that, I used the
input element with the type value as a *checkbox*. This will create a
checkbox, but just like the elements that we have previously created, we
need to specify an *id* and a *value* attribute. The id attribute will
be used for labelling the checkbox and the value attribute is used on
the server side to ascertain what the user actually selected.

For each of the values I have prefixed interest and then followed by an
underscore and the actual topic. So this is not new, as we've actually
done something like this with the select menus. Then I added a label for
each interest, and this label has a *for* attribute so that it is
associated with the correct input element. This process is repeated for
each of the three interests that are listed for the user to select from.
If we save the code and switch to the browser and refresh, we can see
that we now have the option for the user to select one or more interests
via checkboxes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image40.jpg){width="4.707670603674541in"
height="2.1048392388451442in"}

Forms play an important role in gathering data from users, and as we've
seen, HTML provides us with all the tools that we need to replicate the
traditional paper based forms that we have become accustomed to.

HTML Special Characters
-----------------------

In HTML, we can pretty much display all kinds of characters, however,
there are special characters that include various punctuation marks,
accented letters, and symbols. When we type these directly into the HTML
code, they can be mistaken for the wrong character, and this means that
special characters need to be encoded.

There are hundreds of special characters that can be used with HTML, and
these are encoded between an ampersand & and a semi-colon. Everything
between the ampersand and the semi-colon is a character's unique
encoding; this could be a name or numeric encoding.

When you want to include an ampersand, you have to use its special
encoding characters so that the browser renders it properly. You might
have noticed in our code for the form when we created the label for the
radio button that we used an encoding to display the ampersand: *&amp;*.
If you simply type out the ampersand as you would in a word processor,
some browsers will display a weird looking character. Likewise, if you
want to display the @ or copyright symbols, you would use *&commat;* and
*&copy;* respectively. For a full list of how to encode special
characters in HTML, visit <http://goo.gl/TDBevm>

**\
**

IDs & Classes 
--------------

One concept that is important for all web designers and developers to
understand is that of IDs and classes. We have already used IDs quite a
lot so far, as we needed these to match up labels with the correct
elements. Both IDs and classes can be added as attributes of any HTML
element. If you think back to all of the markup that we have coded up,
we can add either an id or a class, or even both. We haven't added any
classes so far to our mark up. This is because they are primarily used
for styling and we haven't added any styling to our HTML so far.

### ID's are unique and classes are not 

Each element on a web page can have only one ID attribute, and each page
can only have one element with that ID. When you are first starting out
in web design and development, this is something that you will hear time
and time again. You should never use an ID more than once in any
instance on an element or each web page. Code that has multiple IDs that
are the same on one page will not pass validation. Furthermore, when you
add more functionality using JavaScript, and you are trying to get the
value of an element with a specific ID, you will run into issues and
this could create bugs on your web page or web app.

IDs also have a special functionality that is not available with
classes, and that is when they are used with hash values in a URL. If
you think back to the section where we created hyperlinks within a web
page, we used an ID to act as the location, and in the value for the
href, we simply prefixed the hash or pound symbol (\#), and used the ID
value of where we wanted to the browser to scroll to.

Classes, on the other hand, are not unique, and you can use the same
class on multiple elements, and you can also add multiple classes to the
same element. This is really useful, because it means any styling
information that needs to be applied to multiple objects on a page can
be done with just one class. This means that in your CSS, you create
style declarations under that name and when you add that class as an
attribute to any element on the web page, it will have that styling
applied to it. This is something that we will be doing extensively in
the CSS section.

We add classes the same way that we have been adding IDs to the
elements. Let's say that we want to add a class to the *\</**h1**\>* tag
in our form page. We simply add the word class as an attribute and the
value is whatever name we want to use for the class:

*\<**h1** class=\"heading-one\"\>Sign Up Form\</**h1**\>*

You can use whatever name you would like as the class name. The class
name must be between either single or double quotes, and there must be
no space between multiple words. If you add a space between multiple
words, each instance of the word on its own will be a class. You can
distinguish multiple words by using either a hyphen, camel case, (this
is making each subsequent word's first letter upper case -- e.g.
*headingOne)*, or use an underscore character: *heading\_one*.

If you want to apply additional styling that is unique to an element
that shares styling with several other elements, you can do so by adding
additional classes with a space:

*\<**h1** class=\"heading-one another-class \"\>Sign Up Form\</**h1**\>*

The heading element now has two classes and you can add additional
styling using the second class that will only be applied to this h1 tag
or wherever else it is used. You can add as many classes as you need, as
most browsers support any number of them and way more than you'll ever
need.

It's also worth knowing that simply applying an id or a class will not
do anything to that element, unless you have added a specific styling
for that class and the CSS is linked to the web page. However, there are
instances when you can simply add a class to any element and styling
will be applied when you save and reload. This is if you load
pre-written CSS styles into your web page and you simply add the classes
defined in the CSS to the elements to apply the styling. A popular
example of this is [Twitter's bootstrap](http://getbootstrap.com/css/)
framework: <http://getbootstrap.com/css/>

The fact that you can add IDs and classes doesn't mean that you should
be adding them to every element. You should use IDs and classes
judiciously and semantically. Only add them when there is an actual
need, as you will be able to apply styling to most elements using only a
few classes and the element tags.

Span & Div 
-----------

As we have already seen with the *\<**em**\>* and *\<**strong**\>*
elements, you can add semantics, which is just a fancy word for giving
content on the page meaning and structure, within HTML. However, there
are two elements that are widely used but don't actually hold any
semantic value, these are the division \<div\> and *\<**span**\>*
elements.

These two elements act as containers for styling purposes, and as such,
do not come with any semantic meaning or value. Before exploring these
two elements, we need to understand what is meant by a block and inline
element.

Whenever you hear that an element is a block-level element, what this
means is that this kind of element begins on a new line, and that it
occupies any available width. Block-level elements can be nested inside
one another. Examples of block-level elements include *\<**h1**\>*,
*\<**p**\>* and *\<**div**\>*.

Inline-level elements do not begin on a new line, instead they fall into
the normal flow of a document, lining up one after the other. Inline
elements only maintain the width of their content, and they can be
nested inside one another. Examples of inline elements that we have used
so far include: the anchor tag *\<**a**\>*, the image tag *\<**img**\>*
and the *\<**span**\>*.

A *\<**div**\>* is a block-level element that is used as container for
large groupings of content, which helps to build a web page's layout and
design. A *\<**span**\>*, on the other hand, is an inline-level element,
which is used as a container for smaller groupings of text within a
block-level element. More than likely, you will see *\<**div**\>* and
*\<**span**\>* with class or id attributes for styling purposes. Let'
see the two elements in action. For these examples, I'm using the file
*14\_div-span.html*.

*\<**!DOCTYPE html**\>*

*\<**html**\>*

*\<**head**\>*

*\<**title**\>Div and Span\</**title**\>*

*\</**head**\>*

*\<**body**\>*

*\<**h1**\>Div and Span\</**h1**\>*

*\<**div**\>*

*\<**p**\>*

*A div tag is a block level element, and this means that it will take up
all available width space. A **\<span\>**span**\<**/**span\>** element,
on the other hand, falls into the normal flow of a document.*

*\</**p**\>*

*\</**div**\>*

*\</**body**\>*

*\</**html**\>*

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image41.jpg){width="4.625in"
height="1.580858486439195in"}

Here I have added a div, nested inside this is a paragraph, which
contains some text and a span element. You will notice that the
*\<**div**\>* sits on its own new line, as it's a block level element,
whereas the *\<**span**\>* element falls nicely into the flow of the
text without taking up all available width. Even though these two
elements don't have any semantic meaning or value, they are nonetheless
very useful and widely used.

HTML5 Web Page Structure 
-------------------------

The latest edition of HTML, which is HTML5, added semantic elements to
provide meaning and structure to web page documents. Some of these
elements that add semantics and structure include: *\<**header**\>*,
*\<**section**\>*, *\<**article**\>*, *\<**aside**\>*, and
*\<**footer**\>*. All these elements are block-level, and simply using
them instead of \<div\> to structure your page won't apply any
positioning or styles, these have to be added via CSS.

Let's take a visual look at how we can use the HTML5 elements to create
structured web page documents with semantic value:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image42.jpg){width="4.557257217847769in"
height="3.102777777777778in"}

### Header 

The header element, as its name suggests, is used to create a container
for the top of the page. In most websites that make use of the HTML5
structuring elements, you will also have a heading, text and the
navigation inside the header element. Sometimes it's easy to confuse the
*\<**header**\>* element with the *\<**head**\>*. The *\<**head**\>*
element comes before any structuring of the page is actually created.
This is where you add the page title, any meta tags and references to
any style sheets. So going forward, make sure to use the correct element
when creating your web pages.

### Navigation 

Within the *\<**header**\>* element, you typically add the navigational
links on the website. HTML5 now has a *\<**nav**\>* element that you can
use as a container for all the links to other pages on the website.

### Section 

The *\<**section**\>*, element is used to group related content into
their own section. Much like you would use the *\<**div**\>* element as
a container for a group of elements and to also apply styling, you can
do the same with the *\<**section**\>* element.

### Article 

The *\<**article**\>* element can be used to identify a section of
independent, self-contained content. You can use the *\<**article**\>*
content for blog posts, newspaper articles etc. This element acts as a
wrapper for content that can be removed from the web page without having
any impact on the semantic structure of the web page. In order to help
you determine when to use the *\<**article**\>* element, you just need
to check if the content can be replicated elsewhere without any
confusion. For example, if the content within the *\<**article**\>*
element is removed from the context of the page, and put inside a
magazine, this content should still make sense on its own.

### When to use \<section\> or \<article\> 

The article and section elements are probably the most confusing to web
designers and developers. To most people, these elements seem very
similar and there\'s a lot of confusion, even among experienced
developers, around when to use one over another. In many cases, it\'s
really just a judgement call as to which one to use.

### Aside 

One of the most common elements of websites is the sidebar. They\'re so
ubiquitous; in fact, that it can seem rather odd if you go to a site and
it doesn\'t have one. However, even though they are one of the most
common page elements of all time, until the HTML5 specification, there
wasn\'t a semantic element designed to represent the type of content
that you would normally associate with a sidebar.

The \<aside\> element represents a section of a page, which consists of
content that is loosely related to the content around the aside element.
You would typically see content that is found in a sidebar to be put in
its own section in printed typography, also in a sidebar.

The element could be used for typographical effects like quotes or
sidebars, for advertising, for groups of *\<**nav**\>* elements and for
other content that is considered separate from the main content of the
page. The aside element is a sectional element, and this means that if
it\'s used in your content, there\'s a new section in the document.

### Footer 

The *\<**footer**\>* element identifies the closing or end of a page,
article, section, or other segment of a page. Generally, the
*\<**footer**\>* element is found at the bottom of its parent. Content
within the \<footer\> element should be relative information such as
links to other sections of the web page, contact details, disclaimers
etc.

### Abbreviations, Acronyms & Quotes 

In HTML, there are some text elements that are not intended to affect
the structure of your web pages, but their main purpose is to add extra
information to the web page. If you want to include an abbreviation or
an acronym, then you can use the *\<**abbr**\>* element. Let's look at
an example. I'm using the file *15*\_*semantic-markup.html*:

*\<**!DOCTYPE html**\>*

*\<**html**\>*

*\<**head**\>*

*\<**title**\>Semantic Markup\</**title**\>*

*\</**head**\>*

*\<**body**\>*

*\<**h1**\>Semantic Markup\</**h1**\>*

*\<**p**\>\<abbr title=\"Doctor\"\>Dr\</abbr\> Paul Bergin has authored
many books in the field of medicine\</**p**\>*

*\<**p**\>\<**abbr** title=\"HyperText Markup
Language\"\>HTML\</**abbr**\> is used to create web pages\</**p**\>*

*\</**body**\>*

*\</**html**\>*

When you use the abbreviation element or an acronym, a title attribute
on the opening tag is used to specify the full term. Before HTML5, a
separate element, \<acronym\>, was used for acronyms.

There will be times when you want to include a quote on your web pages,
and in HTML, there are two elements that can be used to help you achieve
this. The first is the *\<**blockquote**\>* element. This element is
used for longer quotes that take up an entire paragraph:

*\<**p**\>Brue Lee:\</**p**\>*

*\<**blockquote**\>*

*If you spend too much time thinking about a thing, you\'ll never get it
done. *

*\</**blockquote**\>*

Browsers usually indent the content of the *\<**blockquote**\>* element.
Let's save and switch to the browser then refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image43.jpg){width="4.625in"
height="2.012153324584427in"}

**\
**

Day Three 
==========

Getting started with CSS
------------------------

In this section, we\'re going to learn the basics of CSS, or Cascading
Style Sheets. CSS is one of the core technologies for designing and
building Web sites and applications. No matter what kind of Web site or
web application you want to build, you\'ll have to use CSS. In this
section, we\'re going to dive a little deeper into many of the core
concepts of CSS and practically apply them so that we can fully
understand how CSS works with HTML.

So, what exactly is CSS and why is it considered a core web technology?
CSS is a stylesheet language that describes the presentation of Web
pages. HTML, as you've already seen, forms the structural foundation of
a web page, CSS is what we use to style the HTML with colors,
backgrounds, font sizes, layout, and much more.

We\'ll start with basic CSS concepts, then gradually progress to more
advanced concepts. To get familiar with the most important parts of CSS,
we\'re going to style the HTML structure of a simple landing page for
the beautiful city of Grenada, Spain.

We\'ll start off by learning the different ways we can apply CSS to a
page. Then we\'ll add nice design layers to our page with basic
selectors, common CSS properties and values.

Introduction to CSS
-------------------

CSS is a language that allows us to make designs that are well organized
and beautiful. While HTML describes the structure of information, CSS
describes how that information should be visually presented. In this
section, we will spend some time learning about the syntax of CSS, and
apply what we learn by building out a beautiful landing for the city of
Granada.

CSS stands for Cascading Style Sheets. The style sheet portion of this
term is obvious. It just means a document that describes the visual look
of a webpage. The cascading portion of this term is also important, as
it means each CSS rule has the potential to override or cancel out
previous rules. This is something that we will explore in more detail
later on.

Back in the early days of the web before CSS was introduced, developers
would have to embed presentational tags and attributes into HTML to
control the design of a Web page. Many of those tags were privately
owned tags by companies that only worked on the browsers that they
created. So, providing support and, maintaining a consistent look for
every browser was nearly impossible.

When styling was embedded into the HTML, it made it difficult to
separate out the content from the presentation. Web developers would
have to manually edit tens or, hundreds of HTML files to make a single
styling change. Developers sought a better way and CSS was finally
introduced in HTML 4 to help solve many of these problems. With CSS, web
developers finally had a way to express their designs without having to
add new HTML tags.

By separating the content from the presentation, CSS made the
development and maintenance of Web sites more efficient because the
styles written in a single CSS file could be shared across multiple Web
pages. Over the years, CSS has also improved the accessibility of web
content because it\'s allowed us to adapt our content to various
devices, screen sizes, and resolutions.

User agent styling
------------------

In web development, you will come across the terms user agent or user
agent styling. User agent in general means a piece of software that is
acting on behalf of a user. In our context, the user agent is the
browser, which acts on behalf of the user to make requests for web pages
and resources and then displays this to the user. User agent styling or
user agent style sheets, are the default sets of style declarations
applied by the user agent, i.e. the browser. For example, the default
styling for content that is in between an anchor tag \<a\> is an
underline when the user hovers over the link.

Inline Styles 
--------------

***Exercise File: css-section/1-getting-started-with-CSS/
1-inline-and-internal-styles/start***

There are four ways we can add CSS styles to our web pages:

1.  Inline styles

2.  Internal styles

3.  External styles

4.  Importing them inside a CSS file

We will start by adding styling to individual elements using the inline
style rule. Inline styles are CSS styles that are applied to one element
using the style attribute. In the exercise files under the folder called
*css-section*, go into the *getting-started-with-css* folder. There you
will see an index file that contains some HTML markup for the Grenada
landing page. For now, we\'re only working with the header of the page,
and an introductory paragraph about Granada. You will also see a folder
named CSS, which we\'ll be using to store our CSS files very soon. If
you double click the *index.html* file, it will open in your default
browser and you should see the beginnings of our landing page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image44.jpg){width="4.883907480314961in"
height="1.6693547681539807in"}

As you can see in the browser preview, our page is currently not styled.
But remember that even if we haven\'t written a single line of CSS for
the page, browsers use the user agent style sheet that gives certain
elements some default styling. That way users can still have a somewhat
presentable and, readable experience by default.

So, if you're wondering where this default style is coming from, it's
the user agent styling in action. This is why we can see some white
space around the page, below the headings, paragraphs and between lines
of text. These are the default styles applied by the browser. As we
mentioned previously when we talked about the user agent styling, if we
opened this page in Firefox, Safari or, Internet Explorer, it would
still look just like this.

Let's write our first lines of CSS using the inline method. We will
start by adding styling to individual elements using the inline style
rule. Inline styles are CSS styles that are applied to one element using
the style attribute.

So, in our *index.html* file let\'s style the body element. To add
inline styles, we'll use the style attribute, and we'll make the
background a color of orange. Here is the code to do that:

\<**body** *style*=\"background-color: orange;\"\>

In the *index.html,* I've given the body element a *style* attribute,
then inside the quotation, I've added the property that I want to style,
which is the background using *background-color* followed by a colon and
a space, then the word *orange* and a semicolon.

Now, when we save our HTML file and switch over to the browser and
refresh the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image45.jpg){width="5.593400043744532in"
height="0.7898151793525809in"}

We can see how this makes the background color of our page orange. We
can add styling to any element using the inline method. Let's add some
styling to the h1 element. We're going to do the same thing as we did
with the body element, and that is to add a style attribute and make the
color of the text white:

\<**h1** *style*=\"color: white;\"\>Granada, Spain\</**h1**\>

When we save our *index.html* file, and refresh the browser preview, we
see how the main heading text changes to the color white:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image46.jpg){width="5.0in"
height="2.0355424321959754in"}

As you can see, we can style any element with any CSS property, using
this in-line style method. We could style the entire page with this
method if we wanted to, however, this is not recommended.

Inline styles are not considered a good practice for developing
websites, and they should be used sparingly if at all. Because if we
need to make any styling changes, it means we need to go inside our html
to make those changes.

So, we\'re not really separating content from presentation and this
means that the CSS gets scattered throughout the file, which makes
maintenance difficult and impractical. For example, if there were a
dozen web pages on a site and you were using inline styling, whenever
you wanted to change a style, say the color of all h1 elements, you
would have to go into each individual HTML page and make the changes. As
you can imagine, this involves a lot of work and repetition and becomes
very difficult when the website scales to hundreds of HTML pages.

Inline styles are also at the lowest level possible in terms of the
cascading rule in CSS. This means that they are very powerful and
specific and will override other styles applied to an element. For
example, if we declare a new background color style for the body or a
color style for the h1 element in an internal or external style sheet,
we won't be able to see those changes because these inline styles will
always override them, as we will soon see.

Inline styles may come in handy when creating quick HTML and CSS
markups, or, if we want to test something quickly, we can use the inline
style method for debugging purposes or writing temporary fixes.

Internal styles
---------------

The second way we can add CSS to a page is with internal styles.
Internal styles are usually embedded in the head section of the HTML
document by using a style tag. That's what we're going to do, so, inside
the head element, right beneath the title tag, create an opening and
closing style tag like so:

\<**head**\>

\<**title**\>Granada\</**title**\>

\<**style**\>

\</**style**\>

\</**head**\>

This time we\'re going to style the paragraph by making the font size
bigger. Here's how we can do that:

\<**style**\>

p {

font-size: 20px;

}

\</**style**\>

So, in between the style tag, I have targeted all paragraphs by writing
*p*, then followed by a set of curly braces. I created little space by
hitting the tab key, then I've specified the property that I wish to
style, which is the font size, by using font-size, followed by a colon
and a space, then I've written 20 px and a semicolon.

The *px* stands for pixels, and this will be explained in more detail
later on. If we now save our changes and switch back to the browser
preview, we will see that our text is now slightly bigger:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image47.jpg){width="3.928976377952756in"
height="2.2177416885389327in"}

If we go back into our style tag and this time let's make the font
weight slightly bolder, and you can probably guess which property we can
use to make this happen using CSS. We can apply multiple styles to a
single element inside the curly braces. To do that, I'm simply going to
hit Return or, Enter, and right below what we just wrote, I\'m going to
write *font-weight*, followed by a colon and a space, then the word
bold, and a semicolon:

\<**style**\>

p {

font-size: 20px;

font-weight: bold;

}

\</**style**\>

We've already used a couple of CSS properties, values and syntax without
explaining them. Don\'t worry about these properties for now, we\'ll
cover a lot of that throughout this section. Just know that the styles
inside these curly, braces will increase the paragraph\'s text size and
make it bold. So, let\'s save our changes and take a look at it in the
browser, then in the browser preview, click the refresh button to see
the changes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image48.jpg){width="3.7358541119860016in"
height="1.75in"}

You will immediately notice how the text in our paragraph is now larger
and bold. Let's do the same for our headings. So, let's go back to our
html file, and underneath the styling for the paragraph and the last
curly brace, we\'re going to style the h1 element in our page by writing
h1, followed by a space and a set of curly braces. Then, inside the
curly, braces we\'re going to write font-size followed by colon, a
space, then we're going to write 90px and a semicolon:

\<**style**\>

p {

font-size: 20px;

font-weight: bold;

}

h1 {

font-size: 90px;

}

\</**style**\>

To see the changes, as usual save and then preview in the browser by
clicking refresh. You will see that we have a pretty large heading on
the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image49.jpg){width="5.763888888888889in"
height="3.421527777777778in"}

Now that the font size is bigger, let's change the text color to
firebrick red. We can easily change this by going into the h1 selector
and adding a *color* property followed by the color keyword *firebrick*:

\<**style**\>

p {

font-size: 20px;

font-weight: bold;

}

h1 {

font-size: 90px;

color: firebrick;

}

\</**style**\>

So, if we save our *index.html* file, go back to the browser preview and
refresh the page. You will notice that nothing happens, the *h1* is
still white. You might have a clue as to what is happening. Earlier, we
mentioned that inline styles are very powerful and that they are
extremely specific.

They will override any other styles that target the same element in an
internal style or an external style sheet. To make the change appear in
the page, we need to remove the specific styling that is overriding our
style that we have just written. So, I\'m going to select the entire
style attribute in the h1 element and hit Delete. Then we save our index
file, go back to the browser preview and hit Refresh. We\'re now able to
see the color of the *h1* change to Fire Brick Red:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image50.jpg){width="4.398956692913385in"
height="2.0887095363079613in"}

The next thing that we will do is to make the background in the body
white, but we still want the header area to have a background color of
orange. So first, let\'s go back to our HTML file, and, we\'re going to
delete the inline style in the body tag. Simply highlight the style
attribute and delete it.

Next go back to the style tag inside the head element and this time we
want to make the header element have a background color of orange. To do
that, we will simply target the header element by using header, and then
we're going to specify that we want to change the background color
property by writing *background-color* followed by a colon and then give
it the value *orange* like so:

\<**style**\>

p {

font-size: 20px;

font-weight: bold;

}

h1 {

font-size: 90px;

color: firebrick;

}

header {

background-color: orange;

}

\</**style**\>

As usual we will save the file and then preview the changes in the
browser by clicking the refresh button:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image51.jpg){width="5.763888888888889in"
height="1.4152777777777779in"}

We can see that the body background is back to the default color of
white, while the header maintains that orange background color. The
internal style sheet method we just used is useful if we\'re creating a
small-scale site, something that has a few pages at max, or for
temporary use.

Similar to inline styles, the internal styles are not recommended to be
used for building websites. When using internal stylesheets on larger
projects, it means that the browser will have to download the styles
multiple times for each page. Also, we will be duplicating code across
tens or even hundreds of web pages and this defeats the real purpose of
CSS.

External Stylesheets 
---------------------

So, you're probably asking what is the best practice way of adding CSS
styles to a web page? The simple answer is using external style sheets,
and we will now look at how to add an external stylesheet to our landing
page. One of the great advantages of using an external style sheet is
that we can change the look of an entire site using just one style
sheet.

The first thing that we need to do is to create a style sheet file. Open
the *2-external-style-sheets* folder inside the *Getting started*
directory. Then double click on the *start* folder. Here you will see an
*index.html* file and a *CSS* folder. Open the *CSS* folder and create
*a style.css* file.

You will notice that there is already another file inside the CSS
folder. We will be using this CSS file very soon to see how we can
import other CSS files. The *.css* extension is what tells the browser
that the file is a stylesheet. So, make sure you always add that *.css*
extension to every stylesheet you create. Otherwise the browser won't be
able to apply your styles.

Now that we have created the style sheet, we need to link it to our web
page, and whilst we are at this point, it is worth mentioning that one
of the common errors that is made is to forget to link the style sheet
to the webpage. So, without further ado, let's do that right now.

We can add the link to the style sheet that we have just created using
HTML\'s link element. We need to add the link to our CSS file in between
the head tags. So, we\'ll go over to the head section of our HTML file
and, right beneath the title tag, we\'ll create a link tag. The
following is the syntax for linking our style sheet to the web page:

\<**head**\>

\<**title**\>Granada\</**title**\>

\<**link** rel=\"stylesheet\" href=\"css/style.css\" /\>

\</**head**\>

At the very least, we\'ll need to add two attributes to this link tag in
order for our CSS file to link correctly. The first attribute that we
need to include is the relationship attribute, shortened to *rel*. This
attribute specifies the relationship between the current HTML document
and the document that we are about to link. Since the document is a
stylesheet, the value needs to be set to *stylesheet*.

It's important to note that if the *rel* value is misspelled, the
browser will not link to the stylesheet, so make sure that it always
reads *stylesheet*. After the *rel* attribute, we need to add a *href*
attribute and the *href* attribute is what points to the location of the
CSS file. We know that the new CSS file is inside the folder named
*CSS*.

So, we need to write the path to the CSS file as *css/style.css*. Now we
can save our *index.html* file, and go over to our new *style.css* file
where we\'ll write a few styles for some of our elements.

Our file should be linked to our landing page, and we can now start
applying styles using the external stylesheet that we have created.
First, let\'s style the *body* of the page by aligning the text to the
center and changing the font size of the *h1* element and give it a
color of white:

body {

text-align: center;

}

h1 {

font-size: 72px;

color: white;

}

Next, let\'s give our header an orange background color:

header {

background-color: orange;

}

And finally, let\'s add styles to our paragraph and make a font size of
*20* pixels:

p {

font-size: 20px;

}

Don\'t worry if you\'re not sure what these styles mean right now, we'll
cover everything in detail very soon. The important thing here is that
you understand the concept of separating content from presentation.

Let's save the stylesheet, and before going to the browser and
refreshing, we need to remove the internal styles from the *index.html*
page. So, go into the *index.html* file and remove all the styling from
the opening style tag to the closing tag itself and delete. Then save
the file and preview the changes in the browser by clicking refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image52.jpg){width="5.0in"
height="1.0427712160979878in"}

We can see how the external stylesheet affects the page. So, compared to
the previous methods we used to add CSS, the advantage to using this
external stylesheet method is flexibility. We may have multiple HTML
files linked to the stylesheet, but as long as we keep our CSS in a
separate file, any styling changes or additions we need to make are done
in one file. Another advantage is that the browser often caches the
stylesheet after the first request, which saves on download time
throughout the site for repeat visits.

Are you wondering why we write CSS or link to stylesheets from the head
section of the HTML document? This is so we load the CSS before the HTML
markup. Also, it\'s standard practice to link to stylesheets from the
head of the document. That way, the browser loads and parses the
stylesheet first, before any of the body elements. This means that when
our website is up on a web server and a user visits our site, the HTML
is nicely styled right before it\'s presented to the user.

Importing stylesheet with \@import
----------------------------------

The final method of adding CSS to our web pages is using a CSS import
statement. The \@import statement lets us import CSS from other
stylesheets. It shares some of the same advantages as linking a style
sheet, like browser caching and maintenance efficiency.

Adding a CSS file using the \@import is straightforward. First let's go
back to the head section of our *index.html* page. Then right underneath
the link tag let\'s create a new style tag like we did earlier -- this
is how our head section should look like:

\<**head**\>

\<**title**\>Granada\</title\>

\<**link** rel=\"stylesheet\" href=\"css/style.css\"\>

**\<style\>**

**\</style\>**

\</**head**\>

Then inside the style, write \@import followed by a set of quotes and a
semicolon and inside the set of quotes, we\'ll specify the path to the
CSS file we want to import. In the CSS folder, we should see a file
named *import-styles.css*, which contains a simple layout background and
color styles. Go ahead and specify the path to that CSS file by writing
*css/import-styles.css*. Here's how the import statement looks like
inside the style tags:

\<**style**\>

**\@import \"css/import-styles.css\"; **

\</**style**\>

There is quite a bit of styling already inside this file, but don't
worry about these for now, we will go over them in detail later on.
Let's save our index.html file and then switch to the browser and
refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image53.jpg){width="4.379032152230971in"
height="2.6886187664041996in"}

We now see how the page has imported the styles from *import-styles.css*
and the styles have been applied to our landing page.

We can also import a style sheet from within a style sheet. To see this
in action, we need to first remove the import statement from our
*index.html file*. Select the import statement between the style tags
and cut it, then delete the style tags since we no longer need them.
Then save the index.html file and open up the *style.css* file and here,
we can paste the import statement at the very top of our style sheet.

For the import statement to work, it must precede all other CSS styles
in a style sheet. So, remember to always keep the import statement at
the beginning of the style sheet before applying any styles.

Because our *style.css* file is already inside the CSS directory, we
don\'t need to include the directory name in our path. So, we can remove
the *css/* part and we\'ll just keep the file name inside the quotation
marks. So, you should have the following at the very top in your
style.css file:

**\@import \"import-styles.css\"; **

body {

text-align: center;

}

...

When we save our style sheet and refresh the browser preview, you will
notice that nothing has changed. This is because we\'re still importing
the same CSS file. The only difference is that we\'re importing it from
our style sheet instead of our HTML file as we were doing earlier.

So, this import method lets us separate our CSS into as many separate
files as we want. So, while the page may link to one main style sheet,
the style sheet can import other style sheets for base styles layout,
typography and so forth. There is a drawback, however, which is site
speed and performance. Each import statement requires a new request to
the server. So, if we have too many, they can be expensive in terms of
load time. In the next chapter, we\'ll learn the different ways we\'re
able to target HTML elements and apply styles to them with CSS
selectors.

 CSS resources 
--------------

I can understand you might be feeling a little bit overwhelmed with all
the styles that we just went through and how I was able to know which
selectors I needed to use to style the different parts of our landing
page. You might be asking yourself: "*are we expected to memorize every
CSS selector, property and value out there?*"

Well, I'm going to let you in on a secret! Web Developers don't memorize
the CSS styles that they need to use to style web pages. In fact, nobody
expects you to memorize every CSS selector, property and value. Pretty
much all web developers get stuck at working with HTML & CSS, and this
is why documentation is a developer's best friend.

Documentation is an integral part of the development process in software
engineering and CSS is no exception. It has a very well documented
specification covering practically every aspect that you will need when
using CSS.

So, before we continue writing CSS, I would like to quickly cover
helpful resources that will always have the most important and up to
date information you\'ll need on a given CSS topic.

One of best resources for CSS is the: [Mozilla Developer Network
Doc](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) link:
<https://goo.gl/n0DQ4R>, or, MDN Docs:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image54.jpg){width="4.5in"
height="2.9130719597550305in"}

It has an extensive list of all the standard CSS properties, selectors,
and CSS concepts in alphabetical order, and it gives us detailed
information for each of them. So, for example, if you're stuck on how to
style a link when the user hovers over it.

You can find hover from the list of topics, and then you're presented
with a summary on the hover selectors. One of the great things about the
MDN Doc is that there\'s even a browser compatibility chart at the
bottom of the page, which shows what browsers support each of the
properties and which ones don't:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image55.jpg){width="5.114194006999125in"
height="2.1491940069991253in"}

So, it\'s a handy reference you should keep close by when building
websites with CSS. If you\'re looking for really specific information
about CSS, you can read the actual specs from the [World Wide Web
Consortium](https://www.w3.org/) link: <https://goo.gl/O437Zm>, or, WC3
for short.

The W3C is the group that develops and maintains web standards. All the
standard CSS features we use today were written up in a specification,
and approved by the WC3.

One of the most important parts about building for the web is keeping up
with browser support. One of the best sources to check whether a browser
supports a certain CSS feature is *caniuse.com*. It provides up to date
browser support information for all the front-end web technologies on
desktop and mobile web browsers.

When learning web development, it\'s important to have good
self-initiative. This means being able to find answers on your own,
working on small projects that will help you retain what you\'re
learning, and knowing when and how to ask for help when you\'re stuck.
Self-initiative is one of the most valuable assets a web developer can
have.

The single important thing that you need to take away from this is that
you don't need to memorize every selector, property, or, CSS value
available. A solid understanding of the concepts, and a reliable
reference, combined with patience and an energetic self-initiative will
make you a solid web developer.

**\
**

Day Four 
=========

Basic selectors 
----------------

### Intro to selectors 

In the previous section, we dived straight into CSS without actually
discussing the way in which the CSS syntax works in detail, as we wanted
to learn how we can add CSS to our web page. In this section, we will be
learning the different ways we can define a CSS selector.

Selectors can be defined based on an element\'s type, its class or, ID
attribute, even how we interact with the element and more. But before we
get into how CSS selectors work, let\'s first talk about what makes up a
CSS rule.

CSS rules or rule sets, tell browsers how to render HTML elements. A CSS
rule is made up of two main parts, as you've already seen: the selector
followed by the declaration block:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image56.jpg){width="4.887096456692913in"
height="2.0702449693788276in"}

The selector is the part of the CSS rule that targets HTML elements.
It\'s what actually lets us select the content we want to style. Now,
after the selector comes the declaration block, which begins with a left
curly brace and ends with a right curly brace. Inside those curly braces
is where we write the declarations that style the element we\'re
selecting. Each declaration consists of a property name and a value,
separated by a colon.

The property is what indicates the part of the element we want to
change, and the value describes how it\'s changed. As you\'ll learn, we
can write as many declarations as we want, as long as we separate each
one with a semicolon. Now that we\'re familiar with the syntax of a CSS
rule, let\'s get started with basic type selectors. Then we\'ll get more
specific as we go. Selectors are one of the most important and powerful
parts of CSS.

We can think of selectors as patterns that allow us to target HTML
elements and apply styles to them. When we define a selector in our
style sheet, we\'re instructing the browser to match every instance of
that selector in the HTML. We\'ve actually already written a few CSS
selectors in the previous section when we added CSS to our page.

In our exercise files for this section (which can be found in the
*2-basic-selectors* folder then open *1-intro-to-selectors*), we have
our style sheet ready to go, and it\'s already linked to our HTML file,
which now contains the rest of the content we\'ll need in our Granada
landing page website. If you open the *index.html* file in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image57.jpg){width="4.681451224846894in"
height="2.6921161417322836in"}

As we can see, the page is once again completely un-styled in the
browser. So, let\'s open the text editor, and open up *our style.css*
file. You will find the file inside the exercise files folder \> CSS
section \> Basic Selectors and there you will find two folders, one
named *start* and the other *final*. Open the start folder and then open
the *index.html* and the CSS file inside the CSS folder.

Let\'s start writing some styles with CSS selectors. The very first
selector we\'ll cover is called the universal selector, and it\'s called
a universal selector because it selects every element on the page at
once and applies the styles we set. It\'s a very powerful selector
because it overrides all other selectors, as we\'ll soon find out. So,
to create a universal selector, we use an asterisk as our selector,
followed by the declaration block:

\* {

}

Inside these curly braces is where we\'ll write the styles we\'d like to
apply universally to our page. Let\'s write our first declaration.
We\'re going to use the margin property and we'll set it to zero, we're
also going to set the padding of each element in our web page to 0, and
finally we'll add a color property and set that to red to really make
things stand out. Here's how our CSS code should look like:

**\*** {

margin: 0;

padding: 0;

color: red;

}

This universal selector we just wrote will apply these styles to every
element in our project. So, let\'s take a look at the results. First
save the stylesheet and then refresh the page in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image58.jpg){width="5.022588582677165in"
height="2.504032152230971in"}

As we can see, the browser has removed all of the padding and margin
that the user agent styling applied. The universal selector is a very
powerful selector, and we\'ll need to be careful with how we use it. For
now, we\'ll go ahead and, remove the universal selector rule from our
style sheet. Switch back to the text editor and remove the universal
styling declaration and save your style sheet.

### Type selectors 

Next we're going to look at type selectors. A type selector is what we
use to select an element type on the page. They\'re also called element
selectors, because we only use the element\'s HTML tag as the selector.
If you recall, we've already been using some of these selectors when we
styled the *body* element, the *header*, and the *h1* element.

If we wanted to target every paragraph element in our HTML file, we need
to use the *p* element as our selector. To apply the styles, I'm going
to type *p*, followed by a set of curly braces, and, as our first
declaration, we will write the color property followed by a colon and
set it to *white*. Below that, we\'re going to type background-color and
we'll set its value to *lightblue*:

p {

color: white;

background-color: lightblue;

}

So, if we save our style sheet and refresh our preview:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image59.jpg){width="4.207786526684164in"
height="3.75in"}

We can see how the selector targets every paragraph on the page and
applies the styles we defined. Like we did previously, if we want to
target the header element and change its background color, we can target
the header element by writing *header* as our selector. Let's make the
header\'s background orange:

header {

background-color: orange;

}

Let's save the stylesheet and refresh our view in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image60.jpg){width="4.2461537620297465in"
height="3.9218088363954506in"}

Each set of tags represents an element on the page and we\'re able to
use any of the HTML tags as selectors in our CSS. Type selectors are
good for describing what elements look like by default. We're going to
use type selectors to begin defining the default styling for how some
our elements will appear in our Granada landing page. In our stylesheet,
I\'m going to remove the paragraph rule we just wrote, as this was just
an example, however, we\'ll keep the header rule with the orange
background color.

Next, we're going to style the *h1* element on our page. Right below the
header rule, I'm going to add a style that will make the font size
bigger by setting it to 90 pixels and we'll set the color to white:

h1 {

font-size: 90px;

color: white;

}

Then below our *h1* rule, we\'ll use another type selector to target the
*h2* elements on the page. I'm going to set the *h2* font-size to 53
pixels.

h2 {

font-size: 53px;

}

Then right below our *h2* rule, I'm going to target the *h3* headings on
the page and set their font-sizes to 20 pixels. I will also add a color
property value to the *h3* style to make it a lighter shade of black.
For this, I will use a hexadecimal as the value for the color property:

h3 {

font-size: 20px;

color: \#48525c;

}

When using hexadecimal values, you need to prepend a pound (or hash)
symbol in front of the value as you can see in the above style rule.
Finally, I'm also going to style the body of the page by targeting the
*body* element. Since the *body* element comes right at the top of the
page, I'm going to place this rule right at the top of the stylesheet.
This is just a matter of preference, to keep things nicely grouped and
organized in reference to our HTML document. I'm going to set the *body*
color to gray, and again for this, I will make use of another
hexadecimal value and add a margin with a value of 0:

body {

color: \#878787;

margin: 0;

}

What the above style does is set the universal color of the text for all
elements on the page to a nice shade of gray. Let\'s go ahead and save
our style sheet, and then switch over to our browser preview:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image61.jpg){width="4.220261373578302in"
height="4.625in"}

The *body*, *header* and heading type selectors we just wrote, match
their respective elements on the page, and they\'re now styled with
those properties we defined. Using selectors to apply styles to our page
is a straight forward process. Next, we\'ll see how we\'re able to make
our selectors more specific using ids as the selector.

### ID selectors 

ID Selectors, unlike a type selector, which targets every element with a
corresponding element type, lets us assign a unique ID to an element.
That way, we\'re able to specifically target an element based on its ID
attribute. ID selectors are declared using the pound (or hash) symbol
followed by the ID name. So, in our *style.css* file right below the
type selectors we wrote previously, let\'s declare an ID selector by
writing the pound symbol followed by the ID name. I'm going to call it
primary-content:

\#primary-content {

}

Then we\'ll follow the selector with our declaration block. I'm going to
create a border around the primary content by giving it a border size of
2px, a solid border and a color of red:

\#primary-content {

border: 2px solid red;

}

This ID selector we just wrote will match the html element that has an
ID attribute with the value primary-content. So, if we save our style
sheet and switch to the browser preview, when we refresh the page we
don\'t see that red border anywhere on the page just yet:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image62.jpg){width="3.9829724409448817in"
height="4.392307524059492in"}

As you start out creating web pages with CSS you often find yourself in
situations like this, this is perfectly normal. The reason the border is
not showing is because we still need to assign the ID of
*primary-content* to an HTML element. So. let\'s go over to our
*index.html* file and we\'re going to give the first div element the ID
of *primary-content*. It should be on around line 12. We'll add an ID
attribute, then inside the quotation marks, we\'re going to write
primary-content:

\<div id=\"primary-content\"\>

The ID names are up to us, but it\'s usually good practice to give them
meaningful names that explain what they do, and what their purpose is.
This div contains the main content on the page and we are giving it the
ID name *primary-content*, which indicates that very clearly. Let's save
our index.html file and take a look at it again in the browser preview
and refresh the screen:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image63.jpg){width="4.8711537620297465in"
height="1.7688746719160104in"}

As you can see from the screenshot, there\'s a red border around the
primary content div element on the page. IDs are unique to the page so
it\'s important to remember that an element can only have one ID and a
page can only have one element with the same ID name.

Also, because our div already has an ID applied, we can no longer add
IDs to it and we cannot use this *primary-content* ID anywhere else in
this particular HTML file. IDs also have a browser functionality,
meaning that they can be used as what are called fragment identifiers
for creating landmarks or anchors in pages as we have seen when we were
creating HTML link tags. In the footer element, let's give the footer an
ID of *main-footer*. So, in the opening footer tag, we\'re going to add
an ID attribute, and we\'re going to make the id value *main-footer*.

\<footer id=\"main-footer\"\>

Make sure to save the *index.html* file, and then switch over to our
style sheet. We\'ll target the main footer element with an ID selector,
right below the *primary-content* selector we wrote earlier. First
we\'re going to give it a *padding-top* with a value of 60 pixels and a
*padding-bottom* also with a value of 60 pixels. Finally, we're going to
give the footer a border on the bottom only, which will be 10 pixels and
the color orange:

\#main-footer {

padding-top: 60px;

padding-bottom: 60px;

border-bottom: solid 10px orange;

}

Let's now save our stylesheet and then switch over to the browser view
and click on refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image64.jpg){width="5.121875546806649in"
height="2.0in"}

We've given our footer the same top and bottom padding to give this
footer text some breathing room. As you can see with IDs, we\'re
specifically telling the browser to target a unique element on the page.
But what if we need to target more than one element with these selectors
while still maintaining some form of specificity? Well, that\'s where
class selectors are really useful and we\'re going to cover those next.

### Class selectors 

Class selectors let us target elements based on their class attribute.
The main difference between a class and an ID selector is that IDs are
unique. They\'re used to identify one element on the page, whereas a
class can be used to classify and target more than one element. This
makes classes more flexible than IDs as you will soon see. Class
selectors are defined with the dot character followed by the class name.
Let\'s see what happens when we change this primary content ID selector
to a class selector. To do that, we\'ll replace the pound (or hash) sign
with a dot:

.primary-content {

border: 2px solid red;

}

So now our selector is a class and if we save our style sheet and take a
look at it in the browser preview, we can see that the red border is no
longer there:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image65.jpg){width="4.6211537620297465in"
height="2.7097779965004376in"}

That's because class selectors only target elements with a matching
class attribute. So, we\'ll need to go back to our HTML file and change
the ID attribute to a class instead on around line 12:

\<div class=\"primary-content\"\>

Classes let us target more than one element with the same class name. In
fact, that\'s one of the biggest advantages to using class selectors.
Multiple elements can share the same class and we're able to reuse them
throughout a page. Remember, we\'re not allowed to do that with IDs. Now
if we save the index.html file and refresh the browser, we should now
see the red border again around the primary content div:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image66.jpg){width="5.224622703412074in"
height="2.375in"}

So, if we give another element in our HTML file the class primary
content, we should also see the red border applied to that element.
Let's give the next div on around line 27 the same primary content
class:

\<div *class*=\"primary-content\"\>

\<h3\>Location and Distances\</h3\>

When we save our *index.html* file and refresh the page, we see that
both divs now have that red border applied:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image67.jpg){width="4.903114610673666in"
height="3.5692311898512687in"}

Like with IDs, naming the class is up to us and we should also give them
meaningful names that explain their purpose. So, let\'s go back to our
HTML file and add a few more class attributes.

But first, instead of giving the div on line 27 the class primary
content in the *index.html* file, let\'s rename it to secondary content
because that\'s what it actually contains:

\<div class=\"secondary-content\"\>

Next, let\'s scroll up and give our header element the class main
header. We could just continue using the header type selector we wrote
earlier to target the *header* element, but let\'s instead give it the
class name *main-header,* because again we\'ll want to give it a
meaningful class name. We know that this will always be the main header
on our page or website, as this main header class communicates that very
clearly.

\<header class=\"main-header\"\>

So, let\'s save our *index.html* file and go back to our style sheet,
and target these new classes. First, we\'re going to change the header
type selector to match that main header class. So, scroll up to where we
declared our header, it should be on around line 6. Then replace the
word *header* with a dot and *main-header*:

.main-header {

background-color: orange;

}

So, if we save our style sheet and take a look at it once again in the
browser preview, we can see that nothing really changes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image68.jpg){width="5.763888888888889in"
height="1.1611111111111112in"}

The header styles are still the same. We\'re just targeting with a class
selector instead of using a type selector. Next, let's remove that red
border around the primary content div, as it\'s not part of our actual
site design. Make sure that you are on the styles for the primary
content class, which should be on around line 24 and instead of the red
border, we're going to center align all of the text.

To do that, we can write text-align and set the value to center:

.primary-content {

text-align: center;

}

So, now when we save our CSS file and take a look at it in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image69.jpg){width="5.763888888888889in"
height="2.4458333333333333in"}

We can see how that center aligns our text nicely inside that primary
content div. Let\'s also target that secondary content class we wrote
earlier by adding a nice border around it. So, in our style sheet, right
below the primary content rule, we\'re going to create a style rule for
the secondary content div by writing a dot followed by
secondary-content. Then we\'re going to add a border top style
declaration. We're going to make a smooth gray color:

.secondary-content {

border-top: 2px solid lightgray;

}

Now even though we don\'t know exactly what this declaration does, just
yet, you can probably tell what\'s about to happen here. Many CSS
declarations like this can be understood at first glance. If you think
this class selector is going to give the secondary content div a solid
lightgray top border, then you\'re on the right track! So, let\'s take a
look. We\'ll save our *style.css* file and when we refresh the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image70.jpg){width="4.3711537620297465in"
height="2.1776771653543308in"}

That\'s exactly what happens. There\'s that light gray solid border
applied to our secondary content element.

###  Reusing classes 

When we looked at class selectors, we learned that we could reuse
classes to target more than one element with a style. In addition to
reusing classes on more than one element, we can also add multiple
classes to a single element. To understand when we might need to do
this, let's look at a practical use case for adding multiple classes to
a single element.

One great use case for adding multiple classes to an element is when we
have lots of repeated CSS code in our style sheets. In a situation like
this, it's best to create a separate class for repeated styles, that way
you can add the class to any element that you wish to apply a particular
styling on. For example, let's say that our primary content and the
footer element need to have the same top border style as the secondary
content element.

In order to add the same styles to these elements, we can repeat the
styling for the border top property two more times in our style sheet,
first by adding it to the primary content element and the footer
element. But this will mean that we have repeated the same style rule in
multiple places. Instead of repeating the styles, we can create a
separate class, let's call it *t-border*, and simply add the styling
rule in this class:

.t-border {

border-top: 2px solid lightgray;

}

Then all we have to do is save our stylesheet and then in our HTML file,
we can add the t-border class to the primary and content div as well as
the footer. To add the class to the primary content div, we simply add a
space right after the primary-content value and then we'll write
*t-border* -- make sure there is a space between the classes like this:

\<div class=\"primary-content t-border\"\>

We then repeat this process for the secondary content div:

\<div class=\"secondary-content t-border\"\>

Finally, we also need to add the class to the footer element, but you
will notice that the footer does not have a class attribute, so we need
to first add the class attribute and then make the value *t-border*:

\<footer class=\"t-border\" id=\"main-footer\"\>

Now that we've added the classes to the elements, let's save our
*index.html* file and then switch over to the browser and then hit the
refresh button:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image71.jpg){width="4.585472440944882in"
height="3.875in"}

We can see that the border style has been applied to all three elements.
Adding multiple classes to elements helps make our CSS more
maintainable, especially when the site is very large because it means
that we are not unnecessarily repeating styling code in our style sheet.
Also, if we wanted to change the border color for all the elements from
light gray to blue for example, all we have to do is change it in one
place as opposed to changing it in three places.

### Descendant selectors 

You can target elements in your HTML based on their relationship. We can
combine selectors to create descendent selectors. Descendent selectors
target an element that's a descendent of another element and this makes
our selectors more specific. If you look at our *index.html* file
carefully, you will notice that we have a span element nested inside the
header element. This makes the span element a descendent of the header
element, and this means that we can target the span element using a
descendent selector.

To create a descendent selector, we need to use two or more selectors
separated by white space. Let's add the descendent selector to target
the span element in our stylesheet, so below the main header rule we'll
write header followed by a space and then the span element selector.
We'll make the color white and give it a larger font size:

header span {

color: white;

font-size: 26px;

}

Now, let's save our stylesheet and preview the changes in the browser by
clicking refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image72.jpg){width="4.937403762029747in"
height="1.4193547681539807in"}

You will notice that the styles we added to the descendent selector are
applied to the span element inside the header. The great thing about
descendent selectors is that they are not limited to type selectors. We
can also create descendent selectors with classes and IDs and this lets
us get very specific. So instead of using the header element in the
descendent selector, we can also use the class name on the header
element, which is *main-header*. So, once we swap the header for the
class name, this is how the style rule should look like:

.main-header span {

color: white;

font-size: 26px;

}

When you save and refresh the web page, you will notice that this works
exactly the same way as before. However, this descendent selector is a
lot more specific. In other words, we're telling the browser to apply
these styles to a span element only if it's a descendent of an element
with the class main-header.

Descendent selectors can also be used to style lists. We can target the
list items in our page for the locations. Let's go back into our
stylesheet and beneath the descendent selector that we have already
created, we'll target the ul element followed by a space, and then the
list item element selector:

ul li {

background-color: tomato;

}

The above descendent selector targets every unordered list element on
our page and gives it a background color of tomato. Save your changes in
the stylesheet then head over to the browser and refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image73.jpg){width="4.84161854768154in"
height="2.5923075240594926in"}

We have targeted all the list items on our page and the background for
each item has been set to tomato. Descendent selectors behave in the
same way as ID selectors, which means that they are specific. This means
that we need to be careful in how we use them in our stylesheets and
using too many selectors will make our CSS rules less reusable. Let's
say that we wanted to add another span element inside of the header
element. This means that it will take on the styles being applied to the
current span element, even if we didn't want it take on this styling.

Descendent selectors have their use cases and can come in very handy,
but for most situations, we're better off with using classes. With that,
let's add a class to the span element inside the header in our
*index.html* file called *title*:

\<span class=\"title\"\>Visit the ancient and beautiful city of
Granada\</span\>

Then inside our stylesheet, we'll replace the descendent selector with
our class:

.title {

color: white;

font-size: 26px;

}

This works exactly the same way as before, only this time we are using a
class to target the span instead of a descendent selector.

### Pseudo classes 

Pseudo-classes can be difficult to understand at first as they are not
explicitly defined in an elements class attribute, and they also don't
appear in the source code like classes do. However, pseudo classes are
similar to classes and they can target elements dynamically based on
user interaction, an elements state and more. You can think of Pseudo
classes to be like a keyword that we can add to a selector that will
enable us to style a special state of an element on a webpage, for
example, we can add styling to a button only when a user hovers over it
with the mouse cursor. The following screenshot shows a list of all the
standard pseudo-classes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image74.jpg){width="4.310483377077865in"
height="4.977830271216098in"}

As you can see, there are quite a few pseudo-classes that we can apply
to elements. We're not going to cover every single pseudo-class, but we
will cover a few of them and this will give us the understanding and the
practical know how that will enable us to use any pseudo-class in the
future. The first pseudo-class that we will learn about is the most
commonly used pseudo class and that is the link history pseudo-class.

The link history pseudo-class allows us to style links based on whether
or not they've been clicked on. There are two different classes that we
can use. The first one is the link pseudo class and it enables us to
apply styling to links that have not been visited, in other words, links
that have not been clicked by the user. Since links are created using
the anchor element \<a\>, then this is the element to which we need to
add a pseudo class. We already have links on our page, so we can go
ahead and style the link pseudo class on the anchor element. After the
last style rule in the stylesheet, I will add the styling for the
un-visited pseudo class:

a:link {

color: orange;

}

In the above style rule, we are giving all the un-visited links on our
web page the color orange. So, if we save the style sheet and go back to
the browser view and refresh, we can see that all of our links now have
the color orange instead of red:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image75.jpg){width="4.650474628171478in"
height="1.3480774278215224in"}

It's important to note that the link pseudo-class only works on anchor
elements that have a *href* attribute, so if an anchor element does not
have the href attribute, then the styles will not be applied. You will
notice that when we click on any of the links and go back to the page,
you will see that the color of the clicked link takes on the default
browser style of purple:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image76.jpg){width="4.6211537620297465in"
height="1.0762281277340333in"}

We can also change this color to anything that we want using the visited
pseudo class of the anchor element. We will add the visited pseudo class
beneath the link pseudo class and we'll set the visited link color to
lightblue:

a:visited {

color: lightblue;

}

We apply the pseudo class in pretty much the same way as before, only
this time we are adding the pseudo class visited and applying the color
lightblue for visited links. Now when you click on any of the links, it
immediately takes on the style that we specified:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image77.jpg){width="4.750866141732283in"
height="1.0692311898512685in"}

### Hover pseudo class 

As you saw from the MDN documentation page, we have a lot of pseudo
classes at our disposal to use for styling our web pages. Another pseudo
class that is very commonly used is the hover pseudo class. The hover
pseudo class is considered a user action pseudo class, because the
styles are applied based on the user's interaction with the element.

To see it in action, let's add the hover pseudo class to our links. We
will add the hover pseudo class right beneath the visited pseudo class
style rule. We add the pseudo class in the same way that we did for the
link and visited pseudo classes and only change the pseudo class name:

a:hover {

background-color: forestgreen;

color: white;

}

So, whenever the user hovers over any link on our web page, it will give
the link element a background color of forest green and a color of
white. To see how this looks, save the stylesheet then switch to the
browser, refresh the page and make sure to hover over a link:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image78.jpg){width="3.803846237970254in"
height="1.8472353455818022in"}

As you can see from the image above, whenever we hover over a link
element, it will apply a background color of forest green and a color of
white for the text. What's interesting about the hover pseudo class is
that you can apply it to any element that you wish. To see how this
works, we can change the anchor element tag to a *p* tag like so:

p:hover {

background-color: forestgreen;

color: white;

}

So now if we save the changes in our stylesheet and switch back to the
browser and do exactly what we did before with the anchor element:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image79.jpg){width="4.8711537620297465in"
height="1.2189621609798775in"}

The hover pseudo class is now being applied to all the paragraph
elements on hover. The hover pseudo class is really useful when you want
to apply a particular styling to an element when they hover their mouse
over it. Make sure to change the element back to the *a* tag again
before moving on.

**\
**

### CSS comments 

In HTML, we saw how we can insert comments into our markup, and we can
do the same in CSS to add explanatory notes. In the same way, the
browser doesn't interpret the comments as markup, it will also ignore
any comments that it finds in our style sheet. Comments in CSS begin
with a forward slash and an asterisk, and end with an asterisk and a
forward slash. The browser ignores anything that is in-between the
opening and closing characters.

Comments are useful for including helpful notes and hints that let
others know what's going on in our code. Comments also help us when we
come back to our code some time in the future. We can add comments
anywhere in our CSS stylesheet. Let's add some comments to the pseudo
classes that we added to the anchor element:

/\*Styling to add pseudo class for unvisited links\*/

a:link {

color: orange;

}

/\*Changes the visited links color to lightblue\*/

a:visited {

color: lightblue;

}

/\*Hover styles for links\*/

a:hover {

background-color: forestgreen;

color: white;

}

It's worth keeping in mind that if you leave out a forward slash, all of
the following styles below will be commented out until you add another
forward slash. So ,make sure all comments slashes match up. Also, if you
are using a code editor like Atom or Sublime, then you can use the
keyboard shortcuts provided to add comments to your style sheet. For
example, you can highlight the text that you want to comment out then
simply hold the command key followed by a forward slash for MAC users
and the Ctrl key followed by the forward slash for Windows users. **\
**

Day Five 
=========

Understanding values and units 
-------------------------------

### Common data types 

As you have already seen, every CSS property has a set of values that it
can accept. When specifying the color property, we can use keywords that
describe the value. A value can also be described as a number, a length,
an image or a URL. These values are categorized into data types and we
have lots to choose from. As I mentioned before, you don't have to
memorize every CSS data type value, we just need a good reference. One
of the great references for CSS is provided by the Mozilla Developer
Network or MDN docs.

A data type is essentially a CSS value for a given property. So far we
have used CSS selectors and some values, and we saw how they affected
certain elements on the page. One of the most common data types are the
color data type for color values. So far, we have used the values
orange, light blue and forest green; these are all considered color data
types. They are some of the predefined color key words.

We can use color values for background color properties, color
properties, border colors, shadows and a few others. Other data types
include integers, numbers, and percentages. We can use any positive or
negative integer, number, or percentage values for certain CSS
properties. Integer and number values are mostly used when defining
values for length property.

For length values, we can use units like pixels, ems, or rems to specify
a unit of measurement for a number value. Don't worry, we'll cover these
length units in detail very soon. But if you look back at some of the
styles we already have in our stylesheet, you will see that we are
already using these values such as the 90-pixel value for the font size
on the *h1* element.

Now that we have a brief understanding of the data types for different
CSS properties, we can look at some of them in more detail. However, I
would like to emphasize the importance of the CSS reference
documentation provided by MDN. Whenever you want to find out what data
types a certain CSS property accepts, just refer to the CSS reference
for that property and you will get a detailed breakdown of all the
values that it accepts. Here is a link to the CSS MDN reference
documentation: <https://goo.gl/rhmZyl>

### Pixel units 

Usually when defining a number value, we need to specify a length or
unit of measurement for that value. If we don\'t, the browser will
likely not know what to do with that number value. CSS offers different
units for expressing length. Some length units are more flexible than
others. For example, relative units and percentage units are always
relative to other length values, which makes it easier for developers to
layout content independently of screen size and resolution.

Absolute units, on the other hand, like pixels, are always fixed in
relation to each other. They don't scale like relative units do. Many
CSS properties take length or percentage values for font-size, padding,
margin, widths and more. When defining values for length properties,
there are several different unit types we can use. As we mentioned
already, there are relative length units and absolute length units.

There are six absolute units in CSS, but the most commonly used one is
the pixel unit. We've already used this pixel unit when specifying font
size. When we use pixels, the size we define will always be the same and
will not scale regardless of the browser window and size of the screen.

To demonstrate how this is in practice, let's go back to our stylesheet
and find where we create the style for the main header in the class
called *main-header*. Let's add a style rule that sets the width of the
header to 960 pixels wide:

.main-header {

background-color: orange;

width: 960px;

}

With this pixel value, the header will always take up 960 pixels of the
screen. Let's save our stylesheet and go back to the browser and refresh
the page to view how this looks:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image80.jpg){width="5.576131889763779in"
height="0.9788462379702537in"}

As you can see from the screenshot, the header no longer takes up the
full browser width, only 960 pixels. The same is true for any CSS
property with a fixed pixel value including our headings, the pixel
based border values or any other value defined with a pixel unit. Values
defined with pixel units will always remain a fixed size in relation to
each other. Pixels in web design are common, since they allow the
developer to size and position elements precisely on a page.

### Percentages 

Percentages can be used to define values more fluidly, because
percentages by nature are always relative to something else. When
percentage units are used as values in CSS, the percentage value is
measured relative to a parent element's length. This means that it will
adjust based on the parent element's length. Many properties like width,
margin, and padding use percentages and they are commonly used for
layout since they allow fluid sizing of elements relative to their
container.

For our header in the web page, we used a value of 960 pixels. Let's
change this to a percentage instead and change it to 50%. To do this in
our code, we simply change the value for the width to 50%:

.main-header {

background-color: orange;

width: 50%;

}

When we save this and view the result in the browser, you will notice
that our header is only taking up half of the width of the page --
regardless if we resize the window or not, it will always take up half
the width:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image81.jpg){width="5.0635017497812775in"
height="0.8461537620297462in"}

Obviously, the header needs to take the entire available width of the
window, since it is acting as our header for the page. So, I will change
the width to 100% and this will make the header fill the entire
available width space in the window. This also means that it will adjust
to take up whatever width space is available. Even if we resize the
browser window width, it will always take up the full width of the page.

Next, I would like to set a percentage width for the width of the
primary and secondary content divs. At the moment, the content is a
little difficult to read since it's so wide. In CSS, we can group
multiple selectors and style them with just one rule. To do this, I am
going to group the class names: *primary-content* and
*secondary-content* and separate them with a comma, then apply

a single style rule for both:

.primary-content,

.secondary-content {

width: 60%;

}

Now when we save our style sheet and switch to the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image82.jpg){width="5.3711537620297465in"
height="2.9819608486439195in"}

Now the two content sections only take up 60% of the available page
width, regardless of the size of the window browser. Later on, in the
layout section, we will adjust the positioning of each of the primary
and secondary content divs so that they are positioned in the middle.

### Em units 

As we have seen already with percentages, relative length units are
relative to other length values. The most commonly used unit is the em
unit. This is a font relative unit, as it's calculated based on a parent
element's font size. So, whenever we use an em unit as the value for an
elements CSS property, that em value is equal to the front size value of
the parent element.

So, for example, the default font size for browsers is 16 pixels. If we
set our page's body font size to 1em, then this is equivalent to setting
the font size to 16 pixels. This means that by default, 1em is
equivalent to 16 pixels, 2ems is equivalent to 32 pixels and so on and
so forth.

Let's change the title font size, which is currently set to 26 pixels,
to 3 ems and see what happens. So, change the font size value for the
title to 3em like this:

.title {

color: white;

font-size: 3em;

}

You will notice that the size of the title has increased. This is
because the value *3em* is making it three times that body font size
context:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image83.jpg){width="5.159574584426947in"
height="1.0480774278215224in"}

At the moment, the size of the font size is 48 in pixels because the
value from which the em is getting its size from is 16 pixels. So, if we
add a font size to the body element and set this to *0.5em*, let' see
what happens to the size of our title:

body {

color: \#878787;

margin: 0;

font-size: 0.5em;

}

When we refresh the browser, we can see that this has changed the size
of the text again:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image84.jpg){width="4.247922134733158in"
height="0.7923075240594926in"}

You'll notice that the size of the title has now decreased. The title's
font size value is now relative to the smaller font size of the body,
and therefore the title size now looks smaller. Going forward, we want
to keep the body context font size 1em, so make sure you change that to
1em as the font size:

body {

font-size: 1em;

}

Now if you refresh your page, you will notice that the size of the title
is still large. We'll need to define a smaller em value that's
equivalent to the title's original font size of 26 pixels. To do this,
we are going to have to do some simple math. We need to convert the
pixel value to its equivalent em value. To get the equivalent value,
we'll need to divide the pixel value by 16, since by default 1em is
equivalent to 16 pixels. This means we need to divide 26 by 16 and this
gives us a value of 1.625.

Then all we need to do is change current font size from 3em to the
equivalent of 26 pixels, which is 1.625em:

.title {

color: white;

font-size: 1.625em;

}

Now when we save our stylesheet and take a look at our page, we can see
that the title is now exactly the size that we want it to be:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image85.jpg){width="4.386536526684164in"
height="0.9in"}

We now have a simple formula for converting pixel values to ems, so we
can now define our *h1* element font sizes as ems instead of pixels. The
h1 element's font size is currently set to 90 pixels, and to get the
equivalent em value, we just need to divide it by 16 which gives us an
em based value of 5.625em. So now all we need to do is to change the
current font size from 90 pixels to 5.625em:

h1 {

font-size: 5.625em;

color: white;

}

If we save our stylesheet and switch over to the browser, you will
notice that the font size of the text *Granada Spain* stays exactly the
same as before. Using ems is very useful for creating scalable content,
because it can adapt to other font sizes. Child elements can resize
proportionally based on a parent's font size without us having to
manually calculate and redefine all the different font sizes for all
child elements like we would have to do with pixels.

However, there is one important aspect that we need to keep in mind when
using ems to size our font. When we use ems, there is a compounding
effect that happens with nested elements. To understand what I mean by
this compounding effect, let's look at an example. Let's go back to our
stylesheet and give the class *main-header* a font size value of 2em:

.main-header {

background-color:

orange; width: 100%;

font-size: 2em;

}

This means that the main header font size of 2em becomes the new context
for our title and heading font sizes, because the main header (or the
div with class main header) is the parent element of both the title and
the *h1* element. Now that we have set the font size for the main header
class, let's save our stylesheet and switch to the browser to see if
anything has changed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image86.jpg){width="4.698333333333333in"
height="1.2923075240594926in"}

Notice the font size for the title and the *h1* scale up based on the
new context of 2em. This is what is meant by compounding effect. What is
happening here is that the 2em font size value that was applied to the
main header is equal to 32 pixels, because it's two times the base font
size of 16 in the body element. This means that our title font is 1.625
times larger than 32 pixels and equivalent to 52 pixels. Likewise, the
*h1* is now 5.625 times larger than 32 pixels at an equivalent 180
pixels.

These are the type of issues that you can run into and that you need to
be aware of when using em units in your styles. This compounding effect
can get very troublesome depending on the number of font sizes that you
have defined in your stylesheet. It's best to avoid any predicaments
where deeply nested em based font sizes are affected by simply adding a
font size to a parent element. To avoid situations like this, we can
make use of rem units.

###  Rem units 

Previously, we saw how using em units can cause compounding effects when
we set font sizes on parent elements. So, to get around this issue, CSS
has another relative unit called a rem unit. Rem stands for root em, and
it's similar to an em unit. The difference is that it's relative to the
root element of the page which is the HTML element.

Rem units are not affected by inheritance the way ems are, which means
that if we get into a situation where we have a compounding issue with
ems, we can use rem units instead. In our stylesheet, we will change the
*h1* and title font size units to rems instead of ems. Let's start with
the title font size and change that to 1.625rem:

.title {

color: white;

font-size: 1.625rem;

}

Let's also change the h1 element from using the em unit to the rem unit:

h1 {

font-size: 5.625rem;

color: white;

}

So, if we save our stylesheet and switch to the browser, we should see
how this affects our elements:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image87.jpg){width="4.282638888888889in"
height="0.8769225721784777in"}

You will notice how the sizes of the title and the *h1* are now back to
their original size. The font size of our title and *h1* are no longer
relative to the 2em font size of the main header parent element but
instead, they are now relative to the root HTML element. This means that
both the title and the *h1* element are back to having a font size equal
to 26 pixels and 96 pixels respectively.

Rems are more predictable than ems, as they always relate back to the
root element. Now that we have got the font sizes exactly how we want
them, make sure to remove the font size declaration that we added to the
*main-header* class of 2em in our stylesheet.

So, you might be wondering, which ones to use in your stylesheets? The
simple answer is to use what you are most comfortable with that works
best for a particular project. Pixel units are more precise, easier to
understand and predictable. However, when you use pixel units, it means
that you are locked into those values and there is no dynamic resizing
when the browser window size changes. If the project that you are
working on has an emphasis on typographic design, or a design that needs
to scale and adapt fluidly across different devices, then units like
percentages, ems, or rems would be more suitable.

### Color values 

Color is an integral part of web design and with CSS, we can describe
color in three different ways: using a keyword, hexadecimal value or an
RGB function. Many CSS data types have predefined keyword values that
simply take the form of words that describe a color value. We have
already seen this when we used orange, light blue, forest green and
light coral. These are just a few in the long list of accepted keyword
values.

Others include black, silver, grey, and white. Some keywords include a
combination of words like cadet-blue, cornflower-blue, green-yellow and
even blonde-green! You can see a full list of all available color
keywords by going to the MDN docs here: <https://goo.gl/U52hQK>

The second and third way we can describe a color value is with an RGB
model, and this stands for Red, Green, Blue. One way to use the RGB
model is with hexadecimal notation, and these are commonly referred to
as a hex value. A hex value is combination of red, green and blue color
values. We'll define a hex value as the background color of our main
header. Hex values are specified by a hash sign followed by six
hexadecimal characters that are represented by the numbers 0 to 9 and
the letters a to f.

A hex value is written as three double-digit numbers, for example, when
the hex value for our background color is *\#ff0033*. The first two
letters -- *ff* -- represent the blue, the middle two digits - *00* -
represent green and the final two digits -- *33* --represent blue.

So now we're going to set the background color of the main header using
the hex value *\#ff0033*, so this is how the style rule should look for
the *main-header* class:

.main-header {

background-color: \#ff0033;

width: 100%;

}

Then save the stylesheet and view the header background in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image88.jpg){width="4.705215441819773in"
height="1.75in"}

As you can see from the screenshot above, the hex value that we used
turned the background color red. We're also able to use three-digit
notation where the hex values are abbreviated. We can do this if each of
the red, green and blue hex pairs are the same. This means that we can
shorten the current hex value and abbreviate each color using just one
character instead of two identical characters:

.main-header {

background-color: \#f03;

width: 100%;

}

If you save and preview the result in the browser, you will see that it
still represents a shade of red. You might be wondering how we come up
with these hex values when styling our pages? These values will come
from a graphics editor like Adobe Illustrator or Adobe Photoshop and
we're not expected to know each hex value combination to get colors on
the fly. You can refer to the MDN docs, which lists the hex value for
each color keyword.

In our stylesheet, we've already used some hex values in the *h3*
element styling. Now we're going to use a lighter variation of the color
orange as a hex value for our header background. So, we're going to
change the keyword value, *orange*, to a hex value that represents a
lighter shade of orange: *\#ffa949*:

.main-header {

background-color: \#ffa949;

width: 100%;

}

We're also going to give our main footer border the same hex value and
replace the orange keyword color:

\#main-footer {

padding-top: 60px;

padding-bottom: 60px;

border-bottom: solid 10px \#ffa949;

}

Now save the stylesheet and switch over to the browser to view how the
footer border bottom color looks like:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image89.jpg){width="4.4961537620297465in"
height="1.301175634295713in"}

The final method for applying color values uses what's called a
functional notation to specify the colors. To see this in action, let's
define our link colors with an RGB function. To create the RGB value,
we're going to type the letters *rgb* followed by a set of parenthesis,
and inside these parenthesis, we will write the numbers to represent
each of the color values separated by a comma:

a:link {

color: rgb(255, 169, 73);

}

It's important to note that when using the RGB function, the value *255*
represents the color white and this is the maximum value that we can
use. The value *0* represents pure black and it's the minimum value that
we can use. This means that if we change our RGB value to 255, 255, 255,
then we will get the color white. Conversely, if we change the value to
0, 0, 0 we will get the color black.

Finally, we will give our links a lighter, transparent shade of orange
(the same rgb color that we used for the links) when the user hovers
over them. To create a transparent shade of the color, we will add a
fourth number called alpha to the RGB function and set it to 0.4:

a:hover {

color: rgb(255, 169, 73, 0.4);

}

Now let's save our stylesheet and preview the result in the browser. We
can see that the links are now transparent when you hover over them:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image90.jpg){width="3.0930227471566054in"
height="1.0in"}

### Text styles 

The effect of text on the way we view web pages cannot be emphasised
enough and there are different properties that we can use to define text
styles. Keyword values are what most of them use and this means that it
is easy to understand what they do.

### Text alignment 

The text-align property enables us to control and direct the horizontal
alignment of the text. Initially, we provided our *primary-content*
element with a text-align property to center align the text-content in
the div. Now, we also need to center align the text-content in the main
header.

We can achieve this by ensuring the *primary-content* selector is
grouped with the *main-header* class selector. To do this, we will need
to go into the stylesheet and locate the style rule that currently
centers the *primary-content* div. This is located just under the styles
for the title class. Simply add the *main-header* as the next class
separated by a comma:

.primary-content, .main-header {

text-align: center;

}

Now, when we save the stylesheet and refresh the browser, we see that
the text inside the header is now center aligned:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image91.jpg){width="4.233871391076115in"
height="1.8629035433070866in"}

The default for the text-align property is on the left side, but it can
also take other keyword values such as *right*, which should be obvious,
as this aligns the content to the right side. It additionally accepts
the value *justify*. The justify value makes the text lines in a
paragraph an equal width, just like a magazine or book alignment.
Earlier, we set the primary and secondary width of our containers to 60%
and this is why we can see the large whitespace area to the right side.
We will be fixing this very soon.

### Text Transform 

Next, we can make use of the text-transform property to change the
text-case to capitalized, uppercase or lower case. Now, we can make the
text content in our *h1* all capitalized. To do this, let's go back to
our stylesheet and scroll up to the *h1* rule and directly beneath the
color declaration inside the *h1* style rule, we will include a
*text-transform* property. We'll then use the keyword: *uppercase*:

h1 {

font-size: 5.625rem; /\* 90px / 16px \*/

color: rgba(255, 255, 255, .5);

text-transform: uppercase;

}

Let's save our style sheet, refresh our browser, and then we can clearly
see the way in which the value transforms the text into uppercase
letters, despite the fact that we didn't input it directly through the
keyboard in the HTML:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image92.jpg){width="4.052419072615923in"
height="0.8246434820647419in"}

We could likewise utilize the values *lowercase* and *capitalize*. Now,
simply go ahead and attempt those, so that you can see what they do.
Also, we can make use of *the text-decoration* property to set the
elements' line decoration, and we'll just make use of this property for
the removal of the underlines from the links. For instance, let's head
toward our CSS file and scroll down to where our link styles are, and
try to give our links rule a *text-decoration* property. Write
*text-decoration*, and then set the value to the keyword *none*.

a:link {

color: rgb(255, 169, 73);

text-decoration: none;

}

Now, once our style sheet is saved, we can refresh the browser. We
should be able to see the way in which the underlines in our links have
now disappeared.

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image93.jpg){width="3.0925929571303588in"
height="1.5in"}

However, we can likewise utilize the text-decoration property on just
about any of the elements. So, for example, let's scroll up to where we
have our *h2* rule, and beneath the font size declaration, let's include
a *text-decoration* property, and now we will set the value to
*underline*:

h2 {

font-size: 53px;

text-decoration: underline;

}

Let's save this and we should be able to see the way the underline is
included beneath the heading text:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image94.jpg){width="4.530294181977252in"
height="1.1653226159230097in"}

The *font-weight* property gives us a chance to set the weight style of
our text-content. By default, all the headings are set to the bold
style. Now, if we give them a *font-weight* property, and set the value
to the *normal* style, this will remove the bold style from the heading.
To do this, let's go back to our stylesheet and locate the style for our
*h1* rule. We will include a *font-weight* property and then we'll set
the value to *normal*:

h1 {

font-size: 5.625rem; /\* 90px / 16px \*/

color: rgba(255, 255, 255, .5);

text-transform: uppercase;

font-weight: normal;

}

I'll go ahead and copy the font property declaration we just typed and
then paste it right beneath, in the h2 rule after text decoration
property:

h2 {

font-size: 53px;

text-decoration: underline;

font-weight: normal;

}

Now, when we save our stylesheet and refresh the browser, we can see
that the two headings are no longer bold:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image95.jpg){width="4.145580708661417in"
height="1.7096773840769903in"}

The *font-weight* property also accepts two other keyword values. Other
than the *bold* and *normal*, it accepts the values *lighter* and
*bolder*, which either lightens or darkens a text's font weight
depending on its acquired font weight.

These values are dependent on the font that is installed on the user's
computer, and this means that they are not as commonly used as the
values normal and bold. You can also use numeric numbers as values for
this property, but as I mentioned, this depends on the font that we use
for the text that is available on the user's computer.

### Font properties

Similar to text properties, font properties allow us to change the text
appearance by assigning a font family, a font style, a font size, and
more. Firstly, we will be able to make use of the font family property
for the definition of a font or typeface for our text; also, we have two
types of font family names.

We have a particular font family name, such as Verdana, Helvetica, or
Arial. The second is the generic family name, including monospace, sans
serif, and serif. Now, we may be a bit tired of seeing the serif font on
the browser, as it's actually the default font.

### Font Family

Let's give ourselves a font family property, right at the top of the
body rule, right under the font size declaration. We will type
*font-family*, and then we'll set the value to *sans-serif*:

body {

color: \#878787; margin: 0;

font-size: 1em; /\* 16px \*/

font-family: sans-serif;

}

Now, we can save our stylesheet, refresh our page, and then we can see
that all the page content has changed to the *sans-serif* font:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image96.jpg){width="4.428827646544182in"
height="1.8104833770778652in"}

Compared to serif fonts, there is no finishing ornamentation or strokes
in sans-serif fonts. We'll need to make use of a really particular font
family than just *sans-serif*. When selecting a typeface or font, it is
important to keep in mind the order in which we declare the fonts, as
this will determine the priority of each font. Also, we need to be
confident that the users visiting our websites have the fonts installed
on their computers. This is because not all fonts are usually available
on all of the computers sold today.

Presently, any font available and accessible on all computers is known
as web-safe fonts. Generally, we'll have to carefully define all other
web-safe fonts as fall-back through the creation of what is known as a
font stack.

Basically, CSS font stacks are an organized list of fonts that the
browser takes into a process of cycling through until it discovers a
font that is installed on the computer system of the user, and we
compose the font stack as a comma separated list of fonts. In case a
user does not have the first-choice font installed, the browser will
attempt the alternative font from the same list.

Let's create a font stack declaration in our stylesheet. Make sure that
you are in the style rule for the body element and add the following
font stack as the value for the font family property:

body {

color: \#878787; margin: 0;

font-size: 1em; /\* 16px \*/

font-family: \"Helvetica Neue\", Helvetica, Arial, sans-serif;;

}

We have set the first font in the stack to *Helvetica Neue* and then the
second font in the stack to *Arial*, then with a comma after it, we have
the generic *sans-serif* font name. At this point, if the user has
*Helvetica* on their computer system, the browser will show it.
Otherwise, it will display Arial, and if it happens that *Arial* and
*Helvetica* are not installed, the browser will then make use of the
generic font family of the *san-serif* if everything else fails.

It's usually a good practice to ensure that the generic font family name
is included, as a final alternative in the font stack. Also, if a font
family name is comprised of more than a single word, we'll have to
compose and type it inside of quotes as we have done already.

### Font Style

The font style property can give our text an oblique or italic style. If
we go back to the body style rule and include a font style property, and
type *font-style* then set the value to *italic*:

body {

color: \#878787;

margin: 0;

font-size: 1em; /\* 16px \*/

font-family: \"Helvetica Neue\", Helvetica, Arial, sans-serif;

font-style: italic;

}

To see how this affects our content, let's save our stylesheet and
refresh the browser -- we should see that all the text content on the
page is italicized:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image97.jpg){width="4.462364391951006in"
height="2.3870964566929134in"}

We can likewise set the value to oblique. Oblique is not often used;
this is usually because many typefaces do not contain an oblique
version. Moving forward, make sure to remove the italics rule from the
body style.

### Line height

The line height is the property that defines the vertical spacing
between the text lines. In case a page has long paragraphs with many
lines of content, it might be too uncomfortable or difficult for the
user to read. A liberal amount of line spacing would make the content
more readable and with the CSS line-height property, we will be able to
increase or decrease the vertical gaps in the lines of the content.

Now, we can see that our page is showing the default line height value
of the browser, which is typically too cramped for easy readability. So,
just before the font family declaration, we will add a line height
declaration and set the value to 1.5:

body {

color: \#878787;

margin: 0;

font-size: 1em; /\* 16px \*/

line-height: 1.5;

font-family: \"Helvetica Neue\", Helvetica, Arial, sans-serif;

}

Let' save our stylesheet and see how this looks in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image98.jpg){width="4.995967847769029in"
height="1.2718646106736657in"}

We can see the way in which every element on the page acquires that line
height and there is now some breathing space between the lines. The
line-height property can accept a range of values. It can also accept
the normal default value as well as a unit-less number value, percentage
value, or a pixel. Also, it can accept relative units such as rems or
ems. But it's really a best practice to define line heights with
unit-less numbers.

The line height is relative and it will continually scale with an
element's font size. It's more predictable than the use of length
values. The browser determines the line height based on the element's
font size. So, in our example rule above, the browser multiplies each
element's font size by 1.5 -- since this is the font size applied to the
body rule and is inherited by all elements inside the parent body
element.

As I mentioned earlier, the value of the unit-less line-height is
relative to the font size that was given to an element. For example, the
*1.5* value will display a larger line height for the *h1* than what it
does for the paragraphs since its font size is much bigger than the
paragraphs.

Sometimes, we just have to offer certain elements custom line values to
reduce the vertical spacing in case it's too large. So, let's go back to
our stylesheet and locate the *h1* rule and directly beneath the
*font-weight* declaration, let's ensure the *h1* is given a custom line
height of *1.3*:

h1 {

font-size: 5.625rem; /\* 90px/16px \*/

color: rgba(255, 255, 255, 1);

text-transform: uppercase;

font-weight: normal;

line-height: 1.3;

}

We can now save our style sheet and refresh the browser and we will see
the how it reduces the line spacing that is around our h1. Finally, CSS
allows us to write a shorthand property, which allows us to compose all
the font properties right in one value. So, for instance, in the body
rule, if we choose to define the font-weight, line-height, font-family,
and font-size at once, we should be able to ensure it is given the
property *font*, and then all the values can be listed:

body {

color: \#878787;

margin: 0;

font: 1em/1.5 \"Helvetica Neue\", Helvetica, Arial, sans-serif;

}

When we use the font shorthand property, it's relatively essential to
recall that the font-family and the font-size must be defined. If they
are left out, the browser ignores the whole line, and the order of the
value is also important. If a font weight or font style value is
utilized, they must be defined before the value of the font size.
Lastly, the font family should be the last value defined. So, if you go
ahead and save the stylesheet and refresh the browser, it should look
exactly as it did before.

**\
**

Day Six 
========

The box model 
--------------

The basis of the CSS layout is the box model since it directs the way in
which elements are shown and the way in which they associate with one
another. Imagine every element on the page as a rectangular box. Every
box is made of particular dimensions and takes up a particular measure
of space. The space the box occupies depends on the content in it, as
well as the margins and the padding borders around the content:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image99.png){width="3.7933333333333334in"
height="2.486666666666667in"}

So, the box model is what dictates the amount of space each element has
on the page. Now, let's dive somewhat deeper into this idea by revising
the main components that constitute the CSS box model. Start thinking of
each HTML component on the page as a box. In fact, you can apply a
global style rule that will add a red outline to all the elements on the
page. To do this, simply add the following style rule to the top of the
stylesheet:

\* {

outline: 2px solid red;

}

This will add an outline to all the elements on the page and it will let
us easily visualize each of the elements on the page as a box:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image100.jpg){width="4.912073490813648in"
height="3.5in"}

Each element is designed with a box or rectangle. Now, to effectively
understand the concept of the CSS box model, it is important that we
know the two ways in which elements can be displayed. Every element has
a display property, depending on the kind of element it is. The default
of most elements is inline or block. Now, block elements are composed of
a separate block that has to take up the full width that is available. A
few examples of block elements include, list items, paragraphs, divs and
any heading tag.

You can observe how the block-level divs on our page, and also the lists
and headings are taking up a whole line of content. They're additionally
forcing another new line of text before and after the next element.
Also, inline elements only take up as much width as they have to. They
don't constrain any lines, and they remain in line with whatever remains
of the rest of the text. A few examples of inline elements are images,
anchor elements, and span tags.

In the title span element, observe the way in which its width consumes
the space of its text, and the reason it's shown on its own line is
because a block-level *h1* element exists beneath it. The block-level
*h1* forces the new line. So now, let's examine how the margins,
borders, and padding interact with one another to form a box since it's
important to understand. The box model is designed with four distinct
parts.

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image101.gif){width="2.75in" height="2.75in"}

The core component and innermost area of the box is the content area.
This is the area in which the actual content, such as image or text of
the element is contained. Surrounding the area of the text is the
padding area. Basically, padding is used to give elements some breathing
space. The next outermost part of the box is known as the border area of
the box. Think of it as an outline to the box model. There are a range
of styles for borders such as thickness and color. Finally, the margin
area is positioned outside of the box. This is the space around an
element that isolates it from different components.

The padding area makes space inside of the box, and the margin area
makes space outside of and around the box. Imagine you have a cardboard
box that you have filled with fragile items, but you have surrounded it
with bubble wrap to cushion any impact. The padding in the box model is
similar to the bubble wrap, in that it is added inside the box. The
Google Chrome dev tool provides a really clear view of the box model for
each element on the page. If you click on **View** \> **Developer** \>
**Developer Tools**:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image102.jpg){width="4.285325896762904in"
height="2.375in"}

It will display the chrome developer tool panel at the bottom of the
page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image103.jpg){width="5.763888888888889in"
height="1.476388888888889in"}

Once you have the dev tools panel open, in the elements tab on the left,
open up the header element and click on the *h1* element. This will be
the element selected in the chrome dev tool and you will see the *h1*
highlighted on the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image104.jpg){width="5.763888888888889in"
height="3.252083333333333in"}

Once the *h1* element is selected, you can increase the width of the
styles tab on the right and scroll all the way down until you see the
box model for the *h1*:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image105.jpg){width="4.755818022747157in"
height="3.25in"}

As you can see from the above screenshot, the *h1* element's box model
can be seen clearly. We have a default margin applied to the top and
bottom, and it has no border or padding. Hopefully, this will give you a
better understanding of how each element on the page is represented, and
how they interact with each other based on their display type.

### Padding

Let's start by looking at the way in which the content area of an
element is affected by padding. In the exercise file, I added a new div
that would contain the *h2* heading and a paragraph. Let's open the
*index.html* and add a class to the div that is on around line number 19
in the file. We'll call this class: *buildings*.

\<div class=\"buildings\"\>

\<!\-- \<h2\>Check out all the buildings\</h2\> \<p\> Granada\'s climate
is friendly and dry,

the air clean and healthy, with clear and cheerful skies.

Strong winds, fog and snow are rare. \</p\> \--\>

\</div\>

Currently, the *h2* and the paragraph text inside of our *buildings* div
are commented out. Make sure to save the *index.html file*, then open up
the stylesheet and scroll down to the end after the layout styles
section. Then we will target the class buildings.

We're going to make the text color white and give it a cool lighter
shade of black background color:

.buildings {

color: white;

background-color: \#434a52;

}

Now to see the results, let's save the stylesheet and open the
*index.html* file in the browser. You will notice that the buildings div
is not visible. This is because it doesn't comprise any of the box model
components we learned earlier. This means that we need to add the
content area, and we can easily do this by uncommenting the *h2* and the
paragraph text in the *index.html* file.

Now, I'll select the content and click the command forward slash on the
MAC or control forward slash on Windows to uncomment it. Then simply
save the *index.html* file and we can now see that the content area is
now displayed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image106.jpg){width="5.0371686351706035in"
height="1.552419072615923in"}

Since we now have the content area of the box, we can now include the
padding area with all the padding properties. We can achieve this by
defining the values for the padding as any length or choice of
percentage unit. There are two ways we can set the values for the
padding. The first way is to simply set each of the padding values
individually and the second method is to use the shorthand notation.
We'll learn both ways, and we're going to start by setting the padding
on each of the sides individually. Let's go back to our stylesheet and
the *buildings* class. Then we will set the top padding of the div to
100 pixels, then we'll set the padding left and padding right properties
to 120 pixels. Finally, we'll set the bottom padding property to 100
pixels:

.buildings {

color: white;

background-color: \#434a52;

padding-top: 100px;

padding-right: 120px;

padding-bottom: 100px;

padding-left: 120px;

}

As you can see here, we are making use of four different padding
declarations. One meant for each side of the div. To see how this
affects our *buildings* div, let's save our style sheet and then refresh
the browser - we will be able to see the padded space around the content
area:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image107.jpg){width="4.974933289588801in"
height="2.3951607611548558in"}

The second way that we can add the same padding is using the shorthand
notation with just one declaration instead of four. Let's write this
shorthand notation directly beneath the individual declarations. To
write the shorthand notation, we will begin by just writing 'padding'
followed by a colon. Depending on the number of values we provide, these
will be applied to the div. So, for example if we only add just one
value like this:

.buildings {

color: white;

background-color: \#434a52;

padding: 100px;

}

This means that 100 pixels of padding will be applied to all four sides
of the div. Go ahead and see for yourself by saving and refreshing the
browser. Since the top and bottom padding values are 100 pixels, and the
left and right are 120 pixels, we can write them like this:

.buildings {

color: white;

background-color: \#434a52;

padding: 100px 120px;

}

The first value of 100 pixels will be applied to the top and bottom
sides, and the next 120-pixel value will be applied to the right and
left sides of the div box model. Let's save this and refresh the browser
and this should work exactly the same as the four individual padding
declarations. We can also apply the padding declaration using three
values only as in the following:

.buildings {

color: white;

background-color: \#434a52;

padding: 100px 120px 200px;

}

With this shorthand version, the first value is applied to the top and
the next middle value is applied to the left and right side and the
final value is applied to the bottom. To see how this looks, add this
shorthand notation, save the file and refresh the browser -- you will
notice that the bottom side has a larger padding area than the top:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image108.jpg){width="4.957226596675415in"
height="2.318548775153106in"}

It's important to understand the order of the shorthand values, as the
same order is used on other shorthand properties -- as we will soon see.
To recap, the order of the values are: top, right, bottom and left. To
help you remember the order, think clockwise starting from the top.
Let's remove the final third value from the declaration and only use two
values for the padding declaration:

.buildings {

color: white;

background-color: \#434a52;

padding: 100px 120px;

}

Keep in mind that we want our page to be as flexible as possible, so
this means that if it is viewed in mobile, tablet or desktop, the
elements should be styled with fluid values. So, for this div, let's
define a fluid padding value using percentages:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

}

When we use percentage values, it's important to remember that the value
of the padding which is applied to each side of the div box is relative
to the width of the container. So, in our declaration above, we are
setting the top and bottom padding values to 18% of the total width of
our buildings container div and likewise, we are setting the left and
right to 24% of the width of the container.

Let's save our stylesheet and then switch to the browser window and
refresh. We should see how the padding on each side of the div adjusts
to the buildings container's width:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image109.jpg){width="4.99759186351706in"
height="3.125in"}

### Borders

With the content and padding areas defined, we now need to add a border
area to the buildings div. To add borders to any element, there are
three properties that we can use. The first property that we need to
define is the width for the border. To do this, we'll need to go back to
the stylesheet and in the style rule for the buildings div, we'll add a
*border-width* declaration and we'll set its value to 10px:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px;

}

We can define the border width value with any length or percentage value
or even keyword values such as thin, medium or thick. For us to actually
see the border, we need to add a border style property. So, after adding
the declaration for the border width property, we'll add a border style
declaration. This property sets the style of the elements border, and
the values that it can accept are solid, dashed, and dotted. Let's play
around with some of the values to see how they actually look, so I'll
set the border style value to dotted:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px;

border-style: dotted;

}

Also, if we want to give our border a custom color, we can use the
border-color property to achieve this. So, I'm going to add a border
color property and set the value to the same orange hexadecimal value
that we have been using:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px;

border-style: dotted;

border-color: \#ffa949;

}

Remember that the border color can be any keyword value, RGB value, or a
hexadecimal value. To see how this looks, let's save our stylesheet and
then refresh the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image110.jpg){width="4.703744531933508in"
height="3.0120964566929134in"}

From the screenshot above, we can see that our buildings div now has an
orange dotted border on each side. If we happen to want to have a dashed
border style instead, we can simply do this by changing the border style
property value to dashed instead of dotted:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px;

border-style: dashed;

border-color: \#ffa949;

}

Now, save the file and look at it in the browser. Our div now has a
dashed border style:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image111.jpg){width="4.514136045494313in"
height="2.8830643044619424in"}

For our div, we want to have a solid border style, instead of dotted and
dashed. So, I'm simply going to set the value for the border style to
solid:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px;

border-style: solid;

border-color: \#ffa949;

}

Like before, let's save and view how our buildings div looks with the
solid border style:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image112.jpg){width="5.04974956255468in"
height="3.0967738407699037in"}

In the same way that we used a shorthand notation to add padding to the
buildings div, we can also use the same shorthand notation on the border
property. So, this means that the border property can have one to two,
three or four values.

To see how this also works with borders, let's add a second value of 20
pixels after the first value of 10 pixels for the border width property:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px 20px;

border-style: solid;

border-color: \#ffa949;

}

As always, let's save the file and preview the result in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image113.jpg){width="4.683732502187227in"
height="3.0201607611548558in"}

You'll notice that the border width for each side is no longer equal.
The top and bottom still have a width of 10 pixels and now the left and
right have a width of 20 pixels each.

Similarly, we can set each side to have a different border style. Say if
we wanted the left and right side to have a different border style, we
could simply add another value to the border style property -- let's set
this to dotted:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px 20px;

border-style: solid dotted;

border-color: \#ffa949;

}

When we save and refresh the page, our top and bottom border styles are
solid, whilst the left and right sides have a border style of dotted:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image114.jpg){width="4.625in"
height="2.9276804461942256in"}

We can extend this to the border color property as well, so if we wanted
to have different border colors for the top and bottom and left and
right, we simply add another value to the border color property. Let's
add the keyword red before the hexadecimal value for the border-color
property:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px 20px;

border-style: solid dotted;

border-color: red \#ffa949;

}

To see how this now looks, simply save the file and preview the changes
in the browser. You will notice clearly now that the top and bottom
border color is red and the left and right still have the orange
hexadecimal color:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image115.jpg){width="5.275795056867891in"
height="3.3911286089238843in"}

As I mentioned previously, it's important to remember the order of these
values. For example, if we go back and add two more color values, say
blue and green respectively:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-width: 10px 20px;

border-style: solid dotted;

border-color: red \#ffa949 blue green;

}

The first color value is for the top border, then the next one is for
the right border, then the third value, green, will be applied to the
bottom border and finally the last value is applied to the left border:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image116.jpg){width="5.105033902012249in"
height="3.25in"}

In web design, it is rare to see an element that has different border
colors, width and border styles. In fact, most of the time, a single
border width, color and border style is used for an element. Just like
we defined the padding values using one declaration, we can also define
the border property using the shorthand version.

To do this, let's go back to our stylesheet and I'm going to add the
shorthand notation for adding a border by writing the property border
followed by values for the width, style and color all in one
declaration:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border: 10px solid \#ffa949;

}

Instead of having individual properties to define the styles for the
border, we are now using the shorthand notation. So, the first value
defines the width of all sides of the border, then the style of the
border, which is solid, and finally the color of the border as a
hexadecimal value. If we now save this and refresh the browser, we will
get the same result that we did earlier when we had individual
declarations for the width, style and color:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image112.jpg){width="4.842741688538933in"
height="2.9698261154855645in"}

Even though we have used the shorthand declaration for styling the
border, we still have the individual border properties available to us.
So, if we wanted to override one of the border values, we can do so
easily. For example, let's say that we wanted a dashed border for the
bottom side instead of a solid one. To do this, we simply apply the
border-bottom-style property and set its value to dashed:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border: 10px solid \#ffa949;

border-bottom-style: dashed;

}

The border bottom will now have a dashed border style:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image117.jpg){width="5.095107174103237in"
height="3.2620964566929134in"}

We can do the same thing for the border left style, border top style and
so on. The same can also be done if we want to have a different border
color. Say we want the left side to have a border color of green instead
of orange. We can easily achieve this by setting the border-left-color
property to green:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border: 10px solid \#ffa949;

border-bottom-style: dashed;

border-left-color: green;

}

So now if we save and preview the result in the browser, we can see that
the left border color is now green:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image118.jpg){width="5.166838363954506in"
height="3.302419072615923in"}

Now that we have seen the different ways we can style an element using
the border property, we want to apply a simple and consistent style to
the *buildings* div. Let's apply a border to the top part only, and to
do this we can use the border-top property:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

}

As you would expect, this only adds a border to the top of the buildings
div:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image119.jpg){width="5.017902449693788in"
height="3.1370964566929134in"}

Before wrapping up the border property, there is one important aspect
that we need to learn about border styles. If there is no color
specified, the border color will take on the text color of that
containing element. To see how this works, let's remove the color value
from the border-top declaration and change the color property value to
red:

.buildings {

color: red;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid;

}

If we now save the stylesheet and open the browser and refresh, we can
see that the color of the top border has taken on the color of the text
since no color is specified in the declaration:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image120.jpg){width="4.7510017497812775in"
height="3.0in"}

Make sure to set the color back to white and set the color of the border
as the last value using the hexadecimal value of *\#ffa949*:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

}

You should now have a thorough understanding of borders, and should you
come across a border property, you will know exactly what it means.

### Margins

As we saw in the box model, the margin is the outermost part of the box:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image121.png){width="2.5555555555555554in"
height="2.0277777777777777in"}

In the same way that we can define padding and borders on all four sides
of the box, we can also define a margin for each side of the box. The
margin property accepts percentage values or any length value. We've
already learned about the clockwise from top, right, bottom, and left
when we added padding and border. We also saw how we can declare each
side's value using the shorthand notation. The same order of values
applies to the margin property.

Now that we are equipped with how to define property values using the
shorthand notation, we'll add the margin property to our buildings div
using the shorthand notation. Make sure you have the stylesheet opened
for this section and then locate the styles for the buildings class.
Beneath the border-top declaration, we'll use the shorthand notation to
give our div some margin:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

margin: 105px 0 60px 0;

}

The shorthand notation for the margin should be familiar to you by now.
Basically, this is the same as writing each individual property
declaration like margin-top, margin-right, margin-bottom, and
margin-left.

We can further refine this shorthand notation to only three values,
because the right and left margin values are the same. We can simply use
one value to target both like this:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

margin: 105px 0 60px;

}

What we've done is omitted the fourth value, which was another zero, and
now this means that the top will have a margin of 105 pixels, the left
and right values will have 0 and the bottom will have a margin of 60
pixels. So, if we save our stylesheet and refresh the browser, we can
now see that we have given the buildings div some extra breathing space
from the other elements:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image122.jpg){width="4.795248250218723in"
height="3.125in"}

The margins give elements a degree of separation from other elements on
the page. So, when we add a margin to an element, it pushes that element
away from other elements on the page. It's also important to understand
that the margin is applied outside of the border in the box model.
Modern browsers come with dev tools that you can use to examine and edit
each element's box model parameters on the fly. Since we're using
Chrome, I will click on the View \> Developer \> Developer Tools -- to
open the Chrome developer panel at the bottom:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image123.jpg){width="5.763888888888889in"
height="3.029861111111111in"}

Once you have the Chrome dev tools open, you should see a small
magnifying glass in the top left corner of the pane. When you click the
icon, it allows you to inspect the styles of any element on the page.
Click on the magnifying glass icon and then select the buildings div on
our page. Then on the right side of the panel, we can see all the CSS
properties we've applied to the buildings div:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image124.jpg){width="5.763888888888889in"
height="2.975in"}

If you hover your cursor over the right side of the panel where we have
the CSS styles and scroll down, we can see all the box model parameters
for the *buildings* div:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image125.jpg){width="4.875in"
height="2.516205161854768in"}

If you hover over the margin, border, padding or the center of the box,
it will highlight each area in the browser. So, when you hover over the
center, it highlights the content area in the buildings div in the
browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image126.jpg){width="5.180247156605424in"
height="3.125in"}

Likewise, when you hover over the padding, border, or margin areas it
will highlight each part in the browser -- this is the perfect example
of how the box model works in the browser. I would encourage you to
explore this tool in more detail, and you can even live edit the values
that we set for the padding, border, and margin in the styles tab and
see the results immediately.

Keep in mind though, that this will not change our stylesheet source
file, it is only the live version that is affected when you make the
changes. Also, the moment you refresh, any changes you made in the
browser will be reset to the values in our stylesheet.

Dev tools are not limited to the Chrome browser. In fact, Firefox,
Safari and Internet Explorer all have similar dev tools for inspecting
an element's styles and box model parameters. You can close the dev tool
panel by clicking the close icon on the top right corner of the panel.
Now that we have added margins to our buildings div, let's give the *h2*
and *h3* elements a bottom margin that will give them a little bit of
separation from the content below. We will use em units to define the
margins.

Let's go back into the stylesheet and locate the styles for the *h2*
rule. We'll need to scroll up. Then inside the *h2* styles declaration
block, we'll add a margin-bottom property -- because we only want to
apply a bottom margin only. We want the margin value to be equivalent to
26 pixels. So, if you recall how we worked out the em unit value for
this -- we divide the desired value, in our case 26, by the pixel font
size value of the *h2*.

The pixel equivalent of our *h2* font size is 53, so this means that we
need to divide 26 by 53, which gives us an em value of 0.5em. Just as we
have been doing before, I'm going to add a comment that will let us know
what this value is in pixels:

h2 {

font-size: 3.3125em; /\* 53px/16px \*/

font-weight: normal;

line-height: 1.1;

margin-bottom: 0.5em; /\* 26px \*/

}

You will notice that the margin has been applied to the bottom side of
the *h2* box element and it has closed up a little bit:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image127.jpg){width="4.928097112860892in"
height="1.4677416885389327in"}

You will also notice that there is a margin top style applied to our
*h2* element, even though we didn't add a margin top in our stylesheet.
This margin top styling for the *h2* element is actually coming from the
browser's user agent styling. If you look closely at the styles tab, you
will be able to see this:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image128.jpg){width="5.317824803149606in"
height="1.9233869203849518in"}

For the *h3* on our page, we're going to do the same thing. Back in the
stylesheet inside the *h3* style rule, which should be directly under
the *h2* styles. Below the line height declaration, we're going to add a
margin-bottom property and we'll set an em value that is equivalent to
34 pixels. Like we did before, we will need to divide 34 by the *h3's*
pixel font size, which is 20 pixels. So, 34 divided by 20 gives us an em
value of 1.7em -- and as we have been doing throughout, I will write a
comment that lets us know what this value is in pixels:

h3 {

font-size: 1.25em; /\* 20px/16px \*/

color: \#48525c;

line-height: 1.2;

margin-bottom: 1.7em; /\*34px\*/

}

Now when we save our stylesheet and preview the change in the browser
and scroll down to the *h2* element, we can see that it now has a bottom
margin applied:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image129.jpg){width="2.45121719160105in"
height="1.7943547681539807in"}

### Negative margin values

As well as adding margins to push elements away from each other, we can
also use negative values in margins to pull elements together. Back in
our stylesheet, we'll add a rule to our *buildings* div further down the
file, and instead of 105 pixels for the top margin on the div, let's
make it a negative *50* pixels:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

margin: -50px 0 60px;

}

Now, let's save the stylesheet and see how this negative value affects
the buildings div on our page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image130.jpg){width="5.06448709536308in"
height="2.326613079615048in"}

When we use negative values for margins, it pulls any surrounding
elements closer, and in our case here, the anchor element is now
overlapping the buildings div. In the majority of cases, we won't need
to use negative values and it's best avoided for layout. Negative values
push or pull elements to and from spaces that they're not supposed to
occupy by default. However, there are times where we need to use
negative values, so they do have their uses. Make sure to set the margin
back to 105 pixels as before:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

margin: 105px 0 60px;

}

### Center Body Content 

There is one more aspect that we need to learn about when it comes to
margins, which is how to use margins and width to center content on the
page. So far, all our content has been left aligned, and what we want to
do is center the entire content in the middle.

To do this, let's head back to the stylesheet and find the primary and
secondary content rules -- they should be on around line 85, underneath
the comment for layout styles. Now, it's important to know that for the
content to be centered, we need to have the width set to less than 100%
if percentages are used. We already have the width set for both divs to
60% and all we're going to do is add a margin property and set its value
to auto:

.primary-content,

.secondary-content {

width: 60%;

margin: auto;

}

By using the value auto, the browser will automatically calculate the
margins for each side and this means all the margins are set to be
equal:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image131.jpg){width="5.763888888888889in"
height="3.2180555555555554in"}

Both divs are now perfectly centred on the page, and this means that
there are equal margins on the left and right sides of the browser
window.

### Display Values

One of CSS' most important properties is the display property, which is
used for controlling layout on a web page. The display property can be
used to override the default settings of an element. The display
property can accept several different values, and the most common
display values are the keyword values *none*, *block*, *inline*, and
*inline-block*. To see how the display property affects an element,
let's open up the stylesheet file and give our buildings div element a
display property and set the value to none:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

margin: 105px 0 60px;

display: none;

}

When we refresh the browser window, we will notice that our buildings
div is no longer there:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image132.jpg){width="4.869581146106737in"
height="3.2338713910761157in"}

Our buildings div has disappeared from the page and the rest of the page
displays as if it was never there. We obviously would like to keep our
buildings div, so let's go back and remove the display none declaration:

.buildings {

color: white;

background-color: \#434a52;

padding: 18% 24%;

border-top: 10px solid \#ffa949;

margin: 105px 0 60px;

}

By default, the value *block* is the display value for block level
elements like divs, paragraphs and all headings. This means that they
each take up the full width available in their parent element. Anchor
elements, on the other hand, have their display values set to inline by
default. We can actually change an inline element's display value, so
let's change the link element's display value to block and see what
happens. So back in the stylesheet, locate the styles for the link
element, which should be on around line 33, and let's give it a display
property and set the value to block:

a:link {

color: rgb(255, 169, 73);

text-decoration: none;

display: block;

}

The value block overrides the link's default display of inline. Now, if
we save the stylesheet and refresh the browser, we can see that the
previously inline anchor elements are now taking up the entire available
width:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image133.jpg){width="5.408054461942257in"
height="1.2620964566929134in"}

As you can see, each line is on its own with a line before it and a line
after it. To really see how this affects our layout, let's give our
links a background color. So back in the style rules for the link
elements, let's add a *background-color* property and set the value to
tomato:

a:link {

color: rgb(255, 169, 73);

text-decoration: none;

display: block;

background-color: tomato;

}

When we save the stylesheet and refresh the browser, we can see clearly
that they are now block level elements:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image134.jpg){width="5.763888888888889in"
height="1.2180555555555554in"}

Going forward, we don't want to have our anchor links displayed as block
level and we certainly don't need the tomato background color. So, we
will remove the display and background color declarations:

a:link {

color: rgb(255, 169, 73);

text-decoration: none;

display: block;

}

Now that we know how inline and block level display works, let's see
what happens when we give our *h1* heading a display value of inline.
Back in the stylesheet, locate the styles for the *h1*, which should
start on line number 9 in the stylesheet and then give it a display
property with a value of inline:

h1 {

font-size: 5.625rem; /\* 90px/16px \*/

color: rgba(255, 255, 255, 1);

text-transform: uppercase;

font-weight: normal;

line-height: 1.3;

display: inline;

}

Inline elements stay with the rest of the content. Save the stylesheet
and see how this affects our *h1* element:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image135.jpg){width="4.25in"
height="0.9181025809273841in"}

You will immediately notice how the *h1* now wraps to the same line that
the span element is on, since the span is also an inline element. We
want our *h1* element to be displayed as a block level component, so
we'll remove the display property and let it default back to block level
display:

h1 {

font-size: 5.625rem; /\* 90px/16px \*/

color: rgba(255, 255, 255, 1);

text-transform: uppercase;

font-weight: normal;

line-height: 1.3;

}

We can also do the same thing to the list items on our page, since
they're also block level elements by default. So, back in our
stylesheet, we're going to add a new rule to target all the list items.
We'll add these new styles underneath the styles for the *h3* rule. To
target all the list elements, I'm going to type the list item selector
*li* and add some style declarations:

li {

display: inline;

}

Now when we save the stylesheet, notice how all the list items are now
all on one line, or inline with each other:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image136.jpg){width="4.931527777777778in"
height="1.4919356955380578in"}

Now if we wanted to give our list items a little bit of breathing space,
we could add a left and right padding. We can easily do that, so back in
the stylesheet inside the declarations for the li elements, let's add a
padding property and set the value to *0* for the top and bottom, and
*12* pixels for the left and right:

li {

display: inline;

padding: 0 12px;

}

When we save the changes we made and view the result in the browser, you
will notice that our list elements are now starting to look more like a
navigation menu:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image137.jpg){width="4.926149387576553in"
height="1.0564512248468942in"}

One thing to keep in mind when using inline as the value for the display
property is that top and bottom margins will not have any effect on the
inline elements. For example, if we go back to our style rule for the
list elements and give them a margin of 80 pixels for the top and bottom
and 0 for the left and right:

li {

display: inline;

padding: 0 12px;

margin: 80px 0;

}

When you save the stylesheet and take a look at the browser window, you
will notice that nothing really changes and we don't see those margins:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image137.jpg){width="5.125in"
height="1.099096675415573in"}

If we want to apply margins to our list items, we'll need to use another
display value called *inline-block*. The *inline-block* value generates
a box that's like a block element, but it flows with its surroundings
just like an inline element. In other words, we're getting a combination
of inline and block level display modes. Let's change the display value
for our list elements to inline block:

li {

display: inline-block;

padding: 0 12px;

margin: 80px 0;

}

Then, when we save our stylesheet and refresh the browser, we can see
that the top and bottom margins are now applied to each list item:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image138.jpg){width="5.468201006124234in"
height="1.875in"}

There's a lot more we can do with the display property, but what I would
like to do is to style our two main call out links on the page: the
*Find out more* line and the *See the history* link. So, moving forward,
I'm going to completely delete the styles for the list items that we
added, but you can comment them out if you want to keep the styles for
reference.

We want these links to stand out a little more, and we're going to style
them using padding, border, margin, and display properties that we have
just learned about.

The first thing that we need to do is to apply a class to the links in
our *index.html* file. So, make sure that you have the *index.html* file
open and then scroll down to the first link: *Find out more* -- it
should be on around line 18 and add the class attribute with a value
*callout*:

\<a *class*=\"callout\" *href*=\"\#more\"\>Find out more\</a\>

Make sure to save the *index.html* file, as we will be targeting this
class in the CSS. Then, back in the stylesheet scroll down and just
above the styles for the main footer, add a selector for the *callout*
class. The first thing that we will do is give our links the font-size
property and we want to have a font size that is little bit larger at
*1.25em*. Then we will add a bottom border and some padding along with a
top margin of 20 pixels:

.callout {

font-size: 1.25em;

border-bottom: 3px solid;

padding: 0 9px 3px;

margin-top: 20px;

display: inline-block;

}

All these style declarations should now be familiar to you. I've set the
font size to 1.25em, this is equivalent to 20 pixels. Then I added
border bottom of 3 pixels with a border style of solid. Note that I
didn't add a border color because I want the color to be the same as the
text color of the links. Remember, if we do not specify a text color,
the border will take on the color of the parent container's text color.
Then I have added a padding of *0* for the top, *9* pixels for the left
and right and *3* pixels for the bottom. I've then added a *margin-top*
value to give it a little bit more separation with *20* pixels.

Finally, I added a display property with a value of *inline-block*, as
links are displayed inline by default as I want a top margin to be
applied. Let\'s take a look at our design. Let\'s save our style sheet,
and refresh the browser and there we have our nicely styled callout
links:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image139.jpg){width="5.005020778652669in"
height="1.1330643044619422in"}**\
**

Day Seven 
==========

Basic Layout 
-------------

### Width and height properties 

It's time to see how everything that we have learned so far about the
box model applies to creating a basic layout for our page. By default,
an element's width and height are determined by the content that it
contains. As you have already seen, we can have granular control and we
can set our own dimensions using the width and height properties in CSS.
As you might expect, the width and the height properties can accept
length units such as pixels, ems, or percentages.

We've already learned that using a percentage value for the width means
that the actual width will be relative to the parent element's width.
This is why the primary and secondary divs adjust their width based on
their parent container's width, as we have set their width by using a
percentage value of 60%. By default, the parent container's width is set
to 100%, so this means that both divs will have a width of 60%.

However, pixel values are still very commonly used, as they give us
precise control over the size of an element. If you open the exercise
files for this section, you will see that we have a very large arrow
image in our header. This arrow image is actually embedded as a Scalar
Vector Graphic or SVG:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image140.jpg){width="3.172689195100612in"
height="2.4838713910761157in"}

As you can see, the image is very large and we're going to need to scale
it down with a width property. Before opening the stylesheet, make sure
to open the *index.html* exercise file, and we're going to add a class
to the image element. The image element should be on around line 11 in
the *index.html* file and a class called arrow:

\<img class=\"arrow\" src=\"img/arrow.svg\" alt=\"Down arrow\"\>

Once again, make sure that you save the *index.html* file and then open
up the accompanying stylesheet. We're going to target the arrow class
that we just added. Since our arrow image is too big at the moment, we
want to give a much smaller width. Let's set its width value to 50
pixels:

.arrow {

width: 50px;

}

Now we can save our stylesheet, and go back to the browser window and
refresh the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image141.jpg){width="4.835135608048994in"
height="2.629032152230971in"}

This is much better. Our arrow image is now scaled down to 50 pixels
wide. Next, we're going to increase the height of our main header
element, as at the moment the arrow image is right up close. As you can
guess, we can achieve this using the CSS height property. Back in the
stylesheet, locate the main header style rules and right beneath the
background color property, we're going to add a height property and set
the value to 850 pixels:

.main-header {

background-color: \#ffa949;

height: 850px;

}

Now if we save our stylesheet and refresh the page, we can see that our
header is now taller:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image142.jpg){width="4.884268372703412in"
height="1.5in"}

If you're wondering why we need this much height, it is because we will
be adding a nice background image to the header later on. It's important
to understand that when we define a width or height on an element, we
are not exactly defining the entire area of the box in terms of the
content, padding and borders. The height and the width that we set are
merely setting the content area only. This can create some undesired
effects, especially when building layouts for our pages. To understand
this issue properly, let's look at an example. If we go back into our
main header rule, and add a padding top property and set it to 170
pixels:

.main-header {

background-color: \#ffa949;

height: 850px;

padding-top: 170px;

}

Make sure to save the stylesheet and refresh the browser window. You
will notice that the header height has now increased even further. You
can inspect the header element using the Chrome dev tools by going to
**View** \> **Developer** \> **Developer Tools**, and then use the
magnifying glass tool to highlight the header element. You will see that
the padding top is added to the height of the header element to give us
a total header height of 1020 pixels:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image143.jpg){width="4.625in"
height="2.166505905511811in"}

What is actually happening is that the browser calculates the total
height value of the entire header element by taking the value we define
for the padding top, plus any other padding and border values for the
header, and adding it to the height value. Furthermore, if we added
borders and applied padding on the bottom of the header, the total
height of the element would increase even further. So, when we add
padding and border properties to the element, it increases the height.
The same thing also happens to the total width of an element and this
makes our elements appear wider than they need to be. To see a good
example of this, let's go back into our stylesheet and find the layout
styles for the primary and secondary divs under the section with the
comment *Layout Styles*. Instead of the fluid 60% width, let's set the
width back to *960* pixels, just as we had before:

.primary-content,

.secondary-content {

width: 960px;

margin: auto;

}

Then save the stylesheet and preview in the browser by clicking refresh.
You will now see that our header is exactly 960 pixels wide:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image144.jpg){width="5.116838363954506in"
height="2.625in"}

Let's add some padding to the two divs to give them some separation
between the content and the margins. We're going to add some left and
right padding to the divs, so back in the stylesheet we're going to
apply two properties *padding-left* and *padding-right* and set their
values to 50 pixels:

.primary-content,

.secondary-content {

width: 960px;

margin: auto;

padding-left: 50px;

padding-right: 50px;

}

Save and then preview the changes in the browser using the dev tools.
You will notice that the total width of the two divs has now increased
and is actually 1060 pixels wide in total:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image145.jpg){width="4.5in"
height="2.9754221347331584in"}

The browser has added 100 pixels to the total width of the two divs,
since we applied a padding of 50 pixels to the left and right sides of
each div. So just like the height property, the browser calculates the
total width value by adding any padding and border values that we apply
to the elements to the total width. So, you're probably wondering what
is the solution to all of this? And how do we get the elements to have
the exact width and height we specify?

What we could do instead of applying an individual width and height to
an element is to factor in any padding and borders into the total width
and height that we wish to apply on an element. For example, we can do
some simple math and subtract the padding or border width that we want
to apply on an element from the total width or height that we add.

So, for instance, we could set the width of the primary and secondary
divs width to 860 pixels to factor in the extra 100 pixels of padding
that will be added when we apply a padding property. This works just
fine, however, it becomes a bit tedious if we have to do this for every
element in our layout that has a width, height, or padding and border
width defined. So, if you are thinking there has to be a better way!
Then you're right, there is, it's called box sizing.

### Box-sizing and max-width

Since we don't want to use calculations to compensate for padding, and
border width values, we can use the CSS feature called box sizing. The
box sizing property changes the way the total width and height of an
element are calculated. To see how the box sizing property works, let's
go back to the primary and secondary content rule in our stylesheet and
beneath the width property, we will add the box size property and set
the value to border box:

.primary-content,

.secondary-content {

width: 860px;

box-sizing: border-box;

padding-left: 50px;

padding-right: 50px;

margin: auto;

}

The value border box forces the padding and borders into the width and
height of the element instead of expanding it. Now we can set the width
back to the desired value of 960 pixels and if we save our stylesheet
and refresh the page, you will see that the final width of the rendered
containers is now the actual 960 pixels for each div, even though we
have a padding applied on the left and right side:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image146.jpg){width="4.762187226596676in"
height="3.625in"}

We also want to apply box sizing to all our elements on the page,
including the header element. To apply it to all our elements, we can
use the universal selector and add a box sizing property then set the
value to border box. To do this, make sure you scroll to the top of the
stylesheet and add the following style rule:

\* {

box-sizing: border-box;

}

Now that we have added the box sizing property to every element on the
page, we can go ahead and delete the box sizing property that we
previously added to the primary and secondary divs:

.primary-content,

.secondary-content {

width: 860px;

padding-left: 50px;

padding-right: 50px;

margin: auto;

}

The universal selector will apply the box sizing property to all
elements including the primary and secondary divs. If we save our
stylesheet and look in the browser, you will notice that the header
element no longer adds the extra 170 pixels and the height of our header
is back to 960 pixels. Previously, I mentioned that using the universal
selector is usually considered bad practice. However, this case is an
exception and a good use case. It's good practice to define the box
sizing at the top and target all the elements on the page as we'll have
one less thing to worry about when it comes to laying out our page.

Now that we have the border box property applied to all the elements, we
can set the width of the primary and secondary divs back to a percentage
value. Back in the stylesheet, locate the style rules for the primary
and secondary divs and set the width to 75%:

.primary-content,

.secondary-content {

width: 75%;

padding-left: 50px;

padding-right: 50px;

margin: auto;

}

If we save our stylesheet and check the browser view, we will see that
the primary and secondary divs now both take up three quarters of the
available width:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image147.jpg){width="5.263101487314086in"
height="2.8870964566929134in"}

Now, instead of the 960 pixels, the width of the primary and secondary
divs will constantly adjust to the browser's width, and whatever the
total available width, they will take up 75%. However, we can run into
an issue when our page is viewed on a screen that is very wide. In that
instance, the content will display too wide for good readability. If you
have access to a wide screen display, you can test this yourself. To
prevent this from happening we can use the *max-width* property to limit
the maximum width of our content. Back in the stylesheet, we're going to
add a *max-width* property to our primary and secondary style rule. No
matter how wide the screen, we want to limit the amount of width the
divs take up, and we're going to set the value to 900 pixels:

.primary-content,

.secondary-content {

width: 75%;

padding-left: 50px;

padding-right: 50px;

margin: auto;

max-width: 900px;

}

Unfortunately, you're only going to be able to see how this property
works if you test it on a wide screen. But essentially, what it does is
limit the width of the primary and secondary content to 900 pixels, no
matter how wide the screen is, and the elements stay fixed in their
position at 900 pixels. However, once the browser is resized to a
narrower width, it will take up a width of 75%. The max width property
is used to create responsive images as well. You will have noticed that
the two images on our page at times are too wide for their containing
div elements. For example, when we reduce the width of the browser, the
images break out of their content divs:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image148.jpg){width="4.416434820647419in"
height="4.032258311461067in"}

To prevent this from happening, we can use the max width property again.
Let's create a new style rule that targets the images on our page. Back
in the stylesheet, locate the *h3* rule and directly underneath it, we
will target the image elements by using the *img* type selector and then
add a max width property, then set the width to *100%*:

img {

max-width: 100%;

}

This will make the images become fluid and proportionally adjust
according to the width of the containing div, and you will notice that
the images no longer break out from their containers:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image149.jpg){width="3.75in"
height="3.678614391951006in"}

The max width property is a really handy feature for creating responsive
layouts. Before we wrap up this part, let's give our images a bottom
margin to give it some separation from any content that follows beneath.
So back in the stylesheet and under the max width property, let's add a
margin bottom property and set its value to *20* pixels:

img {

max-width: 100%;

margin-bottom: 20px;

}

Now when we save our stylesheet and look at the browser, we now have a
degree of separation between the images and the content that follows
beneath:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image150.jpg){width="4.435165135608049in"
height="3.375in"}

### Backgrounds: color and images

All elements in HTML have a background layer that is transparent by
default. We can fill this background layer with a color, as we have
already seen. We can also fill the background with an image and CSS
provides us with some useful background properties that we can use for
this purpose. So far, we have used the background color property to
apply background color to elements, and in our header element we have
set the background to have a cool shade of orange color using the
*background-color* property.

As I mentioned previously, we will set the header's background to an
image, and in CSS there is the *background-image* property we can use to
achieve this. So, without further ado, let's open up the stylesheet for
this section and locate the styles for the header element, which should
be on around line 61 in. Then right beneath the height property, we're
going to add a background image property.

Now the value that the background image property can accept is a URL
value, which is essentially the location of the image. If you open the
*img* folder in the exercise files, you will see several images, and the
image that we want to use for the background of the header is the
*main-img.jpeg*. To add the background image to our header element, we
are simply going to use the *background-image* property and set the
value using the URL function. Since our image is in the *img* folder, we
will set the URL location as *img/main.img.jpg*:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'img/main-img.jpg\');

}

The background image property is set using the URL function, so to tell
the browser where to find the image, we put the [URL]{.underline}
location inside the opening and closing parenthesis. We can optionally
enclose the URL path using the double or single quotes. I prefer to use
single quotes -- but they will work exactly the same with double quotes.
Now that we have set the image path as the value for the background
image property, let's save the stylesheet and refresh the browser. You
will notice that we don't see the background image in our main header.

When an image doesn't display like this, it usually means that the file
path for the image is incorrect. That is the case with our background
image. The *img* folder is not relative to our CSS file -- rather our
CSS file is in a separate folder called *CSS*. So, this means that we
have to tell the browser to move outside the *CSS* folder, and then move
into the *img* folder. We can do this by adding two dots and a forward
slash right before the *img* folder:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

}

The two dots tell the browser to move one folder backwards, then start
searching for the image in the *img* folder. Now when we save our
stylesheet, we can immediately see that this path works as we can see
our image:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image151.jpg){width="5.019632545931758in"
height="1.9153226159230097in"}

As you can see, by default, a background image is repeated or tiled both
horizontally and vertically to cover the entire element. CSS provides a
useful background image property that can help us control whether a
background image gets tiled both vertically and horizontally. So back in
the stylesheet, let's add a *background-repeat* property. If we only
want the image to repeat horizontally, we can use the value repeat-x:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: repeat-x;

}

This will set the image to repeat horizontally on the x-axis:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image152.jpg){width="5.096146106736658in"
height="1.7983869203849518in"}

Ideally, we don't want our background images to repeat, and the
background repeat property can also accept a value of no-repeat, which
means that the image will not be repeated either horizontally or
vertically:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: no-repeat;

}

So now if we save the stylesheet and refresh the browser, you will
notice that our background image is no longer repeated:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image153.jpg){width="4.625in"
height="1.9101804461942258in"}

Now that our image is no longer repeated, it is best practice to set a
background color just in case the image is not available for whatever
reason, or the user has disabled images in the browser. For now, though,
we'll keep the orange hexadecimal value as our background color.

### Backgrounds: size and position

By default, a background image's initial position is the top left hand
corner of the containing element, as we can see in the main header:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image153.jpg){width="4.5in"
height="1.8585542432195976in"}

CSS lets us control the background position of an image with the
position property. To see how this works, let's go back to our
stylesheet and in the main header rule after the *background-repeat*
property, we will add a *background-position* property. This property
can accept keywords, length values, and percentage values. The first
value determines the horizontal position. For the first value, we will
use the keyword center, and as you would expect, it centers the image in
the container. The second value sets the vertical position of the image,
however, if we do not specify a second value, the browser will assume
that the second value is also centered. So, if we just use the one value
*center*:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: no-repeat;

background-position: center;

}

So now if we save the stylesheet and refresh the browser, you will
notice that our background image is now centered:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image154.jpg){width="4.518106955380578in"
height="2.375in"}

Go back to our stylesheet, and set the second value to the keyword
*top*:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: no-repeat;

background-position: center top;

}

Once you save the stylesheet, you will notice that our image is now
positioned at the top of the containing div, but still centered
horizontally:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image155.jpg){width="4.661068460192476in"
height="2.370967847769029in"}

We can also set the second value to bottom, and this will position our
image at the bottom of the header and so on. We can also be more
specific when setting the background position, using a length value. For
example, we can use percentages as the values; these will be relative to
the height and width of the background area. So, if we change our
background position value to 20% and 50%:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: no-repeat;

background-position: 20% 50%;

}

When we save our stylesheet and look at the browser, we can see that our
image is now positioned 20% to the left side of the header and it's
still vertically centered:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image156.jpg){width="4.3049146981627295in"
height="2.197580927384077in"}

Now that we have seen how we can apply background positioning on our
image, we want to have it centered right in the middle. So, we will set
both horizontal and vertical values to center:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: no-repeat;

background-position: center center;

}

This positions our background image in the center both horizontally and
vertically:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image154.jpg){width="4.375in"
height="2.299773622047244in"}

You will notice that our background image is not filling the entire
available background area, and we want to have it fill all of the
available area in the background. To fill the entire available
background area, we can use the background size property. The background
size property can accept a length value, percentage, or a keyword. For
our purposes, we want our background image to fill the entire background
and to do this, we can use the keyword value cover:

.main-header {

background-color: \#ffa949;

padding-top: 170px;

height: 850px;

background-image: url(\'../img/main-img.jpg\');

background-repeat: no-repeat;

background-position: center center;

background-size: cover;

}

Setting the value to cover also means that the image will scale
proportionally to the size of the main header if it is resized. So, to
see how our background image now looks, save the stylesheet and refresh
the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image157.jpg){width="5.1641382327209095in"
height="2.625in"}

The background size property with the value cover is a handy feature
which is commonly used for creating full page background images. As we
have already seen, we can use the shorthand notation to specify all our
background values in one declaration. To do this, we're going to add the
property *background* and then set all the values in one go:

.main-header {

padding-top: 170px;

height: 850px;

**background: \#ffa949 url(\'../img/main-img.jpg\') no-repeat center
/cover;**

}

The first value for the background property is the fallback color value.
Then we specify the path of the image that we want to use by adding the
URL location. After the image path, we set the background repeat value
of the image, so we don't want the image to repeat and set the value to
*no-repeat*. Then we specify the background position value. We want the
image to be centered both horizontally and vertically -- so we set the
value to *center*. Then after the background position value, we add a
space and a forward slash to specify the background size value. The
forward slash is there to separate the background position value from
the background size value.

If you want to make the code a little bit more readable, we can set the
background size value on its own line. This is totally optional, but it
makes the code a little easier to read. So, if we remove the forward
slash and the keyword *cover*, then add the background size property on
its own line:

.main-header {

padding-top: 170px;

height: 850px;

**background: \#ffa949 url(\'../img/main-img.jpg\') no-repeat center;**

background-size: cover;

}

So, now when we save our style sheet, and refresh the page, everything
should still look exactly the same:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image157.jpg){width="5.187935258092739in"
height="2.6370964566929134in"}

### Floats 

Understanding the box model components is half the battle when it comes
to positioning elements on the page. As a developer, you need to be able
to layout elements on the page using different techniques. We're going
to learn about the CSS float property and how it can help us to position
elements on the page. Floats are one of the most commonly used methods
for laying out a page with CSS.

When an element is floated, it is taken out of the normal flow of the
page and placed along the left or right side of its container. This will
cause other elements on the page to wrap around the floated element. In
our *index.html* file, the secondary content div contains two nested
divs and each of them contain an image, a heading element, a paragraph
and a list. Currently, the two nested divs appear stacked:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image158.jpg){width="2.3104833770778654in"
height="3.6372014435695537in"}

What we want to do is lay them out side by side in one row, and we're
going to use the float property to help us achieve this. Before we go
into the stylesheet, let's add a class to each of the two nested divs
inside the secondary content container div. We'll add a class called
*resorts* to the first nested div on around line number 31:

**\
**

**\<div class=\"resorts\"\>**

\<img src=\"img/granada-villa.jpg\" alt=\"Resort\"\>

\<h3\>Location and Distances\</h3\>

\<p\>

The Granada region offers Spain\'s richest variety of climate and
landscape, from the...

\</p\>

\<ul\>

\<li\>\<a href=\"\#\"\>Sacromonte\</a\>\</li\>

\<li\>\<a href=\"\#\"\>Albaycin\</a\>\</li\>

\<li\>\<a href=\"\#\"\>The Alhambra\</a\>\</li\>

\</ul\>

\</div\>

Next, we're going to add a class to the second nested div, and we're
going to call this class *tips*:

**\<div class=\"tips\"\>**

\<img src=\"img/granada-puerta-real.jpg\" alt=\"granada\"\>

\<h3\>Be Prepared For Beauty\</h3\>

\<p\>

Granada is situated at the foot of the Sierra Nevada between two
hills....

\</p\>

\<ol\>

\<li\>Great Weather\</li\>

\<li\>Stunning architecture\</li\>

\<li\>Rich history\</li\>

\<li\>Simply breathtaking\</li\>

\</ol\>

\</div\>

Now that we've added the stylesheet, make sure you save the *index.html*
file and then open the stylesheet and scroll all the way to the bottom.
What we're going to do first is target both the *resorts* and *tips*
classes and give them a width of *46.5%:*

.resorts,

.tips {

width: 46.5%;

}

So now when we save our stylesheet and refresh the page, we can see that
each of the two divs now only take up 46.5% of the parent container
width:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image159.jpg){width="4.428779527559055in"
height="2.375in"}

Now that we have set the width for each of the nested divs inside our
secondary content container, we are ready to lay them out side by side
using the CSS float property. As I mentioned already, when an element is
floated, it is removed from the normal flow of the page and as per our
layout currently, the divs are stacked on top of each other vertically.
Now let's add a float to the tips class. Back in the stylesheet, right
below the *resorts* and *tips* rule, create a selector for the *tips*
class, then add *float* property and then set the value to the keyword
*right*:

.tips {

float: right;

}

Then save the stylesheet and refresh the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image160.jpg){width="4.202227690288714in"
height="3.5in"}

You will see from the screenshot above that the div is now positioned
floated to the right side of the containing secondary content div. You
can immediately tell that it has been taken out of the normal flow of
the page, as it is overlapping the footer content. We're going to fix
this problem after floating the second *resorts* div to the left.

The *resorts* div is still taking up an entire line of content, since it
is still in the normal flow of the page. We can make the resorts div
float to the left in the same way that we floated the *tips* div to the
right. Back in the stylesheet, right under the rule for floating the
tips div to the right, add a selector to target the *resorts* div and
set float property value to left:

.resorts {

float: left;

}

Now when we save our stylesheet and refresh the page, you will notice
how the resort *div* is now also taken out of the normal page flow and
placed along the left side of its container with both divs now
positioned on the same line:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image161.jpg){width="4.375in"
height="2.3198042432195973in"}

The secondary content div no longer expands to completely surround the
floated columns, because the browser does not account for the height of
the floated columns. This is because the floated elements are no longer
positioned in the normal flow of the page, and as a result, the content
of the footer is starting to wrap around the two floated divs. We can
fix this issue using what is called a CSS clear fix and we're going to
learn how to do that next.

### Clearing Floats

To fix the issue of overlapping elements around our floated divs, we
need to open up or clear the collapsed space around the floated divs.
So, we want the float container to stretch up and accommodate the float
items. There are a few ways in which we can achieve this.

The first way we can prevent an element from collapsing from floats is
to apply an overflow property and set the value to *hidden* or *auto*.
So, in the stylesheet inside the style rule for the secondary content
div, let's add an overflow property and set the value to auto:

.secondary-content {

padding-top: 80px;

padding-bottom: 70px;

border-bottom: 2px solid \#dfe2e6;

overflow: auto;

}

Once you've added the property, save the stylesheet and refresh the
browser. You will notice that our secondary div no longer collapses:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image162.jpg){width="4.548318022747156in"
height="3.072580927384077in"}

This solution works effectively for clearing floats, but it isn't the
most recommended way, as the overflow property can cause scroll bars to
appear in certain browsers. Using this solution would be sufficient if
we were working on a small project with simple layouts.

However, we have been learning about best practices when it comes to
layout techniques, and we're going to use the best and most reliable
method for clearing floats, which is called clearfix. Make sure to
remove the overflow property from the secondary content rule in our
stylesheet, so the style rule should be back to the following:

.secondary-content {

padding-top: 80px;

padding-bottom: 70px;

border-bottom: 2px solid \#dfe2e6;

}

The clear fix method is a common technique for clearing floats, and as
you get a better understanding of CSS layouts, you will see this
technique being used a lot to clear floated elements on a page. The CSS
code for the clear fix technique is as follows:

.group:after {

content: \"\";

display: table;

clear: both;

}

The above CSS code might look strange to you at first, but there's
really two key parts that you need to understand. *Group* is a common
name, since we're using it to contain a group of elements. What the
clear fix technique does is generate a blank pseudo element right after
the content of our div. This means that we are actually able to generate
content from our CSS. The key to the clear fix is the clear property
with the value both. The value, both, clears any collapsed space created
by floats on both sides of the container.

Now to see how this actually fixes the float issue, we need to add the
class group to the secondary container, since this is the div that is
the parent container for the floated elements. So, open the *index.html*
file and on around line 30, add the class group:

\<div class=\"secondary-content t-border group\"\>

Make sure to save the stylesheet and the index.html file, then refresh
the browser, and you will notice that this fixes the issue with the
floated elements on our page nicely and it forces the secondary content
div to contain our columns without collapsing:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image162.jpg){width="4.125in"
height="2.7866119860017498in"}

Any time we need a containing element cleared, we simply need to give
that element the class *group*. You can use any class name you want for
this clearfix. With floats, we can change the order of our divs without
having to change anything in our HTML file. For example, if we wanted to
reverse the order of our two columns, all we need to do is set the
direction for the *tips* div to left and the *resorts* div to right:

.tips {

float: left;

} x

.resorts {

float: right;

}

When we look at our layout once again, and refresh, notice how the order
of our columns is now reversed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image163.jpg){width="4.761160323709536in"
height="2.75in"}

### Lists

We can control the appearance of list elements on our page using
specific list properties. By default, list elements display certain
browser styles and you would typically see unordered lists displayed as
a bullet or solid dots. Ordered lists are displayed with a number by
default.

As with pretty much anything on our page, we can change this appearance
using CSS. The list elements have several list properties that we can
use to control their appearance. For example, with the list style
property, we can add any type of list marker to either an ordered or
unordered list.

Make sure you have the exercise file open for this section and scroll
down to the end and add a new rule that targets our unordered list using
the *ul* selector. We're going to use the list style property and we're
going to set the value to square:

ul {

list-style: square;

}

Now, when we save our stylesheet and refresh the browser, you will
notice how our unordered list now has square markers:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image164.jpg){width="4.281446850393701in"
height="2.620967847769029in"}

The list style property can accept a range of values from disk, square,
circle, lower roman and lots more. If you want to see all the possible
values for the list type property, you can visit the MDN CSS
documentation here: <https://goo.gl/3Twq3A>

If you don't want to actually have any list style on your unordered
lists, like when creating navigation menu, you can simply assign the
value *none*:

ul {

list-style: none;

}

When you save and refresh the browser, you will see that the list
markers have been removed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image165.jpg){width="3.586299212598425in"
height="2.197580927384077in"}

Going forward, we want to have the default disk style in our design. We
can do the same thing with the ordered list on our page, so simply
change the *ul* selector that we added previously to *ol*, for the
ordered list element. This time, let's set the value to
*decimal-leading-zero*:

ol {

list-style: decimal-leading-zero;

}

So now when we save the stylesheet and refresh the browser, you will
notice how our ordered list items now have a zero before each number:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image166.jpg){width="3.4657874015748034in"
height="2.1370964566929134in"}

We\'re also able to set whether or not we want the list markers to
appear inside or outside the list element box. For example, let's add a
border to all the list items on our page by using the *li* selector and
adding a solid border all round:

li {

border: 1px solid black;

}

Now when we save our stylesheet and look at the browser, it displays the
list markers outside the list items:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image167.jpg){width="5.387096456692913in"
height="1.9601246719160106in"}

We can also control the position of the list style with the list style
position property. So back in the stylesheet, let's target both the
ordered and unordered lists, and we're going to add the
*list-style-position* property with a value of inside:

ul, ol {

list-style-position: inside;

}

Now when we save and look at the layout once again, you will now see
that our list markers are inside the content flow of our list:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image168.jpg){width="4.814694881889764in"
height="1.899194006999125in"}

By default, lists are indented into the page with left padding and are
not aligned with the rest of the content:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image169.jpg){width="4.625in"
height="1.7173797025371829in"}

However, if we wanted to remove the indented space so that our list
items are left aligned with the rest of the content, we can use the left
padding property of the lists and set this to zero. So back in our
stylesheet, we will add a left padding property to our ul and ol
selector and set the value to *0*:

ul, ol {

list-style-position: inside;

padding-left: 0;

}

Save the stylesheet and refresh the browser, notice how the lists are
now left aligned with the rest of the content:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image170.jpg){width="5.120745844269466in"
height="1.8064512248468942in"}

Going forward, we want to keep the default list position declaration and
the default indent on the lists. Also, we want to apply some margin top
and bottom to the lists to give them some separation from the rest of
the content on the page. With that we can go ahead and remove the list
style position and use the shorthand notation for the margins:

ul, ol {

margin: 30px 0;

}

This gives a bit of breathing room to our ordered and unordered lists on
the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image171.jpg){width="5.102119422572178in"
height="1.8951607611548555in"}

We also want to increase the vertical gaps between the list items
themselves, and we can do that inside the *li* selector rule. First,
remove the rule for the border and then add a bottom margin with a value
of *10* pixels:

li {

margin-bottom: 10px;

}

So now when we save our stylesheet, we can see that we have removed the
borders and now there is 10-pixel vertical spacing between each list
item and this looks much better:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image172.jpg){width="5.362915573053368in"
height="1.927419072615923in"}

Fundamental Concepts 
=====================

### The Cascade

As you know, CSS stands for Cascading Style Sheets and I would like to
highlight here the importance of the Cascading. The cascade is what
determines which styles are applied to an element. To understand this
importance, let's say that we give our *h1* element a color of red at
the beginning of our stylesheet file . Then further down the file we
give the same *h1* element a color of green. This means that we now have
two conflicting styles being applied to our *h1* element, so which style
will be applied to the *h1* element?

This is where the Cascade part of CSS comes into play to resolve the
conflict between two or more declarations. The last declaration in our
case, the one that sets the color to green, will be applied to the *h1*
element. The cascade follows three steps to determine which properties
are applied to an element. These are as follows:

1.  Importance

2.  Specificity

3.  Source Order

### Importance 

The first step that the cascade uses is the importance, which is the
origin of the style sheet. The origin of the stylesheet can come from
different sources and one of these sources is the user agent stylesheet.
This is the CSS the browser applies by default, as we learned in the
beginning of the CSS section. Every browser has its own user agent
stylesheet. Another source is the user stylesheet, which contains styles
that have been set by the user. Users can have special predefined styles
that overrides the browser's user agent stylesheet. Special styles are
often used for accessibility for special needs users such as larger font
sizes, specific colors etc. Finally, the third source is the author
stylesheet, and this contains the CSS that we write to style the HTML
page. So, this means that the author stylesheet has more importance than
the user agent and user stylesheets.

### Specificity & Source Order 

The next step that the cascade takes in determining which properties are
applied is the specificity. Specificity is what resolves a lot of the
declaration conflicts in CSS and it decides which styles are applied to
an element. We've already seen that styles with the most specific
selectors override styles with less specific ones. Take a look at the
following HTML & CSS code snippet and try to see which color property
has the most specificity:

**HTML:**

\<**h1** class=\"heading\" id=\"heading\"\>Hello World\</**h1**\> 

**CSS:**

\#heading {

color: red;

}

.heading {

color: green;

}

h1 {

color: blue;

}

As you can see, all the three rules set a color property and they all
have the same importance in the origin. ID selectors have a higher
specificity than element and class selectors, so this means that the
color that is applied to the heading is red. Now, let's look at another
example:

**HTML:**

\<**h1** class=\"heading\" id=\"heading\"\>Hello World\</**h1**\> 

**CSS:**

\#heading {

**color: red;**

**color: gray;**

}

.heading {

color: green;

}

h1 {

color: blue;

}

This time there is a second property declaration that also sets the
color for the heading element. Because there are two color declarations,
only the second declaration will be applied because it has the most
specificity since it comes after the first color declaration. Now, let's
look at an example with an inline style inserted into the HTML markup:

**HTML:**

\<**h1** class=\"heading\" id=\"heading\" **style=\"color:
tomato\"**\>Hello World\</**h1**\> 

**CSS:**

\#heading {

**color: red;**

**color: gray;**

}

.heading {

color: green;

}

h1 {

color: blue;

}

Inline styles are at the lowest level of the cascade, which means that
they have a higher specificity than ID, class, or element selectors.
This means that the inline style color of tomato will be applied. The
last step that the cascade takes in determining what properties are
applied to an element is the source order of the stylesheet. The cascade
assigns a priority number to each CSS style based on the order that they
appear. So, if you're linking two or more stylesheets in the head of
your webpage, the last stylesheet takes precedence over the others. The
role of the cascade is to assign a priority to each style declaration
after considering its importance, specificity, and source order. Then,
based on this priority it determines which style declarations are
applied to an element. Understanding how the cascade works will save you
a lot of time when it comes to style rules not working as expected in
your projects.

Conclusion 
===========

Thanks for sticking around until the end, that was an epic journey! We
went from zero to a professionally designed landing page in a short
time. As I mentioned at the beginning of the CSS section, you don't have
to memorize every single CSS property and value but rather you need to
have access to the excellent MDN CSS documentation.

The landing page that we created is a typical example of what a Front
End Web Developer might do as part of his or her tasks for a day. Now
that you have created this landing page, you can pat yourself on the
back and show it off to friends and family!

**Please leave a review**

If you have enjoyed reading this book, then I would kindly like to ask
you to leave a review, to let others know -- it will only take you a few
minutes, and I will be forever grateful! Here's the link to leave a
review:

[Amazon](https://www.amazon.com/HTML-Week-Less-Abdi-Cagarweyne-ebook/dp/B06XBMDHGM/ref=sr_1_1?ie=UTF8&qid=1488804061)
