# Intro to selectors 

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

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image56.jpg)

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

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image57.jpg)

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

```css
* {

}
```

Inside these curly braces is where we\'ll write the styles we\'d like to
apply universally to our page. Let\'s write our first declaration.
We\'re going to use the margin property and we'll set it to zero, we're
also going to set the padding of each element in our web page to 0, and
finally we'll add a color property and set that to red to really make
things stand out. Here's how our CSS code should look like:

```css
{
margin: 0;
padding: 0;
color: red;
}
```

This universal selector we just wrote will apply these styles to every
element in our project. So, let\'s take a look at the results. First
save the stylesheet and then refresh the page in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image58.jpg)

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

```css
p {
color: white;
background-color: lightblue;
}
```

So, if we save our style sheet and refresh our preview:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image59.jpg)

We can see how the selector targets every paragraph on the page and
applies the styles we defined. Like we did previously, if we want to
target the header element and change its background color, we can target
the header element by writing *header* as our selector. Let's make the
header\'s background orange:

```css
header {
background-color: orange;
}
```

Let's save the stylesheet and refresh our view in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image60.jpg)

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

```css
h1 {
font-size: 90px;
color: white;
}
```

Then below our *h1* rule, we\'ll use another type selector to target the
*h2* elements on the page. I'm going to set the *h2* font-size to 53
pixels.

```css
h2 {
font-size: 53px;
}
```

Then right below our *h2* rule, I'm going to target the *h3* headings on
the page and set their font-sizes to 20 pixels. I will also add a color
property value to the *h3* style to make it a lighter shade of black.
For this, I will use a hexadecimal as the value for the color property:

```css
h3 {
font-size: 20px;
color: #48525c;
}
```

When using hexadecimal values, you need to prepend a pound (or hash)
symbol in front of the value as you can see in the above style rule.
Finally, I'm also going to style the body of the page by targeting the
*body* element. Since the *body* element comes right at the top of the
page, I'm going to place this rule right at the top of the stylesheet.
This is just a matter of preference, to keep things nicely grouped and
organized in reference to our HTML document. I'm going to set the *body*
color to gray, and again for this, I will make use of another
hexadecimal value and add a margin with a value of 0:

```css
body {
color: #878787;
margin: 0;
}
```

What the above style does is set the universal color of the text for all
elements on the page to a nice shade of gray. Let\'s go ahead and save
our style sheet, and then switch over to our browser preview:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image61.jpg)

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

```css
#primary-content {

}
```

Then we\'ll follow the selector with our declaration block. I'm going to
create a border around the primary content by giving it a border size of
2px, a solid border and a color of red:

```css
#primary-content {
border: 2px solid red;
}
```

This ID selector we just wrote will match the html element that has an
ID attribute with the value primary-content. So, if we save our style
sheet and switch to the browser preview, when we refresh the page we
don\'t see that red border anywhere on the page just yet:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image62.jpg)

As you start out creating web pages with CSS you often find yourself in
situations like this, this is perfectly normal. The reason the border is
not showing is because we still need to assign the ID of
*primary-content* to an HTML element. So. let\'s go over to our
*index.html* file and we\'re going to give the first div element the ID
of *primary-content*. It should be on around line 12. We'll add an ID
attribute, then inside the quotation marks, we\'re going to write
primary-content:

```html
<div id="primary-content">
```  

The ID names are up to us, but it\'s usually good practice to give them
meaningful names that explain what they do, and what their purpose is.
This div contains the main content on the page and we are giving it the
ID name *primary-content*, which indicates that very clearly. Let's save
our index.html file and take a look at it again in the browser preview
and refresh the screen:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image63.jpg)

As you can see from the screenshot, there\'s a red border around the
primary content div element on the page. IDs are unique to the page so
it's important to remember that an element can only have one ID and a
page can only have one element with the same ID name.

Also, because our div already has an ID applied, we can no longer add
IDs to it and we cannot use this *primary-content* ID anywhere else in
this particular HTML file. IDs also have a browser functionality,
meaning that they can be used as what are called fragment identifiers
for creating landmarks or anchors in pages as we have seen when we were
creating HTML link tags. In the footer element, let's give the footer an
ID of *main-footer*. So, in the opening footer tag, we\'re going to add
an ID attribute, and we\'re going to make the id value *main-footer*.

```html
<footer id="main-footer">
```

Make sure to save the *index.html* file, and then switch over to our
style sheet. We\'ll target the main footer element with an ID selector,
right below the *primary-content* selector we wrote earlier. First
we\'re going to give it a *padding-top* with a value of 60 pixels and a
*padding-bottom* also with a value of 60 pixels. Finally, we're going to
give the footer a border on the bottom only, which will be 10 pixels and
the color orange:

```css
#main-footer {
padding-top: 60px;
padding-bottom: 60px;
border-bottom: solid 10px orange;
}
```

Let's now save our stylesheet and then switch over to the browser view
and click on refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image64.jpg)

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

```css
.primary-content {
border: 2px solid red;
}
```

So now our selector is a class and if we save our style sheet and take a
look at it in the browser preview, we can see that the red border is no
longer there:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image65.jpg)

That's because class selectors only target elements with a matching
class attribute. So, we\'ll need to go back to our HTML file and change
the ID attribute to a class instead on around line 12:

```html
<div class="primary-content">
```  

Classes let us target more than one element with the same class name. In
fact, that\'s one of the biggest advantages to using class selectors.
Multiple elements can share the same class and we're able to reuse them
throughout a page. Remember, we\'re not allowed to do that with IDs. Now
if we save the index.html file and refresh the browser, we should now
see the red border again around the primary content div:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image66.jpg)

So, if we give another element in our HTML file the class primary
content, we should also see the red border applied to that element.
Let's give the next div on around line 27 the same primary content
class:

```html
<div class="primary-content">
  
<h3>Location and Distances</h3>
```

When we save our `index.html` file and refresh the page, we see that
both divs now have that red border applied:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image67.jpg)

Like with IDs, naming the class is up to us and we should also give them
meaningful names that explain their purpose. So, let\'s go back to our
HTML file and add a few more class attributes.

But first, instead of giving the div on line 27 the class primary
content in the *index.html* file, let\'s rename it to secondary content
because that\'s what it actually contains:

```html
<div class="secondary-content">
```  

Next, let's scroll up and give our header element the class main
header. We could just continue using the header type selector we wrote
earlier to target the *header* element, but let\'s instead give it the
class name *main-header,* because again we\'ll want to give it a
meaningful class name. We know that this will always be the main header
on our page or website, as this main header class communicates that very
clearly.

```html
<header class="main-header">
```  

So, let\'s save our *index.html* file and go back to our style sheet,
and target these new classes. First, we\'re going to change the header
type selector to match that main header class. So, scroll up to where we
declared our header, it should be on around line 6. Then replace the
word *header* with a dot and *main-header*:

```csss
.main-header {
background-color: orange;
}
```

So, if we save our style sheet and take a look at it once again in the
browser preview, we can see that nothing really changes:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image68.jpg)

The header styles are still the same. We\'re just targeting with a class
selector instead of using a type selector. Next, let's remove that red
border around the primary content div, as it\'s not part of our actual
site design. Make sure that you are on the styles for the primary
content class, which should be on around line 24 and instead of the red
border, we're going to center align all of the text.

To do that, we can write text-align and set the value to center:

```css
.primary-content {
text-align: center;
}
```

So, now when we save our CSS file and take a look at it in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image69.jpg)

We can see how that center aligns our text nicely inside that primary
content div. Let\'s also target that secondary content class we wrote
earlier by adding a nice border around it. So, in our style sheet, right
below the primary content rule, we\'re going to create a style rule for
the secondary content div by writing a dot followed by
secondary-content. Then we\'re going to add a border top style
declaration. We're going to make a smooth gray color:

```css
.secondary-content {
border-top: 2px solid lightgray;
}
```

Now even though we don\'t know exactly what this declaration does, just
yet, you can probably tell what\'s about to happen here. Many CSS
declarations like this can be understood at first glance. If you think
this class selector is going to give the secondary content div a solid
lightgray top border, then you\'re on the right track! So, let\'s take a
look. We\'ll save our *style.css* file and when we refresh the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image70.jpg)

That's exactly what happens. There's that light gray solid border
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

```csss
.t-border {
border-top: 2px solid lightgray;
}
```

Then all we have to do is save our stylesheet and then in our HTML file,
we can add the t-border class to the primary and content div as well as
the footer. To add the class to the primary content div, we simply add a
space right after the primary-content value and then we'll write
*t-border* -- make sure there is a space between the classes like this:

```css
<div class="primary-content t-border">
```

We then repeat this process for the secondary content div:

```css
<div class="secondary-content t-border">
```

Finally, we also need to add the class to the footer element, but you
will notice that the footer does not have a class attribute, so we need
to first add the class attribute and then make the value *t-border*:

```html
<footer class="t-border" id="main-footer">
```  

Now that we've added the classes to the elements, let's save our
*index.html* file and then switch over to the browser and then hit the
refresh button:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image71.jpg)

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

```css
header span {
color: white;
font-size: 26px;
}
```

Now, let's save our stylesheet and preview the changes in the browser by
clicking refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image72.jpg)

You will notice that the styles we added to the descendent selector are
applied to the span element inside the header. The great thing about
descendent selectors is that they are not limited to type selectors. We
can also create descendent selectors with classes and IDs and this lets
us get very specific. So instead of using the header element in the
descendent selector, we can also use the class name on the header
element, which is *main-header*. So, once we swap the header for the
class name, this is how the style rule should look like:

```css
.main-header span {
color: white;
font-size: 26px;
}
```

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

```css
ul li {
background-color: tomato;
}
```

The above descendent selector targets every unordered list element on
our page and gives it a background color of tomato. Save your changes in
the stylesheet then head over to the browser and refresh:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image73.jpg)

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

```html
<span class="title">Visit the ancient and beautiful city of
Granada</span>
```

Then inside our stylesheet, we'll replace the descendent selector with
our class:

```css
.title {
color: white;
font-size: 26px;
}
```

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

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image74.jpg)

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

```css
a:link {
color: orange;
}
```

In the above style rule, we are giving all the un-visited links on our
web page the color orange. So, if we save the style sheet and go back to
the browser view and refresh, we can see that all of our links now have
the color orange instead of red:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image75.jpg)

It's important to note that the link pseudo-class only works on anchor
elements that have a *href* attribute, so if an anchor element does not
have the href attribute, then the styles will not be applied. You will
notice that when we click on any of the links and go back to the page,
you will see that the color of the clicked link takes on the default
browser style of purple:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image76.jpg)

We can also change this color to anything that we want using the visited
pseudo class of the anchor element. We will add the visited pseudo class
beneath the link pseudo class and we'll set the visited link color to
lightblue:

```css
a:visited {
color: lightblue;
}
```

We apply the pseudo class in pretty much the same way as before, only
this time we are adding the pseudo class visited and applying the color
lightblue for visited links. Now when you click on any of the links, it
immediately takes on the style that we specified:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image77.jpg)

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

```css
a:hover {
background-color: forestgreen;
color: white;
}
```

So, whenever the user hovers over any link on our web page, it will give
the link element a background color of forest green and a color of
white. To see how this looks, save the stylesheet then switch to the
browser, refresh the page and make sure to hover over a link:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image78.jpg)

As you can see from the image above, whenever we hover over a link
element, it will apply a background color of forest green and a color of
white for the text. What's interesting about the hover pseudo class is
that you can apply it to any element that you wish. To see how this
works, we can change the anchor element tag to a *p* tag like so:

```css
p:hover {
background-color: forestgreen;
color: white;
}
```

So now if we save the changes in our stylesheet and switch back to the
browser and do exactly what we did before with the anchor element:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image79.jpg)

The hover pseudo class is now being applied to all the paragraph
elements on hover. The hover pseudo class is really useful when you want
to apply a particular styling to an element when they hover their mouse
over it. Make sure to change the element back to the *a* tag again
before moving on.

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

Styling to add pseudo class for unvisited links

```css
a:link {
color: orange;
}
```

Changes the visited links color to lightblue
```css
a:visited {
color: lightblue;
}
```
Hover styles for links
```css
a:hover {
background-color: forestgreen;
color: white;
}
```

It's worth keeping in mind that if you leave out a forward slash, all of
the following styles below will be commented out until you add another
forward slash. So ,make sure all comments slashes match up. Also, if you
are using a code editor like Atom or Sublime, then you can use the
keyboard shortcuts provided to add comments to your style sheet. For
example, you can highlight the text that you want to comment out then
simply hold the command key followed by a forward slash for MAC users
and the Ctrl key followed by the forward slash for Windows users.
