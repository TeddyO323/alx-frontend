# 0x00. Advanced HTML

## HTML
## Front-end

## Concepts
For this project, we expect you to look at this concept:

- [HTML - elements of a web page]()

![html](images/5d9e347964a9cc0e3e24.jpg)


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
![Sitemap Image](images/4dec2ba9d84a0a55355b1c1e2de4c57854a2d35a.png)

## Wireframe of Techium project
![Link to Wireframe Image](images/3e4f9e2b3cb73d1768229e086f5da35337be5c6c.png)

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

Create your first HTML file `0-index.html `with:

- Add the doctype on the first line (without any comment)
- Open and close an HTML tag after the doctype
- Add the language tag, specify English for the ISO language code, and add the direction tag (ltr or rtl) on the HTML tag.
- Open your file in your browser (the page should be blank)
- Ignore W3C errors


**Repo:**
-  GitHub repository: `alx-frontend`
-  Directory: `0x00-html_advanced`
-  File:  `0-index.html`

---

### Task 1: Structure your webpage

Copy the content of `0-index.html` into `1-index.html`
- Create the head and body sections inside the HTML tag
- The head and body tags should be empty
- Ignore W3C errors

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File:  `1-index.html`

---

### Task 2: The head - meta charset, viewport, title, description, favicons

Copy the content of `1-index.html` into `2-index.html`

![html](images/2ba3a0d7878316de5aaa.jpg)

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
  - Add the title tag just after the meta viewport with the value: "`Homepage - Techium"`.

**Description:**
  - Add a meta tag inside the head section.
  - Add an attribute `name` on the tag and specify that is the meta description.
  - Add another attribute called `content`.
  - Add the following description: "`Techium is a digital agency"`.

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
-  GitHub repository: `alx-frontend`
-  Directory: `0x00-html_advanced`
-  File:  `2-index.html`

---

### Task 3: Simple header, main, footer

Copy the content of `2-index.html` into `3-index.html`

**Header:**
  - Create the header of your page between the open and close body tags.
  - Put the text "`Header"` inside the header.

**Main:**
  - Create the main tag after the header tag.
  - Put the text "`Main content"` inside your main tags.

**Footer:**
  - Create the footer tag after the main tag.
  - Put the text "`Footer"` inside the footer tags.


**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `3-index.html`

---

### Task 4: Aside

Copy the contents of `3-index.html` into `article.html`
- Change the `<title>` to put: "`Article - Techium"`
  - Inside the main tags after the text, create the aside tags with text "`Aside"`



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `article.html`

---

### Task 5: Section

Copy the content of `3-index.html` into `5-index.html`
- Inside your `<main>` section:
  - Remove the text in main.
  - Create these sections:
    - Create the first section and put the text "`Hero section"` inside.
    - Create the second section and put the text "`Services section"` inside.
    - Create the third section and put the text "`Works section"` inside.
    - Create the fourth section and put the text "`About section"` inside.
    - Create the fifth section and put the text "`Latest news section"` inside.
    - Create the sixth section and put the text "`Testimonials section"` inside.
    - Create the seventh section and put the text "`Contact section"` inside.
Ignore W3C errors



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `5-index.html`

---

### Task 6: Work, News, Testimonial articles

Copy the content of `5-index.html` into `6-index.html`

**Work articles:**
  - Inside the section "`Works section"`, add 3 article tags.
  - add 3 article tags
    - Inside each article, write "`Work #"` where the hashtag will be the ordered number (1, 2, or 3).

**News articles:**
  - Inside the section "`Latest news section"`, add 3 article tags.
  - add 3 article tags
    - Inside each article, write "`Article #"` where the hashtag will be the ordered number (1, 2, or 3).

**Testimonial articles:**
  - Inside the section "`Testimonials section"`, add 3 article tags.
  - add 3 article tags
  - Inside each article, write "`Testimonial #"` where the hashtag will be the ordered number (1, 2, or 3).
Ignore W3C errors

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `6-index.html`

---

### Task 7: Navigation

Copy the content of `6-index.html` into `7-index.html`
- Remove the "`Header"` text inside the `<header>`
- Create the `nav` tag inside the `header` tag.
- The `nav` tag should remain empty for now.
- Ignore W3C errors


**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `7-index.html`

---

### Task 8: Level 1 headings

Copy the content of `7-index.html` into `8-index.html`
- Create the level 1 heading inside your main before your sections.
- Put text "`Homepage"` in your heading tag.
- Ignore W3C errors



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `8-index.html`

---

### Task 9: Level 2 headings

Copy the content of `8-index.html` into `9-index.html`
- In the section tag with the text "`Hero section,"` remove the text and create a level 2 heading with text "`We help you build your brand!"`
- In the section tag with the text "`Services section,"` remove the text and create a level 2 heading with text "`Services."`
- In the section tag with the text "`Works section,"` remove the text and create a level 2 heading with text "`Works."`
- In the section tag with the text "`About section,"` remove the text and create a level 2 heading with text "`About Us."`
- In the section tag with the text "`Latest news section,"` remove the text and create a level 2 heading with text "`Latest news."`
- In the section tag with the text "`Testimonials section,"` remove the text and create a level 2 heading with text "`Testimonials."`
- In the section tag with the text "`Contact section,"` remove the text and create a level 2 heading with text "`Contact."`
- Ignore W3C errors



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `9-index.html`

---

### Task 10: Level 3 headings
Copy the content of `9-index.html `into `10-index.html`

#### Services headings:

- Inside the section containing the h2 heading "`Services,"` add these elements right after the h2:
  - Create a level 3 heading with text "`Design & Concept."`
  - Create a level 3 heading with text "`Digital Strategy."`
  - Create a level 3 heading with text "`Content Strategy."`
  - Create a level 3 heading with text "`UX Design."`
  - Create a level 3 heading with text "`Web Development."`
  - Create a level 3 heading with text "`Social Media."`

#### Works headings:

- Inside the section containing the h2 heading "`Works:"`
  - In the first article, replace the text with a level 3 heading with text "`Interior Design."`
  - In the second article, replace the text with a level 3 heading with text "`Web Development."`
  - In the third article, replace the text with a level 3 heading with text "`Personal Brand."`

#### About Us headings:

- Inside the section containing the h2 heading "`About Us,"` after the h2 heading, create these elements in this order:
  - Create a level 3 heading with text "`Who are we."`
  - Create a level 3 heading with text "`Our culture."`
  - Create a level 3 heading with text "`How we work."`

#### Latest news headings:

- Inside the section containing the h2 heading "`Latest news:"`
  - In the first article, replace the text with a level 3 heading with text "`Hoc loco tenere se Triarius non potuit."`
  - In the second article, replace the text with a level 3 heading with text "`Ut alios omittam, hunc appello, quem ille unum secutus est."`
  - In the third article, replace the text with a level 3 heading with text "`Bestiarum vero nullum iudicium puto."`
- Ignore W3C errors



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `10-index.html`

---

### Task 11: Styleguide

Copy the content of `3-index.html` into `11-styleguide.html`
- Change the title to "`Styleguide - Techium"`
- Remove the text from header, main, and footer
- Create a new `<section>` inside your main tag
- Create a header in this section
- In the header, add a level 2 heading with text "`Headings"`
- After the header:
  - Add a level 1 heading with text "`Heading level 1"`
  - Add a level 2 heading with text "`Heading level 2"`
  - Add a level 3 heading with text "`Heading level 3"`
  - Add a level 4 heading with text "`Heading level 4"`
  - Add a level 5 heading with text "`Heading level 5"`
  - Add a level 6 heading with text "`Heading level 6"`



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `11-styleguide.html`

---

### Task 12: Paragraphs

Copy the content of  `10-index.html` into `12-index.html`

#### About Us paragraphs:

- In the About Us section:
  - After the first h3 ("`Who are we"`), create a paragraph with the text: "`Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!"`
  - After the second h3, create a paragraph with the text: "`Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!"`
  - After the third h3, create a paragraph with the text: "`Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!"`

#### Latest news paragraphs:

- In the Latest news section:
  - In the first article:
    - Create a paragraph with text "`Career"` before the heading.
    - Create a paragraph with text "`Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?"` after the heading.
  - In the second article:
    - Create a paragraph with text "`Digital Life"` before the heading.
    - Create a paragraph with text "`Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama?"` after the heading.
  - In the third article:
    - Create a paragraph with text "`Social"` before the heading.
    - Create a paragraph with text "`Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones."` after the heading.

#### Contact paragraph:

- In the Contact section after the heading:
  - Create a paragraph with the text: "`Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?"`

#### Additional paragraphs:

- Below the level 2 Services heading, add a paragraph with text "`We work with you."`
- Below the level 2 Works heading, add a paragraph with text "`Take a look at our portfolio."`
- Below the level 2 About Us heading, add a paragraph with text "`Everything about us."`
- Below the level 2 Testimonials heading, add a paragraph with text "`We are more than a digital company."`
- Below the level 2 Contact heading, add a paragraph with text "`We like to know new people."`
- Ignore W3C errors



**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `12-index.html`

---

### Task 13: Styleguide Paragraphs

Copy the contents of `11-styleguide.html` into `13-styleguide.html`
- After the existing section containing Headings, create a new section in the main.
- In this section, create a header.
- Inside the header, create a level 2 heading with text "`Paragraph."`
- After the header:
  - Add a level 2 heading with text "`Heading with a subtitle."`
  - Add a paragraph with text "`This is my subtitle."`
  - Add another paragraph with text: "`Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan."`


**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `13-styleguide.html`

---

### Task 14: Span

Copy the contents of `12-index.html` into `14-index.html`
- In the very first `<header>`, before the `nav`, create a span with the text "`Techium."`
- Ignore W3C errors

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `14-index.html`

---

### Task 15: Div

Copy the contents of `14-index.html` into `15-index.html`
- Wrap the contents of the `header` element with a `div`
- Wrap the contents of all `section` elements with a `div`
- Finally, wrap the contents of the `<footer>` tag with a `div`
- W3C does not need to pass

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `15-index.html`

---

### Task 16: Structure your Sections

Copy the contents of `15-index.html` into `16-index.html`
- In the `div` in the Services section:
  - Create a `header` tag that wraps the `h2` and the `p`
  - Create a `div` sibling to the `header` that wraps the rest of the content
- In the `div` in the Works section:
  - Create a `header` tag that wraps the `h2` and the `p`
  - Create a `div` sibling to the `header` that wraps the rest of the content
- In the `div` in the About Us section:
  - Create a `header` tag that wraps the `h2` and the `p`
  - Create a `div` sibling to the `header` that wraps the rest of the content
- In the `div` in the Latest news section:
  - Create a `header` tag that wraps the `h2`
  - Create a `div` sibling to the `header` that wraps the rest of the content
- In the `div` in the Testimonials section:
  - Create a `header` tag that wraps the `h2` and the `p`
  - Create a `div` sibling to the `header` that wraps the rest of the content
- In the `div` in the Contact section:
  - Create a `header` tag that wraps the `h2` and the first `p`
  - Create a `div` sibling to the `header` that wraps the rest of the content
- W3C does not need to pass

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `16-index.html`

---

### Task 17: Comments

Copy the contents of `16-index.html` into `17-index.html`
- Before the `header`, add a line break and a comment saying "`Header"` to help with scanning your code
- Before the `main`, add a line break and a comment saying "`Main"` to help with scanning your code
- Before the `footer`, add a line break and a comment saying "`Footer"` to help with scanning your code
- Before the "`Hero section,"` add a line break and a comment saying "`Hero section"`
- Before the "`Services section,"` add a line break and a comment saying "`Services section"`
- Before the "`Works section,"` add a line break and a comment saying "`Works section"`
- Before the "`About Us section,"` add a line break and a comment saying "`About Us section"`
- Before the "`Latest news section,"` add a line break and a comment saying "`Latest news section"`
- Before the "`Testimonials section,"` add a line break and a comment saying "`Testimonials section"`
- Before the "`Contact section,"` add a line break and a comment saying "`Contact section"`
- Does not need to pass W3C

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `17-index.html`

---

### Task 18: Link Your Logo

Copy the contents of `17-index.html` into `18-index.html`
- In the `header`, wrap the `span` with a link that redirects to the page at the root of your folder (`/`)
- Wrap the link with a `div`
- W3C does not need to pass

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `18-index.html`

---

### Task 19: Create New Pages

Copy the contents of `18-index.html` into `about.html`, `latest_news.html`, and `contact.html`
- Change the title of `about.html` to replace "`Homepage"` with "`About"`
- Change the title of `latest_news.html` to replace "`Homepage"` with "`Latest news"`
- Change the title of `contact.html` to replace "`Homepage"` with "`Contact"`
Does not need to pass W3C

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- Files: `about.html`, `latest_news.html`, `contact.html`

Certainly! Here are the tasks with the specified format for the "Repo" section:

### Task 20: Add links

- Copy the content of `18-index.html` into `20-index.html`
- In your `nav` tags:
  - Create a link to `/` with the text Home
  - Create an anchor to services with the text Services
  - Create an anchor to works with the text Works
  - Create an anchor to about with the text About
  - Create an anchor to latest_news with the text Latest news
  - Create an anchor to testimonials with the text Testimonials
  - Create an anchor to contact with the text Contact
  - For now, the anchor links will not work. We will make them work in the CSS project.

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `20-index.html`

---

### Task 21: Add social media links

- Copy the content of `20-index.html` into `21-index.html`
- In the `div` in the footer:
  - Remove any text you have
  - Create a link to `https://www.facebook.com/HolbertonSchool/` with the text Facebook
  - Create a link to `https://twitter.com/holbertonschool` with the text Twitter
  - Create a link to `https://www.instagram.com/holbertonschool/` with the text Instagram

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `21-index.html`

---

### Task 22: "Button" links

- Copy the content of `21-index.html` into `22-index.html`
- In the Hero section, after the heading:
  - Create a link to `#` with the text Get started
- In the About Us section, after the div containing the level 3 headings and paragraphs:
  - Create a link to `about.html` with the text Learn more about us
- In the Contact section, after the div containing the paragraph:
  - Create a link to `contact.html` with text Get in touch

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `22-index.html`

---

### Task 23: Services, Works, Latest news links

- Copy the content of `22-index.html` into `23-index.html`
- In the Services section:
  - In each level 3 heading, create a link to `#` around the text already in the heading
- In the Works section:
  - In each level 3 heading, create a link to `#` around the text already in the heading
- In the Latest news section:
  - In each level 3 heading, create a link to `#` around the text already in the heading

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `23-index.html`

---

### Task 24: List the links

- Copy the content of `23-index.html` into `24-index.html`
- In the `nav`:
  - Create an unordered list, put each anchor tag (Home, Services, Works, …) as an individual list item
- In the `div` in the footer:
  - Create an unordered list and put each anchor tag (Facebook, Twitter, …) as an individual list item

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `24-index.html`

---

### Task 25: Secondary navigation menu

- Copy the content of `24-index.html` into `25-index.html`
- Inside the footer, after the div:
  - Create a new div
  - In the new div, create an unordered list with the following links:
    - Link to `#` with text Terms of Use
    - Link to `#` with text Privacy Policy
    - Link to `#` with text Cookie Policy

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `25-index.html`

---

### Task 26: Examples of lists for the styleguide

- Copy the content of `13-styleguide.html` into `26-styleguide.html`
- Example of unordered list:
  - Inside main after Paragraph section, add:
    - A new line and a comment with text Lists
    - After, create a new section with inside:
      - Create a header with inside a level 2 heading with the text Lists
      - After the new header, create a div with inside:
        - A level 3 heading with text Unordered
        - Under it, add an unordered list with these items: Dolor pulvinar etiam magna etiam., Sagittis adipiscing lorem eleifend., Felis enim

 feugiat dolore viverra.
- Example of ordered list:
  - After the previous unordered list, in the same div:
    - Add a level 3 heading with text Ordered
    - Add an ordered list with these items:
      - Dolor pulvinar etiam magna etiam.
      - Sagittis adipiscing lorem eleifend.
      - Felis enim feugiat dolore viverra.
- Example of definition list:
  - After the previous ordered list, in the same div:
    - Add a heading level 3 with text Definition
    - Add a definition list with these items:
      - Term: Definition List title, Definition: Definition text.
      - Term: Startup, Definition: A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.
      - Term: Water, Definition: A colorless, transparent, odorless liquid that forms the seas, lakes, rivers, and rain and is the basis of the fluids of living organisms.

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `26-styleguide.html`

---

### Task 27: Separate content

- Copy the content of `25-index.html` into `27-index.html`
- In the footer between the two divs:
  - Add a horizontal rule
  - After the horizontal rule, add a paragraph with text © 2020 Techium, made with ♥ by students at Holberton School.

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `27-index.html`

---

### Task 28: Horizontal rule example

- Copy the content of `26-styleguide.html` into `28-styleguide.html`
- In main after Lists section:
  - Add a new line and a comment with the text Horizontal rule
  - Create a new section
  - Create a header and inside it add a level 2 heading with the text Horizontal rule
  - After the header, create a div and put a horizontal rule in it

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `28-styleguide.html`

---

### Task 29: Client quotes

- Copy the content of `27-index.html` into `29-index.html`
- In the Testimonials section:
  - In the first article, replace the text with a blockquote with text I am completely blown away. Thanks to Techium, we've just launched our 5th website! and cite author Yuri Y.
  - In the second article, replace the text with a blockquote with text Thank you so much for your help. Techium company is awesome! and cite author Dorrie S.
  - In the third article, replace the text with a blockquote with text I love your system. Definitely worth the investment. I'd be lost without Techium company. and cite author Sven H.

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `29-index.html`

---

### Task 30: Examples of quotes

- Copy the content of `28-styleguide.html` into `30-styleguide.html`
- Example of inline quote:
  - Inside main after Horizontal rule section:
    - Add a new line and a comment with text Blockquotes
    - Create a new section
    - In the section, create a header, in the header create a level 2 heading with text Blockquotes
    - After the header, create a div
    - In the div, add a level 3 heading with the text Inline quote
    - Add an inline quote with the text Stay hungry. Stay foolish.
- Example of blockquote:
  - After the inline quote div, create another div
  - In the new div, add a level 3 heading with the text Blockquote
  - Add a multiline quote with the text I will be the leader of a company that ends up being worth billions of dollars, because I got the answers. I understand culture. I am the nucleus. I think that’s a responsibility that I have, to push possibilities, to show people, this is the level that things could be at. and cite Kanye West, Musician

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `30-styleguide.html`

---

### Task 31: Address and latest news authors

- Copy the content of `29-index.html` into `31-index.html`
- In the footer:
  - Right after the open footer tag, put the following address: 234 Washington Street (line-break) Urbana, Illinois
- In the Latest news section:
  - In the first article, after the last paragraph, add the author name in small print: By Kelly D.
  - In the second article, after the last paragraph, add the author name in small print: By William A.
  - In the third article, after the last paragraph, add the author name in small print: By Frances J.

**Repo:**
- GitHub repository: `alx-frontend`
- Directory: `0x00-html_advanced`
- File: `31-index.html`

---

### Task 32: Typography section - using the correct tags

- Copy the content of `30-styleguide.html` into `32-styleguide.html`

Inside the `main` after the Blockquotes section, add a new line and a comment with text "Typography." Create a new section.

In the section:
- Create a header and inside it, add a level 2 heading with the text "Typography."
- After the header, create a div.
- Inside the div, add the address text with the correct HTML tags: 
  - `320 Stewart Avenue, Unit 12` (line break)
  - `New York City NY 10001`
  - The city, state, and postal code should be on separate lines.
- Create another div.
- In the new div, nest the provided code block using the `pre` HTML tag:

```html
<code>
  <h2>My title</h2>
  <p>Proin lacus turpis, feugiat sit amet sollicitudin non, volutpat in libero. Aenean hendrerit ultrices nulla ac lobortis. Vestibulum consectetur nibh vel ante rhoncus faucibus.</p>
</code>
```

- Create another div.
- In the new div, add the provided paragraph of text with the correct HTML tags: 
  - Curabitur sit amet turpis cursus massa mollis highlighted. Duis finibus leo massa, eget dapibus erat finibus sed. Aenean condimentum sapien magna, eleifend highlighted mi consequat ut. Cras nec quam sed sapien ultricies highlighted ut sed metus. Each occurrence of the word "highlighted" should be highlighted.

W3C does not need to pass


Repo:

- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 32-styleguide.html

---

### Task 33: Table

- Copy the content of `32-styleguide.html` into `33-styleguide.html`

Inside the `main` after the Typography section, add a new line and a comment with text "Table." Create a new section.

In the section:
- Create a header, and in the header, add a level 2 heading with the text "Table."
- After the header, create a table to reproduce the provided visual:

![html](images/1348f88f2d78a5dee5d0.jpg)


The `<th>` tags containing Title, Director, Release Date should have a `scope` attribute set to `col`. The `<th>` tags containing the names of the movies should have a `scope` attribute set to `row`.


Due to the previous task, it does not need to pass W3C

Repo:

- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 33-styleguide.html

---

### Task 34: Details

- Copy the content of `33-styleguide.html` into `34-styleguide.html`

In the `main` after the Table section, add a new line and a comment with text "Details." Create a new section.

In the section:
- Create a header, and in the header, add a level 2 heading with the text "Details."
- After the header, create a div.
- In the div:
  - Add a level 3 heading with text "Default."
  - Add a details element and specify "Show/Hide me" in the summary.
  - Add this text after the summary: "Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas."
- Create another div.
- In the new div:
  - Add a level 3 heading with text "Open."
  - Add a details element that is open by default and specify "Always open" in the summary.
  - Add this text after the summary: "Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas."

Due to earlier tasks, it does not need to pass W3C



Repo:

- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 34-styleguide.html

---

### Task 35: Replace text logo with image logo

![html](images/06f32e89f2a82582234e.png)

- Copy the content of `31-index.html` into `35-index.html`

In the header, find the span with the name of the website and replace it with the provided image:

```html
<img src="logo-black.png" alt="Techium logo" width="160" height="40">
```

In the footer, after the opening tag and before the address, insert the same logo image:

```html
<img src="logo-black.png" alt="Techium logo" width="160" height="40">
```

W3C does not need to pass



Repo:

- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 35-index.html

---

### Task 36: Add images to your sections

- Copy the content of `35-index.html` into `36-index.html`

Add three images in the Works section:
- Before the first level 3 heading, create a div, and add `images/pic-work-01.jpg` inside the div. Alt: empty.
- Before the second level 3 heading, create a div, and add `images/pic-work-02.jpg` inside the div. Alt: empty.
- Before the third level 3 heading, create a div, and add `images/pic-work-03.jpg` inside the div. Alt: empty.

Add one image in the About Us section:
- Before the first level 3 heading inside the div, add the image `images/pic-about-us.jpg`. Alt: empty. Width: 460, Height: 447.

Add three images in the Latest news section:
- In the first article, before the first paragraph, create a div, and add the image `images/pic-blog-01.jpg`. Alt: empty. Width: 305, Height: 205.
- In the second article, before the first paragraph, create a div, and add the image `images/pic-blog-02.jpg`. Alt: empty. Width: 305, Height: 205.
- In the third article, before the first paragraph, create a div, and add the image `images/pic-blog-03.jpg`. Alt: empty. Width: 305, Height: 205.

Add three images in the Testimonials section:
- In the first article before the quote, add the image `images/pic-person-01.jpg`. Alt: Yuri Y. avatar. Width: 100px, Height: 100px.
- In the second article before the quote, add the image `images/pic-person-02.jpg`. Alt: Dorrie S. avatar. Width: 100px, Height: 100px.
- In the third article before the quote, add the image `images/p

ic-person-03.jpg`. Alt: Sven H. avatar. Width: 100px, Height: 100px.

W3C does not need to pass

---

Repo:

- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 36-index.html

---

### Task 37: Social icons

- Copy the content of `36-index.html` into `index.html` (the final file!)
- Inside the footer:
  - Replace the text "Facebook" with the SVG icon code and add a width of 25px and height of 25px to the SVG tag:

```html
<svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <title>Facebook icon</title>
  <path d="M23.998 12c0-6.628-5.372-12-11.999-12C5.372 0 0 5.372 0 12c0 5.988 4.388 10.952 10.124 11.852v-8.384H7.078v-3.469h3.046V9.356c0-3.008 1.792-4.669 4.532-4.669 1.313 0 2.686.234 2.686.234v2.953H15.83c-1.49 0-1.955.925-1.955 1.874V12h3.328l-.532 3.469h-2.796v8.384c5.736-.9 10.124-5.864 10.124-11.853z"/>
</svg>
```

  - Replace the text "Twitter" with the SVG icon code and add a width of 25px and height of 25px to the SVG tag:

```html
<svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <title>Twitter icon</title>
  <path d="M23.954 4.569a10 10 0 0 1-2.825.775 4.958 4.958 0 0 0 2.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 0 0-8.384 4.482C7.691 8.094 4.066 6.13 1.64 3.161a4.822 4.822 0 0 0-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 0 1-2.228-.616v.061a4.923 4.923 0 0 0 3.946 4.827 4.996 4.996 0 0 1-2.212.085 4.937 4.937 0 0 0 4.604 3.417 9.868 9.868 0 0 1-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 0 0 7.557 2.209c9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63a9.936 9.936 0 0 0 2.46-2.548l-.047-.02z"/>
</svg>
```

  - Replace the text "Instagram" with the SVG icon code and add a width of 25px and height of 25px to the SVG tag:

```html
<svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
  <title>Instagram icon</title>
  <path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913a5.885 5.885 0 0 0 1.384 2.126A5.868 5.868 0 0 0 4.14 23.37c.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558a5.898 5.898 0 0 0 2.126-1.384 5.86 5.86 0 0 0 1.384-2.126c.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913a5.89 5.89 0 0 0-1.384-2.126A5.847 5.847 0 0 0 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227a3.81 3.81 0 0 1-.899 1.382 3.744 3.744 0 0 1-1.38.896c-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421a3.716 3.716 0 0 1-1.379-.899 3.644 3.644

 0 0 1-.9-1.38c-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324 6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 0 1-2.88 0 1.44 1.44 0 0 1 2.88 0z"/>
</svg>
```

**Repo:**
- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: index.html

---

### Task 38: Add a video player in the styleguide

- Copy the content of `34-styleguide.html` into `38-styleguide.html`
- In the main, after the Details section:
  - Add a new line and a comment with the text "Video"
  - Create a section
  - In the section header, add a level 2 heading with the text "Video"
  - After the header, add the following video: [https://intranet-projects-files.s3.amazonaws.com/webstack/BigBuckBunny.mp4](https://intranet-projects-files.s3.amazonaws.com/webstack/BigBuckBunny.mp4)
  - Add controls to the video
  - Ensure that the video loops
  - Display [https://intranet-projects-files.s3.amazonaws.com/webstack/thumbnail.jpg](https://intranet-projects-files.s3.amazonaws.com/webstack/thumbnail.jpg) when the video is downloading
  - Provide alternative text: "Sorry, your browser doesn't support HTML5 video"

**Repo:**
- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 38-styleguide.html

---

### Task 39: Add an audio player in the styleguide

- Copy the content of `38-styleguide.html` into `39-styleguide.html`
- In the main, after the Video section:
  - Add a new line and a comment with the text "Audio"
  - Create a section
  - In the section header, add a level 2 heading with the text "Audio"
  - After the header, add the following audio file: [https://intranet-projects-files.s3.amazonaws.com/webstack/TroubleChapter8_64kb.mp3](https://intranet-projects-files.s3.amazonaws.com/webstack/TroubleChapter8_64kb.mp3)
  - Add controls to the audio player
  - Provide alternative text: "Sorry, your browser doesn't support audio element"

**Repo:**
- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: 39-styleguide.html

---

### Task 40: Add an iframe example in the styleguide

- Copy the content of `39-styleguide.html` into `styleguide.html`
- In the main, after the Audio section:
  - Add a new line and a comment with the text "Iframe"
  - Create a section
  - In the section header, add a level 2 heading with the text "Iframe"
  - After the header, add a div
  - Inside the div, create an iframe with the following properties:
    - Title: Holberton School
    - Width: 350px
    - Height: 200px
    - Source: [https://www.youtube.com/embed/41N6bKO-NVI](https://www.youtube.com/embed/41N6bKO-NVI)
    - Fallback text: Holberton Sally

**Repo:**
- GitHub repository: alx-frontend
- Directory: 0x00-html_advanced
- File: styleguide.html