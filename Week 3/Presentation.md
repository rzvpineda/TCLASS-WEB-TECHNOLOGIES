# HTML FUNDAMENTALS

**Week 2 – Introduction to HTML**

**Instructor:** [Your Name]

**Course:** Web Technologies

**Semester:** [Semester / Academic Year]

---

# Review of Last Week

Last week, we learned:

- What the Internet is
- Difference between the Internet and the World Wide Web
- Website vs Web Application
- Client-Server Architecture
- HTML, CSS, and JavaScript
- Basic HTML Document Structure

**Question:**

Which technology is responsible for the structure of a webpage?

---

# Learning Objectives

At the end of today's lesson, you should be able to:

- Explain what HTML is.
- Identify common HTML tags.
- Create headings and paragraphs.
- Use text formatting tags.
- Add line breaks and horizontal rules.
- Understand HTML attributes.
- Create a simple webpage from scratch.

---

# What is HTML?

**HTML** stands for **HyperText Markup Language**.

It is the standard markup language used to create webpages.

HTML describes the structure of a webpage using elements called **tags**.

Unlike Java or C#, HTML is **not a programming language**. It is a **markup language** because it tells the browser how content should be organized and displayed.

---

# What is HyperText?

HyperText is text that contains links to other pages or resources.

**Example:**

Clicking a link on Facebook that opens another page is an example of HyperText.

---

# What is Markup?

Markup means adding tags to content so browsers understand its structure.

**Without Markup**

Hello World

**With Markup**

```html
<h1>Hello World</h1>
```

The browser understands that this content should be displayed as a large heading.

---

# HTML Document Structure

Every webpage begins with the following structure.

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>

</body>
</html>
```

Every HTML document should follow this structure.

---

# Understanding the HTML Structure

## `<!DOCTYPE html>`

- Tells the browser this is an HTML5 document.

## `<html>`

- The root element.
- Everything belongs inside this tag.

## `<head>`

- Contains information about the webpage.
- Content here is generally not visible to users.

## `<body>`

- Contains everything displayed on the webpage.

---

# What is an HTML Tag?

HTML uses **tags** enclosed inside angle brackets.

Example:

```html
<h1>This is a Heading</h1>

<p>This is a Paragraph</p>
```

Most HTML tags consist of:

- Opening Tag
- Content
- Closing Tag

---

# Container Tags vs Empty Tags

## Container Tags

These have both an opening and a closing tag.

```html
<h1>Heading</h1>

<p>Paragraph</p>

<title>Website</title>
```

## Empty Tags

These do not require closing tags.

```html
<br>

<hr>
```

---

# HTML Headings

HTML provides six heading levels.

```html
<h1>Heading 1</h1>

<h2>Heading 2</h2>

<h3>Heading 3</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>
```

Use **`<h1>`** for the main title of the webpage.

---

# Paragraph Tag

The paragraph tag is used to display blocks of text.

```html
<p>
Welcome to my webpage.
</p>
```

Browsers automatically add spacing between paragraphs.

---

# Line Break

The `<br>` tag creates a new line.

```html
Juan Dela Cruz
<br>
BSIT Student
<br>
First Year
```

---

# Horizontal Rule

The `<hr>` tag inserts a horizontal line.

```html
<h1>About Me</h1>

<hr>

<p>This is my profile.</p>
```

Horizontal lines help separate sections of a webpage.

---

# Text Formatting Tags

Common formatting tags include:

- `<b>` – Bold
- `<strong>` – Strong Importance
- `<i>` – Italic
- `<em>` – Emphasized
- `<u>` – Underline
- `<mark>` – Highlight
- `<small>` – Smaller Text

---

# Example of Text Formatting

```html
<p>I am a <b>BSIT</b> student.</p>

<p>I love <i>Programming</i>.</p>

<p>This is <mark>important</mark>.</p>

<p><strong>Warning!</strong></p>
```

---

# HTML Comments

Comments are ignored by the browser.

They are used for documentation and organization.

```html
<!-- This is a comment -->
```

---

# HTML Attributes

Attributes provide additional information about HTML elements.

Example:

```html
<p align="center">
Hello World
</p>
```

Another example:

```html
<body bgcolor="lightblue">
```

Attributes are written inside the opening tag.

---

# Example Webpage

```html
<!DOCTYPE html>
<html>
<head>
    <title>Student Profile</title>
</head>

<body>

<h1>John Doe</h1>

<hr>

<p>I am a BSIT student.</p>

<p>I love programming.</p>

</body>
</html>
```

---

# Best Practices

Always:

- Close your tags.
- Indent your code properly.
- Organize your HTML.
- Use meaningful headings.
- Save before refreshing your browser.

---

# Common Beginner Mistakes

- Forgetting closing tags.
- Misspelling HTML tags.
- Placing content outside the `<body>`.
- Forgetting the `<title>` tag.
- Incorrect nesting of HTML elements.

---

# Live Demonstration

Today we will build a webpage together.

We will create:

- A webpage title
- Headings
- Paragraphs
- Horizontal lines
- Formatted text
- Comments

---

# Summary

Today we learned:

- HTML Fundamentals
- HTML Tags
- Headings
- Paragraphs
- Line Breaks
- Horizontal Rules
- Text Formatting
- HTML Comments
- HTML Attributes

---

# Looking Ahead

**Next Week**

- Lists
- Images
- Hyperlinks
- Tables
- Semantic HTML

We will begin creating larger and more organized webpages.

---

# Questions and Discussion

**Thank You!**

**Any Questions?**