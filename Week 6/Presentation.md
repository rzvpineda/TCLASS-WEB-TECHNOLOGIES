# WEB TECHNOLOGIES

# Week 5 – Introduction to CSS

**Instructor:** [Your Name]

**Course:** Web Technologies

**Semester:** [Semester / Academic Year]

---

# Learning Objectives

At the end of this lesson, you should be able to:

- Explain the purpose of CSS.
- Write basic CSS rules.
- Differentiate Inline, Internal, and External CSS.
- Apply basic text and background styling.
- Apply borders, margins, and padding.

---

# Review

Previously, we learned **HTML**.

HTML provides the **structure** of a webpage.

Examples:

- Headings
- Paragraphs
- Images
- Tables
- Forms

CSS is responsible for the **appearance** of these elements.

---

# HTML vs CSS

| HTML | CSS |
|------|------|
| Creates webpage structure | Styles webpage appearance |
| Defines content | Defines presentation |
| Uses HTML tags | Uses CSS rules |
| Required for webpages | Optional but recommended |

---

# What is CSS?

CSS stands for **Cascading Style Sheets**.

CSS controls how HTML elements are displayed.

Examples:

- Colors
- Fonts
- Backgrounds
- Borders
- Spacing
- Layout

---

# CSS Syntax

Every CSS rule has two parts:

- Selector
- Declaration

The declaration consists of:

- Property
- Value

Example:

```css
h1 {
    color: blue;
}
```

| Part | Description |
|------|-------------|
| h1 | Selector |
| color | Property |
| blue | Value |

---

# CSS Rule Structure

Example

```css
h1 {
    color: blue;
    font-size: 30px;
    text-align: center;
}
```

---

# CSS Comments

Comments are ignored by the browser.

They are used to explain sections of your stylesheet.

Example

```css
/* Main Heading */

h1{
    color:blue;
}
```

---

# CSS Selectors

Selectors determine which HTML elements will receive a style.

Common selectors:

- Element Selector
- ID Selector
- Class Selector
- Universal Selector

---

# Element Selector

Targets **all elements of the same type**.

Example

```css
p{
    color:red;
}
```

HTML

```html
<p>First Paragraph</p>

<p>Second Paragraph</p>

<p>Third Paragraph</p>
```

Result

All paragraph text becomes **red**.

---

# ID Selector

Targets **one unique element**.

Uses the **#** symbol.

Example

```css
#header{
    color:blue;
}
```

HTML

```html
<h1 id="header">Welcome to My Website</h1>
```

Result

Only the heading with **id="header"** becomes blue.

> One ID should only be used once on a webpage.

---

# Class Selector

Targets **multiple elements**.

Uses the **.** symbol.

Example

```css
.student{
    color:green;
}
```

HTML

```html
<p class="student">Juan</p>

<p class="student">Maria</p>

<p class="student">Jose</p>
```

Result

All elements with the **student** class become green.

---

# Universal Selector

Targets **every element** on the webpage.

Example

```css
*{
    font-family:Arial;
}
```

Result

Every element uses the Arial font.

---

# Three Ways to Apply CSS

CSS can be applied using:

- Inline CSS
- Internal CSS
- External CSS

---

# Inline CSS

CSS is written directly inside an HTML tag.

Example

```html
<h1 style="color:blue;">
    Welcome
</h1>
```

Advantages

- Quick testing
- Good for small changes

Disadvantages

- Difficult to maintain
- Repetitive

---

# Internal CSS

CSS is written inside the **style** tag in the HTML document.

Example

```html
<head>

<style>

h1{
    color:blue;
}

</style>

</head>
```

Advantages

- Good for single-page websites

Disadvantages

- Cannot be reused across multiple pages

---

# External CSS

CSS is stored in a separate file.

HTML

```html
<head>

<link rel="stylesheet" href="style.css">

</head>
```

style.css

```css
h1{
    color:blue;
}
```

Advantages

- Reusable
- Cleaner code
- Easier maintenance
- Used in professional web development

---

# Common CSS Properties

Frequently used properties include:

- color
- background-color
- font-family
- font-size
- font-weight
- text-align
- border
- margin
- padding
- width
- height

---

# Text Color

Changes the color of text.

Example

```css
h1{
    color:blue;
}
```

Other values

```css
color:red;

color:green;

color:black;

color:white;
```

---

# Background Color

Changes the background color of an element.

Example

```css
body{
    background-color:lightgray;
}
```

Other values

```css
background-color:yellow;

background-color:lightblue;

background-color:black;
```

---

# Font Family

Changes the font style.

Example

```css
body{
    font-family:Arial;
}
```

Common fonts

- Arial
- Verdana
- Times New Roman
- Georgia
- Courier New

---

# Font Size

Changes the size of text.

Example

```css
h1{
    font-size:30px;
}
```

Common values

```css
12px

16px

20px

24px

30px
```

---

# Font Weight

Changes text thickness.

Example

```css
h1{
    font-weight:bold;
}
```

Common values

- normal
- bold
- lighter

---

# Text Alignment

Controls horizontal alignment.

Example

```css
h1{
    text-align:center;
}
```

Possible values

- left
- center
- right
- justify

---

# Borders

Borders surround HTML elements.

Example

```css
div{

border:2px solid black;

}
```

Other examples

```css
border:3px dashed blue;

border:5px dotted red;

border:4px double green;
```

---

# Margin

Margin creates space **outside** an element.

Example

```css
div{

margin:20px;

}
```

Individual margins

```css
margin-top:20px;

margin-bottom:20px;

margin-left:10px;

margin-right:10px;
```

---

# Padding

Padding creates space **inside** an element.

Example

```css
div{

padding:20px;

}
```

Individual padding

```css
padding-top:20px;

padding-bottom:20px;

padding-left:10px;

padding-right:10px;
```

---

# Margin vs Padding

| Margin | Padding |
|---------|----------|
| Outside the border | Inside the border |
| Creates space between elements | Creates space inside an element |
| Pushes elements apart | Pushes content away from the border |

---

---

# CSS Shorthand vs Regular Properties

Many CSS properties can be written in two ways:

- Regular (Longhand)
- Shorthand

Both produce the same result.

Shorthand simply reduces the amount of code you write.

---

# What is Longhand?

Longhand means writing each property individually.

Example

```css
h1{

    margin-top:20px;
    margin-right:20px;
    margin-bottom:20px;
    margin-left:20px;

}
```

Advantages

- Easier to understand
- Better for beginners
- Allows changing one side only

Disadvantages

- More code
- Repetitive

---

# What is Shorthand?

Shorthand combines multiple properties into one line.

Example

```css
h1{

    margin:20px;

}
```

This produces the exact same result as the previous example.

Advantages

- Less typing
- Cleaner code
- Easier to maintain

---

# Margin Shorthand

Regular

```css
margin-top:10px;
margin-right:20px;
margin-bottom:30px;
margin-left:40px;
```

Shorthand

```css
margin:10px 20px 30px 40px;
```

Order

```
Top
Right
Bottom
Left
```

Remember:

**TRBL (Trouble)**

Top → Right → Bottom → Left

---

# Margin Shorthand Variations

One Value

```css
margin:20px;
```

All four sides become **20px**.

Two Values

```css
margin:20px 40px;
```

- Top & Bottom → 20px
- Left & Right → 40px

Three Values

```css
margin:10px 20px 30px;
```

- Top → 10px
- Left & Right → 20px
- Bottom → 30px

Four Values

```css
margin:10px 20px 30px 40px;
```

- Top → 10px
- Right → 20px
- Bottom → 30px
- Left → 40px

---

# Padding Shorthand

Regular

```css
padding-top:10px;
padding-right:20px;
padding-bottom:30px;
padding-left:40px;
```

Shorthand

```css
padding:10px 20px 30px 40px;
```

The order is exactly the same.

```
Top
Right
Bottom
Left
```

---

# Border Shorthand

Regular

```css
border-width:2px;
border-style:solid;
border-color:black;
```

Shorthand

```css
border:2px solid black;
```

Order

```
Width
Style
Color
```

---

# Background Shorthand

Regular

```css
background-color:lightblue;
background-image:url(bg.jpg);
background-repeat:no-repeat;
background-position:center;
```

Shorthand

```css
background:lightblue url(bg.jpg) no-repeat center;
```

---

# Font Shorthand

Regular

```css
font-style:italic;
font-weight:bold;
font-size:20px;
font-family:Arial;
```

Shorthand

```css
font:italic bold 20px Arial;
```

---

# Which One Should You Use?

| Situation | Recommended |
|-----------|-------------|
| Learning CSS | Longhand |
| Small changes | Longhand |
| Professional projects | Shorthand |
| Repeated styling | Shorthand |

Both methods are correct.

Choose the one that makes your code easier to understand.

---

# Summary

Longhand

- Easier to read
- Easier for beginners
- More lines of code

Shorthand

- Cleaner
- Shorter
- Preferred by experienced developers

As beginners, it is recommended to learn the longhand properties first, then gradually use shorthand as you become more comfortable with CSS.

# Common Beginner Mistakes

- Forgetting semicolons (`;`)
- Misspelling CSS properties
- Forgetting curly braces (`{}`)
- Using the wrong selector
- Confusing margin and padding
- Forgetting to link the external CSS file
- Using `#` instead of `.`
- Using uppercase property names

---

# Summary

Today you learned:

- What CSS is
- CSS Syntax
- CSS Selectors
- CSS Comments
- Inline CSS
- Internal CSS
- External CSS
- Text Properties
- Background Properties
- Borders
- Margin
- Padding

---

# Next Lesson

We will learn:

- CSS Box Model
- Width and Height
- Display Property
- Position Property
- Introduction to Flexbox
- Responsive Web Design Basics