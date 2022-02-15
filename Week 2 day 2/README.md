# Learning Objectives Week 2 Day 2

- Fonts
- Flex
    -(briefly) @media query [just know it exists]
- Grid
- Flexbox
- id/class selectors
- parent/child selectors
- justify content
- align content

# Review yesterday

we spoke briefly on id/class and worked with borders, shapes, etc.

# Fonts

Google fonts is the most popular font generator, but any generator will work the same

font-size
font-weight
 - font size and weight are affected by em and rem values
font-style
font-family 
    Show some examples here
text-decoration


# Flex

<code> display:flex;</code>

Flex is the most basic form of reactive and responsive websites.
Flex display adjusts based on the size of the browser window

# Grid

Grid allows for easily adjusting your page with custom layouts
Grid is responsive and does not require absolute sizing in CSS

# Flexbox

Flexbox is a way of stacking and moving around elements within a container
Flexbox also gives your website responsive characteristics, easily allowing for transition from traditional desktop sites to mobile sites

# Parent/Child selectors

Parent child selectors allows for your CSS to be more accurate and more scalable 

syntax for this is:

<code> parentName > childName {
    KEY : VALUE
} </code>

Example, I want to select all <li> elements are are part of an <ol> section, I would write

<code>ol > li {
    key:value;
} </code>
This example would only target ORDERED list elements, leaving unordered lists alone

this combination also works when selecting class/id selectors in parent/child relationships

# Setting your content within the element

When you want to set your content's placement, there are a few ways to accomplish this

You can justify content, which sets the content from left to right
Or you can align content, which sets the content from top to bottom

example
<code>
div > p.sidebar {
    justify-content: right;
    align-content: bottom;
} </code>
This selector is only going to target paragraph elements within div elements that have the class of "sidebar". Using this type of selector can often be just as effective as targeting CSS elements with an id attribute
