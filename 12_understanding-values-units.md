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

```css
.main-header {
background-color: orange;
width: 960px;
}
```

With this pixel value, the header will always take up 960 pixels of the
screen. Let's save our stylesheet and go back to the browser and refresh
the page to view how this looks:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image80.jpg)

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

```css
.main-header {
background-color: orange;
width: 50%;
}
```

When we save this and view the result in the browser, you will notice
that our header is only taking up half of the width of the page --
regardless if we resize the window or not, it will always take up half
the width:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image81.jpg)

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

```css
.primary-content,
.secondary-content {
width: 60%;
}
```

Now when we save our style sheet and switch to the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image82.jpg)

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

```css
.title {
color: white;
font-size: 3em;
}
```

You will notice that the size of the title has increased. This is
because the value *3em* is making it three times that body font size
context:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image83.jpg)

At the moment, the size of the font size is 48 in pixels because the
value from which the em is getting its size from is 16 pixels. So, if we
add a font size to the body element and set this to *0.5em*, let' see
what happens to the size of our title:

```css
body {
color: \#878787;
margin: 0;
font-size: 0.5em;
}
```

When we refresh the browser, we can see that this has changed the size
of the text again:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image84.jpg)

You'll notice that the size of the title has now decreased. The title's
font size value is now relative to the smaller font size of the body,
and therefore the title size now looks smaller. Going forward, we want
to keep the body context font size 1em, so make sure you change that to
1em as the font size:

```css
body {
font-size: 1em;
}
```

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

```css
.title {
color: white;
font-size: 1.625em;
}
```

Now when we save our stylesheet and take a look at our page, we can see
that the title is now exactly the size that we want it to be:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image85.jpg)

We now have a simple formula for converting pixel values to ems, so we
can now define our *h1* element font sizes as ems instead of pixels. The
h1 element's font size is currently set to 90 pixels, and to get the
equivalent em value, we just need to divide it by 16 which gives us an
em based value of 5.625em. So now all we need to do is to change the
current font size from 90 pixels to 5.625em:

```css
h1 {
font-size: 5.625em;
color: white;
}
```

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

```css
.main-header {
background-color:
orange; width: 100%;
font-size: 2em;
}
```

This means that the main header font size of 2em becomes the new context
for our title and heading font sizes, because the main header (or the
div with class main header) is the parent element of both the title and
the *h1* element. Now that we have set the font size for the main header
class, let's save our stylesheet and switch to the browser to see if
anything has changed:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image86.jpg)

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

```css
.title {
color: white;
font-size: 1.625rem;
}
```

Let's also change the h1 element from using the em unit to the rem unit:

```css
h1 {
font-size: 5.625rem;
color: white;
}
```

So, if we save our stylesheet and switch to the browser, we should see
how this affects our elements:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image87.jpg)

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

```css
.main-header {
background-color: \#ff0033;
width: 100%;
}
```

Then save the stylesheet and view the header background in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image88.jpg)

As you can see from the screenshot above, the hex value that we used
turned the background color red. We're also able to use three-digit
notation where the hex values are abbreviated. We can do this if each of
the red, green and blue hex pairs are the same. This means that we can
shorten the current hex value and abbreviate each color using just one
character instead of two identical characters:

```css
.main-header {
background-color: \#f03;
width: 100%;
}
```

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

```css
.main-header {
background-color: #ffa949;
width: 100%;
}
```

We're also going to give our main footer border the same hex value and
replace the orange keyword color:

```css
#main-footer {
padding-top: 60px;
padding-bottom: 60px;
border-bottom: solid 10px #ffa949;
}
```

Now save the stylesheet and switch over to the browser to view how the
footer border bottom color looks like:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image89.jpg)

The final method for applying color values uses what's called a
functional notation to specify the colors. To see this in action, let's
define our link colors with an RGB function. To create the RGB value,
we're going to type the letters *rgb* followed by a set of parenthesis,
and inside these parenthesis, we will write the numbers to represent
each of the color values separated by a comma:

```css
a:link {
color: rgb(255, 169, 73);
}
```

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

```css
a:hover {
color: rgb(255, 169, 73, 0.4);
}
```

Now let's save our stylesheet and preview the result in the browser. We
can see that the links are now transparent when you hover over them:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image90.jpg)

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

```css
.primary-content, .main-header {
text-align: center;
}
```

Now, when we save the stylesheet and refresh the browser, we see that
the text inside the header is now center aligned:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image91.jpg)

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

```css
h1 {
font-size: 5.625rem; /* 90px / 16px */
color: rgba(255, 255, 255, .5);
text-transform: uppercase;
}
```

Let's save our style sheet, refresh our browser, and then we can clearly
see the way in which the value transforms the text into uppercase
letters, despite the fact that we didn't input it directly through the
keyboard in the HTML:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image92.jpg)

We could likewise utilize the values *lowercase* and *capitalize*. Now,
simply go ahead and attempt those, so that you can see what they do.
Also, we can make use of *the text-decoration* property to set the
elements' line decoration, and we'll just make use of this property for
the removal of the underlines from the links. For instance, let's head
toward our CSS file and scroll down to where our link styles are, and
try to give our links rule a *text-decoration* property. Write
*text-decoration*, and then set the value to the keyword *none*.

```css
a:link {
color: rgb(255, 169, 73);
text-decoration: none;
}
```

Now, once our style sheet is saved, we can refresh the browser. We
should be able to see the way in which the underlines in our links have
now disappeared.

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image93.jpg)

However, we can likewise utilize the text-decoration property on just
about any of the elements. So, for example, let's scroll up to where we
have our *h2* rule, and beneath the font size declaration, let's include
a *text-decoration* property, and now we will set the value to
*underline*:

```css
h2 {
font-size: 53px;
text-decoration: underline;
}
```

Let's save this and we should be able to see the way the underline is
included beneath the heading text:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image94.jpg)

The *font-weight* property gives us a chance to set the weight style of
our text-content. By default, all the headings are set to the bold
style. Now, if we give them a *font-weight* property, and set the value
to the *normal* style, this will remove the bold style from the heading.
To do this, let's go back to our stylesheet and locate the style for our
*h1* rule. We will include a *font-weight* property and then we'll set
the value to *normal*:

```css
h1 {

font-size: 5.625rem; /* 90px / 16px */
color: rgba(255, 255, 255, .5);
text-transform: uppercase;
font-weight: normal;
}
```

I'll go ahead and copy the font property declaration we just typed and
then paste it right beneath, in the h2 rule after text decoration
property:

```css
h2 {
font-size: 53px;
text-decoration: underline;
font-weight: normal;
}
```

Now, when we save our stylesheet and refresh the browser, we can see
that the two headings are no longer bold:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image95.jpg)

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

```css
body {
color: #878787; margin: 0;
font-size: 1em; /* 16px */
font-family: sans-serif;
}
```

Now, we can save our stylesheet, refresh our page, and then we can see
that all the page content has changed to the *sans-serif* font:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image96.jpg)

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

```css
body {
color: \#878787; margin: 0;
font-size: 1em; /* 16px */
font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```

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

```css
body {
color: #878787;
margin: 0;
font-size: 1em; /* 16px */
font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
font-style: italic;
}
```

To see how this affects our content, let's save our stylesheet and
refresh the browser -- we should see that all the text content on the
page is italicized:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image97.jpg)

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

```css
body {
color: \#878787;
margin: 0;
font-size: 1em; /* 16px */
line-height: 1.5;
font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```

Let' save our stylesheet and see how this looks in the browser:

![](https://raw.githubusercontent.com/cagarweyne/html-css-files/master/images/media/image98.jpg)

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

```css
h1 {
font-size: 5.625rem; /* 90px/16px */
color: rgba(255, 255, 255, 1);
text-transform: uppercase;
font-weight: normal;
line-height: 1.3;
}
```
We can now save our style sheet and refresh the browser and we will see
the how it reduces the line spacing that is around our h1. Finally, CSS
allows us to write a shorthand property, which allows us to compose all
the font properties right in one value. So, for instance, in the body
rule, if we choose to define the font-weight, line-height, font-family,
and font-size at once, we should be able to ensure it is given the
property *font*, and then all the values can be listed:

```css
body {
color: #878787;
margin: 0;
font: 1em/1.5 "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```

When we use the font shorthand property, it's relatively essential to
recall that the font-family and the font-size must be defined. If they
are left out, the browser ignores the whole line, and the order of the
value is also important. If a font weight or font style value is
utilized, they must be defined before the value of the font size.
Lastly, the font family should be the last value defined. So, if you go
ahead and save the stylesheet and refresh the browser, it should look
exactly as it did before.
