# 0x00. Advanced HTML

## HTML
## Front-end

## Concepts
For this project, we expect you to look at this concept:

- [HTML - elements of a web page]()

[html](images/5d9e347964a9cc0e3e24.jpg)


## Welcome!
Welcome to the Web Stack specialization. The first three projects will give you all the basics of Web development: HTML, CSS, and Developer tools.

In this project, you will learn how to use HTML tags to structure a web page. No CSS, no styling - don’t worry, the final page will be “ugly”; it’s normal, and it’s not the purpose of this project.

**Important note:** details are important! Lowercase vs uppercase / wrong letter… be careful!

## Resources
Read or watch:

- [HTML 5.2](https://www.w3.org/TR/html52/)
- [HTML: HyperText Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Reference - A free guide to all HTML elements and attributes](https://htmlreference.io/)
- [Can I use… Support tables for HTML5, CSS3, etc](https://caniuse.com/)
- [HTML Cheat Sheet - WebsiteSetup](https://websitesetup.org/html5-cheat-sheet/)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- Which guidelines to follow for HTML
- How to create the skeleton of an HTML5 page
- How to use semantic HTML tags to structure a web page
- Which use cases to use div vs span
- The semantic values of header, main, footer, article, nav, section, aside
- How to use headings (and why it’s important to follow the hierarchical order)
- How to make lists in HTML
- The differences between medias (SVG, GIF, PNG, JPG)
- How to structure data in a table
- How to integrate a video on a webpage
- How to integrate an audio file on a webpage
- How to embed external content
- How to correctly structure an HTML page

## Requirements
- A README.md file at the root of the folder of the project is mandatory
- Your code should be W3C compliant and validate with W3C-Validator
- Techium will be the name of the company we will use across our webpages.

## Sitemap of the project
[Sitemap Image](images/4dec2ba9d84a0a55355b1c1e2de4c57854a2d35a.png)

## Wireframe of Techium project
[Link to Wireframe Image](images/3e4f9e2b3cb73d1768229e086f5da35337be5c6c.png)

<details>
  <summary>Show/Hide Quiz</summary>

## Quiz questions
  
### Question #0
Which information can we find in the `<head>` tag? Please select all correct answers

- [x] link to stylesheets
- [x] metadata
- [ ] link to Twitter
- [ ] navigation

### Question #1
Which tag should we use to embed another website?

- [ ] `<code>`
- [ ] `<p>`
- [ ] `<a>`
- [ ] `<div>`
- [x] `<iframe>`

### Question #2
Which tag should we use to change the font weight of a text? Please select all correct answers

- [x] `<strong>`
- [ ] `<em>`
- [x] `<b>`
- [ ] `<h1>`
- [ ] `<i>`
- [ ] `<bold>`

### Question #3
Which tag should we use to group elements in an unordered list?

- [ ] `<unordered list>`
- [ ] `<table>`
- [x] `<ul>`
- [ ] `<li>`
- [ ] `<ol>`
- [ ] `<list>`

### Question #4
Which tag should we use to draw a horizontal line? (usually used to separate topics in a paragraph)

- [x] `<hr>`
- [ ] `<line>`
- [ ] `<break>`
- [ ] `<br>`

### Question #5
How many levels are available in HTML5 for section headings?

- [ ] 8
- [x] 6
- [ ] 2
- [ ] 1
- [ ] 4
- [ ] 10

### Question #6
Which tag should we use to create a hyperlink?

- [x] `<a>`
- [ ] `<div>`
- [ ] `<to>`
- [ ] `<link>`
- [ ] `<p>`

### Question #7
Which tag should we use to change the browser tab text?

- [ ] `<browser>`
- [ ] `<head>`
- [ ] `<tab>`
- [x] `<title>`

### Question #8
Which tag should we use to embed an image?

- [ ] `<caption>`
- [x] `<img>`
- [ ] `<div>`
- [ ] `<iframe>`

</details>

### Task 0: Create your first webpage

- Add the doctype on the first line (without any comment)
- Open and close an HTML tag after the doctype
- Add the language tag, specify English for the ISO language code, and add the direction tag (ltr or rtl) on the HTML tag.
- Open your file in your browser (the page should be blank)
- Ignore W3C errors


**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File:  `0-index.html`

---

### Task 1: Structure your webpage

- Copy the content of `0-index.html` into `1-index.html`
- Create the head and body sections inside the HTML tag
- The head and body tags should be empty
- Ignore W3C errors

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File:  `1-index.html`

---

### Task 2: The head - meta charset, viewport, title, description, favicons

- Copy the content of `1-index.html` into `2-index.html`

**Meta charset:**
  - Add a meta tag inside the head.
  - Add the `charset` attribute with the value `utf-8`.

**Viewport:**
  - Add a meta tag inside the head.
  - Add an attribute `name` on the tag and specify that it is the meta viewport.
  - Add the key `width` with the value `device-width`.
  - Add the key `initial-scale` with the value `1.0`.
  - Add the key `viewport-fit` with the value `cover`.

**Title:**
  - Add the title tag just after the meta viewport with the value: "Homepage - Techium".

**Description:**
  - Add a meta tag inside the head section.
  - Add an attribute `name` on the tag and specify that is the meta description.
  - Add another attribute called `content`.
  - Add the following description: "Techium is a digital agency".

**Favicons:**
  - Download the image above to use as a favicon.
  - Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats.
  - Take the `favicon.ico` and `favicon.png` and place these at the root of your project directory, so that it is siblings with your `[0-9]+-index.html` files.
  - Inside the head, create 2 link tags with these 3 attributes: `rel`, `type`, and `href`.
    - The first link tag:
      - `rel`: icon
      - `type`: image/x-icon
      - `href`: `./favicon.ico`
    - The second link tag:
      - `rel`: icon
      - `type`: image/png
      - `href`: `./favicon.png`


**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File:  `2-index.html`

---

