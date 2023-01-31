# Simple Portfolio Website

### What is this about?
This simple portfolio website has been built as one of the tasks in [Career Foundry's Full-Stack Web Development Program](https://careerfoundry.com/en/courses/become-a-web-developer/)

- a simple test portfolio website in HTML and CSS, consisting of `index.html`, `about.html`, `work.html`, `contact.html`
- no build workflow
- no SCSS
- no JavaScript, besides [tota11y](https://khan.github.io/tota11y/)
- desktop first (not responsive)
- `contact.html` has no functionality implemented (see "no JavaScript")

### Tools / Requirements
- Visual Studio Code
- GitHub
- [tota11y on GitHub](https://github.com/Khan/tota11y/releases/tag/0.1.6), to grab the `min.js` via zip download
- [PostCSS CSS Variables](https://madlittlemods.github.io/postcss-css-variables/playground/) to compile CSS Variables in use to "simple" CSS
- [Autoprefixer](http://autoprefixer.github.io/) to set the exact browser versions you want to support and add all the prefixes you need
- `index.html` is built according to the delivered, annotated HTML template: ![template index](img/template-index-page.jpg)
- `about.html` is built according to this template: ![template about](img/template-about-page.png)
- `<svg>` has been provided
- `contact.html` has form validation, proper `<label>` and `<input>`
- CSS Grid and Flexbox, genereal styling, where required (Header, Footer, `work.html`, etc.)

### How to run this?
As there's no npm packages or a build workflow present, it's fairly easy:
- clone the repo
- `cd` into project
- if on Visual Studio Code, install "Live Server" extension, go to bottom menu and click "Go Live": <br>
![Visual Studio Code Screenhot Go Live](img/screenshot-golive.png) <br>
- this is going to open the website on localhost http://127.0.0.1:5500/

