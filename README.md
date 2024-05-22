# Lesson 2: HTML Tags w/ Attributes

### 🎯 Objectives

- Create HTML elements with attributes to add links and images to their pages.

## Table of Contents

1. [Do Now](#do-now)
2. [Anchor and Image Tags](#anchor-and-image-tags)
3. [Coding Practice](#coding-practice)

## Do Now

For today's activity, you will be editing a website about sloths which is missing some information. Open the index.html file and complete these tasks:

- Create an `<h1>` tag which says “Sloths!”
- Create a `<p>` tag which says “Sloths are the slowest animal in the world”

## Anchor and Image Tags

Wow, you did great with those `<h1>` and `<p>` tags! Now, let's have some fun with other cool tags – `<a href…>` and `<img src…>` tags.
<br>

### Did you say anchor?

Yes! The `<a href…>` tag is like a magic portal on a webpage. It's called an **anchor tag**, and it lets us hop around from one web page to another, or even different parts of the same page.

When you see a clickable word or picture on a webpage that takes you somewhere else when you click it, that's an anchor tag doing its thing!

But how does the anchor tag know where to take us? That's where **attributes** come in. Think of them like special instructions we give to our HTML elements.

For an anchor tag, we use an attribute called `href` that holds the web address (URL) of where we want to go. It looks something like this:

```html
<a href="https://www.codenation.org">Code Nation!</a>
```

In this example, "Code Nation!" is what we'll see and click on the webpage, and "https://www.codenation.org" is where we'll go when we click it.
<br>
<br>

### Picture Time with `<img>` tag

The `<img>` tag allows us to add an image to our website. But how does it know which image to show?

Just like the anchor tag uses the `href` attribute, the `<img>` tag uses an attribute called `src` (short for source). The `src` attribute holds the address of the image we want to show.

Unlike most tags, the `<img>` tag doesn't need a closing tag. It's what we call a **self-closing tag**.

Here's what it looks like:

```html
<img src="https://www.example.com/image.jpg" />
```

## Coding Practice

Let's open up our coding environment and practice writing some anchor and image tags! As I write code, make sure you are writing along with me.
