# Sessions - InceptionU Cohort 11

[Live Site](https://acidtone.github.io/sessions-c11/)

---

## Oct 10 - Introduction to HTML and CSS

### 1. Visual hierarchy
- [Design principles: Visual hierarchy](https://www.youtube.com/watch?v=qZWDJqY27bw)

### 2. Introduction to HTML
- [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

#### Materials
- Video: [Pair Programming](https://www.youtube.com/watch?v=vgkahOzFH2Q)
  - [Dos and Donts](https://gist.github.com/acidtone/caa20b2520814a94240043c40301024a)

#### Activity: Wikipedia Markup**
1. Pick a hobby or interest that you could build a webpage around;
2. Find open source content on Wikipedia that contains examples of:
	- Headings (`<h1>`-`<h6>`)
	- Paragraphs (`<p>`)
	- Links (`<a>`)
	- Bold (`<strong>`) and italicized (`<em>`) text
	- Bullet (`<ul>` and `<li>`) and/or numbered (`<ol>` and `<li>`)lists
3. Create an `index.html` file in your workspace
	- Pro-tip: type `!` and then the `Tab` key inside an empty `.html` file to create an empty page!
4. Copy and paste the Wikipedia content inside a `<main>` container inside the `<body>` element of your `.html` page;
5. Wrap the text in the appropriate html element (see above).

### 3. Introduction to CSS

[![Slides: CSS Introduction](assets/images/slides/css-introduction.png)](html-css/css-introduction.html)

#### Materials
- [Getting Started with CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/Getting_started)
- [CSS values and units](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units)

#### Activity: Box Model Styles
Play around and experiment with different box model properties and HTML elements.
- Add a background color to the `<body>` or `<main>` with [`background-color`](https://css-tricks.com/almanac/properties/b/background-color/).
- Add [`padding`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding) on a container so the text doesn't touch the edge of the container.
- Add an accent line using [`border-left`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-left) or [`border-bottom`](https://developer.mozilla.org/en-US/docs/Web/CSS/border-bottom).
- Centre the text _within_ a heading using [`text-align`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align).
- Use the [`max-width`](https://developer.mozilla.org/en-US/docs/Web/CSS/max-width) property to limit the line length of your text to `650px` (or similar);
    - Hint: you can apply this to a container (i.e. `<main>`) to affect all text inside the container.
- Italicize the first paragraph using [`font-style`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-style) and a [class selector](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors).
- Use [`margin: auto`](https://www.hongkiat.com/blog/css-margin-auto/) to add equal spacing to the sides of a container of body text.
  - Note: this will only work if the container width is less than 100% of its parent.

### 4. Web Typography

[![Web typography](assets/images/slides/web-typography.png)](html-css/web-typography.html)

#### Materials
- Video: [Design principles: Typography](https://www.youtube.com/watch?v=yom0nogFN3k)
- [Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

#### Activity: Styling Text
Continue with the wikipedia text and customize your text and font styles:
- Increase the font size from its `16px` default using [`font-size`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) on the `<body>` element.
- Increase the leading of your text from the page's `1.2` default by setting `line-height` on the `<body>`.
- Refactor your `max-width` declaration from the previous activity so that it uses the `ch` unit. Change your max line length to `85ch`.
- User [Google Fonts](https://fonts.google.com/) to set a custom Display font on your headings and a Text font for the rest of your text.

**Don't forget to push your code to a public GitHub repo to keep up your green!**

---

## Oct 5 - Git, GitHub and the Command Line

**Important**: Create a GitHub account (professional username, plz) and Ping your username to Grimes in Basecamp.

### 1. Files, Directories and the command line
- Slides: [URLs and File Paths](https://acidtone.github.io/sessions-c11/misc/urls-file-paths.html)
- [Files, directories and naming conventions](https://gist.github.com/acidtone/d77059ec1851eff266339a3df70f6984)
- [Command Line Basics](https://gist.github.com/acidtone/316d2bd9cf59f841684dbd68ffc3ee95)
- Activity: [Follow the White Rabbit](https://gist.github.com/acidtone/6e3b69b7f2a81573d683b716fb069296)

### 2. Git and Github
- Slides: [Git and GitHub Basics](assets/files/Tech%20Appendix%20-%20Git%20and%20GitHub%20Basics.pdf)
- Activities:
  - [Git: First-time setup](https://gist.github.com/acidtone/6ca4c62d88570732d3760904ef965e4d)
  - [Clone Happy](https://gist.github.com/acidtone/1a6e3324d97e61fa0ee59bc4cba3ef33)
  - [Project: Publish a webpage with Git and GitHub Pages](https://gist.github.com/acidtone/5d45f96bc11fada75038e552f9ba1a5c)
- Don't like the command line? Try [using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview)

---

## Oct 3 - Dev Life and Searching like a nerd

- Slides:
  - [Better Search Phrases](https://acidtone.github.io/sessions-c11/misc/better-search-phrases.html)
  - [Browser Triad](https://acidtone.github.io/sessions-c11/html-css/browser-triad.html)
  - [UI Triad Quiz](https://acidtone.github.io/sessions-c11/html-css/ui-triad-quiz.html)
- Resources
  - Video: [HTML Tutorial for Beginners: HTML Crash Course](https://www.youtube.com/watch?v=qz0aGYrrlhU) by Mosh Hamedani
  - [Getting started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
  - [CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
- HTML/CSS/JS Course: [Mimo.org](https://mimo.org)
  - Recommended by many past learners.

---


