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
