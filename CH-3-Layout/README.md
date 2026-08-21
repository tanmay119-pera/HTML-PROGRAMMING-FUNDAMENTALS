# CH-3-Creating-a-page-Layout-html-
🧩 Chapter 3: Creating a Page Layout

<p align="center">
  <b>Learn how HTML layout tags, links, containers, and inline elements help create a clear and structured webpage.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-Page%20Layout-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML Page Layout">
  <img src="https://img.shields.io/badge/Chapter-03-5B5FC7?style=for-the-badge" alt="Chapter 3">
  <img src="https://img.shields.io/badge/Level-Beginner--Friendly-2EA44F?style=for-the-badge" alt="Beginner Friendly">
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-layout-tags">Layout tags</a> •
  <a href="#-link-attributes">Links</a> •
  <a href="#-div-and-span-tags">Containers</a>
</p>

---

## ✨ Overview

Using the right HTML tag in the right place creates a cleaner and more readable page layout. It can also improve search-engine indexing and the user experience.

This chapter introduces the tags used to structure the main content of a webpage, create links, and group content with containers.

## 🎯 Topics Covered

- `<main>` tag
- `<section>` tag
- `<article>` tag
- `<aside>` tag
- Link attributes and the `target` attribute
- Linking an image
- `<div>` tag
- `<span>` tag

## 🏗️ Layout Tags

HTML layout tags describe the purpose of different parts of a webpage.

| Tag | Purpose |
| --- | --- |
| `<main>` | Contains the main content of the page. |
| `<section>` | Groups related content into a section. |
| `<article>` | Contains self-contained content, such as a post or news article. |
| `<aside>` | Contains content related to, but separate from, the main content, such as a sidebar or advertisement. |

## 🧱 Basic Page Layout

The following example uses the layout tags together:

```html
<main>
  <section>
    <article>
      <h1>Article Heading</h1>
      <p>Article content goes here.</p>
    </article>
  </section>

  <aside>
    <p>Aside content goes here.</p>
  </aside>
</main>
```

### Understanding the Structure

- `<main>` wraps the main content of the page.
- `<section>` creates a group of related content.
- `<article>` contains independent content that can stand on its own.
- `<aside>` contains supporting content, such as ads or a sidebar.

Using these tags is not compulsory for every simple webpage, but they make a page more readable and structured.

## 🔗 Link Attributes

The anchor tag, `<a>`, is used to create links.

### Open a Link in the Same Tab

```html
<a href="/contact">Contact</a>
```

The `href` attribute tells the browser where the link should go.

### Open a Link in a New Tab

```html
<a href="/contact" target="_blank">Contact Us</a>
```

The `target="_blank"` attribute opens the link in a new browser tab.

## 🖼️ Linking an Image

You can place an image inside an anchor tag to make the image clickable.

```html
<a href="/about">
  <img src="a.jpg" width="120" alt="About page">
</a>
```

In this example, clicking the image takes the user to the About page.

> If a file is inside a folder, make sure that the `href` or `src` path points to the correct location.

## 📦 Div and Span Tags

The `<div>` and `<span>` tags are containers used to group content.

| Tag | Type | Use |
| --- | --- | --- |
| `<div>` | Block-level container | Groups larger sections of content and takes the available width. |
| `<span>` | Inline container | Groups a small piece of text without starting a new line. |

## 🧱 The Div Tag

The `<div>` tag is commonly used as a container for other elements.

```html
<div>
  <h1>This is a heading inside a div.</h1>
  <p>This is a paragraph inside a div.</p>
</div>
```

Because `<div>` is a block-level element, it starts on a new line and takes the full available width by default.

## ✏️ The Span Tag

The `<span>` tag is an inline container. It takes only as much width as its content needs.

```html
<p>This is a <span>highlighted</span> word in a sentence.</p>
```

`<span>` is useful when you want to select or style a small part of text separately.

## ✅ Important Points

- Use `<main>` for the primary content of the webpage.
- Use `<section>` to group related content.
- Use `<article>` for self-contained content.
- Use `<aside>` for content such as sidebars or advertisements.
- Use `target="_blank"` when a link should open in a new tab.
- An image can be made clickable by placing it inside an `<a>` tag.
- Use `<div>` to group block-level content.
- Use `<span>` to group small inline pieces of content.

## 🚀 How to Run the Program

1. Create or open an `index.html` file.
2. Add the required HTML boilerplate.
3. Paste the layout examples inside the `<body>` tag.
4. Save the file.
5. Open it in a browser to view the page structure.

---

<p align="center">
  Made with ❤️ while creating HTML page layouts for Beginner
</p>

