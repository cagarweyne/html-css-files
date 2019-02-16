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

Exercise File: css-section/1-getting-started-with-CSS/
1-inline-and-internal-styles/start

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

```html 
<body style="background-color: orange;">
```

In the *index.html,* I've given the body element a *style* attribute,
then inside the quotation, I've added the property that I want to style,
which is the background using *background-color* followed by a colon and
a space, then the word *orange* and a semicolon.

Now, when we save our HTML file and switch over to the browser and
refresh the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image45.jpg)

We can see how this makes the background color of our page orange. We
can add styling to any element using the inline method. Let's add some
styling to the h1 element. We're going to do the same thing as we did
with the body element, and that is to add a style attribute and make the
color of the text white:

```html 
\<h1 style="color: white;">Granada, Spain\</h1>
```

When we save our index.html file, and refresh the browser preview, we
see how the main heading text changes to the color white:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image46.jpg)

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

```html
<head>

<title>Granada\</title>

<style\>

</style>
```
```html
<head>

This time we\'re going to style the paragraph by making the font size
bigger. Here's how we can do that:

<style>

p {
font-size: 20px;
}

</style>
```

So, in between the style tag, I have targeted all paragraphs by writing
*p*, then followed by a set of curly braces. I created little space by
hitting the tab key, then I've specified the property that I wish to
style, which is the font size, by using font-size, followed by a colon
and a space, then I've written 20 px and a semicolon.

The *px* stands for pixels, and this will be explained in more detail
later on. If we now save our changes and switch back to the browser
preview, we will see that our text is now slightly bigger:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image47.jpg)

If we go back into our style tag and this time let's make the font
weight slightly bolder, and you can probably guess which property we can
use to make this happen using CSS. We can apply multiple styles to a
single element inside the curly braces. To do that, I'm simply going to
hit Return or, Enter, and right below what we just wrote, I\'m going to
write *font-weight*, followed by a colon and a space, then the word
bold, and a semicolon:

```html
<style>
p {
font-size: 20px;

font-weight: bold;

}
</style>
```

We've already used a couple of CSS properties, values and syntax without
explaining them. Don\'t worry about these properties for now, we\'ll
cover a lot of that throughout this section. Just know that the styles
inside these curly, braces will increase the paragraph\'s text size and
make it bold. So, let\'s save our changes and take a look at it in the
browser, then in the browser preview, click the refresh button to see
the changes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image48.jpg)

You will immediately notice how the text in our paragraph is now larger
and bold. Let's do the same for our headings. So, let's go back to our
html file, and underneath the styling for the paragraph and the last
curly brace, we\'re going to style the h1 element in our page by writing
h1, followed by a space and a set of curly braces. Then, inside the
curly, braces we\'re going to write font-size followed by colon, a
space, then we're going to write 90px and a semicolon:

```html
<style>
p {
font-size: 20px;
font-weight: bold;
}

h1 {
font-size: 90px;
}
</style>
```

To see the changes, as usual save and then preview in the browser by
clicking refresh. You will see that we have a pretty large heading on
the page:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image49.jpg)

Now that the font size is bigger, let's change the text color to
firebrick red. We can easily change this by going into the h1 selector
and adding a color property followed by the color keyword firebrick:

```html
<style>
p {
font-size: 20px;
font-weight: bold;
}

h1 {
font-size: 90px;
color: firebrick;
}
</style>
```

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

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image50.jpg)

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

```html
<style>
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
</style>
```

As usual we will save the file and then preview the changes in the
browser by clicking the refresh button:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image51.jpg)

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

```html
<head>
<title>Granada\</title>
<link rel="stylesheet" href="css/style.css" />
</head>
```
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

```html
body {

text-align: center;

}

h1 {

font-size: 72px;

color: white;

}
```

Next, let\'s give our header an orange background color:

```html
header {
background-color: orange;
}
```

And finally, let\'s add styles to our paragraph and make a font size of
*20* pixels:

```html
p {
font-size: 20px;
}
```

Don\'t worry if you\'re not sure what these styles mean right now, we'll
cover everything in detail very soon. The important thing here is that
you understand the concept of separating content from presentation.

Let's save the stylesheet, and before going to the browser and
refreshing, we need to remove the internal styles from the *index.html*
page. So, go into the *index.html* file and remove all the styling from
the opening style tag to the closing tag itself and delete. Then save
the file and preview the changes in the browser by clicking refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image52.jpg)

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

```html
<head>
<title>Granada</title>
<link rel="stylesheet" href="css/style.css">
<style>
</style>

</head>
``` 

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
