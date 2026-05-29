# HTML Theory Questions

This repository contains answers to important HTML theoretical questions with examples.

---

## Q1. What is HTML and what is the difference between HTML and HTML5?

HTML stands for HyperText Markup Language. It is used to create web pages and structure content on websites.

HTML5 is the latest version of HTML. It introduced new semantic tags, audio/video support, and better features for modern web development.

### Difference:
- HTML is the older version.
- HTML5 supports audio, video, semantic tags, and improved APIs.

### Example

```html
<!DOCTYPE html>
<html>
<head>
  <title>HTML Example</title>
</head>
<body>
  <h1>Hello World</h1>
</body>
</html>
```

---

## Q2. What are semantic HTML tags? Why are they important?

Semantic tags clearly describe the meaning of content in HTML.

Examples:
- `<header>`
- `<footer>`
- `<section>`
- `<article>`

These tags improve:
- SEO
- Accessibility
- Code readability

### Example

```html
<header>
  <h1>My Website</h1>
</header>

<section>
  <p>Welcome to my website.</p>
</section>

<footer>
  Copyright 2026
</footer>
```

---

## Q3. What is the difference between `<div>` and `<span>` tags?

`<div>` is a block-level element and takes full width.

`<span>` is an inline element and only takes needed space.

### Example

```html
<div>This is a div tag</div>

<span>This is a span tag</span>
```

---

## Q4. Explain the difference between block-level elements and inline elements.

Block-level elements start on a new line and take full width.

Inline elements stay in the same line and only use required space.

### Block Elements
- `<div>`
- `<p>`
- `<h1>`

### Inline Elements
- `<span>`
- `<a>`
- `<strong>`

---

## Q5. What is the purpose of the DOCTYPE declaration in HTML?

The `DOCTYPE` declaration tells the browser which HTML version is being used.

### Example

```html
<!DOCTYPE html>
```

It helps browsers display the page correctly.

---

## Q6. What is the difference between id and class attributes?

`id` is unique and used for one element.

`class` can be used for multiple elements.

### Example

```html
<div id="header"></div>

<p class="text"></p>
<p class="text"></p>
```

---

## Q7. How do you create a form in HTML? Which input types are commonly used?

Forms are created using the `<form>` tag.

Common input types:
- text
- email
- password
- number
- submit

### Example

```html
<form>
  <input type="text" placeholder="Name">
  <input type="email" placeholder="Email">
  <input type="submit">
</form>
```

---

## Q8. What are meta tags in HTML and why are they used?

Meta tags provide information about the webpage.

They are used for:
- SEO
- character encoding
- responsive design

### Example

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## Q9. Explain the purpose of the alt attribute in the `<img>` tag.

The `alt` attribute describes an image.

It helps:
- accessibility
- screen readers
- when image fails to load

### Example

```html
<img src="image.jpg" alt="Nature Image">
```

---

## Q10. How do you make an image clickable in HTML?

You can place the image inside an anchor tag.

### Example

```html
<a href="https://google.com">
  <img src="image.jpg" alt="Image">
</a>
```

---

## Q11. What is the difference between JPG, PNG, SVG, and WebP image formats?

- JPG: Small size, good for photos
- PNG: Supports transparency
- SVG: Vector format, scalable
- WebP: Modern format with better compression

---

## Q12. What are semantic tags introduced in HTML5 such as `<header>`, `<footer>`, `<section>`, and `<article>`?

These tags give meaning to webpage structure.

### Tags:
- `<header>` → top section
- `<footer>` → bottom section
- `<section>` → grouped content
- `<article>` → independent content

### Example

```html
<header>
  <h1>Website</h1>
</header>

<article>
  <p>Blog content</p>
</article>
```

---

## Q13. What is the difference between `<script>`, async, and defer in HTML?

- `<script>` loads JavaScript normally
- `async` loads script independently
- `defer` loads script after HTML parsing

### Example

```html
<script src="app.js" defer></script>
```

---

## Q14. How do you embed audio and video in HTML5?

HTML5 provides `<audio>` and `<video>` tags.

### Example

```html
<audio controls>
  <source src="audio.mp3">
</audio>

<video controls width="300">
  <source src="video.mp4">
</video>
```

---

## Q15. What is the difference between relative paths and absolute paths in HTML?

Relative paths point to local project files.

Absolute paths contain full URLs.

### Example

```html
<img src="images/photo.jpg">
<img src="https://example.com/photo.jpg">
```

---

## Q16. What are data attributes in HTML (`data-*`)? Where are they used?

Data attributes store custom information inside HTML elements.

### Example

```html
<div data-id="101">Product</div>
```

They are commonly used with JavaScript.

---

## Q17. What is the purpose of the viewport meta tag in responsive web design?

The viewport tag makes websites responsive on different devices.

### Example

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## Q18. How can you improve SEO using HTML?

SEO can be improved by:
- using semantic tags
- adding meta tags
- using alt attributes
- proper heading structure

### Example

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
```

---

## Q19. What are accessibility best practices in HTML?

Best practices:
- use semantic tags
- add alt text
- use labels in forms
- proper heading order

### Example

```html
<label>Email</label>
<input type="email">
```

---

## Q20. What is the difference between `<strong>` vs `<b>` and `<em>` vs `<i>` tags?

- `<strong>` gives important meaning
- `<b>` only makes text bold

- `<em>` adds emphasis
- `<i>` only italicizes text

### Example

```html
<strong>Important Text</strong>

<b>Bold Text</b>

<em>Emphasized Text</em>

<i>Italic Text</i>
```
