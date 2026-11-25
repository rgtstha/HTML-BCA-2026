# Web Development Class · BCA 2026

Class files for the BCA web development course: every example we wrote in class, the assignments, and the slides.

## What's in this repo

| Folder | What's inside |
| --- | --- |
| [`html-training/`](html-training/) | All the HTML examples we wrote in class |
| [`css-training/`](css-training/) | CSS examples, starting with our first external stylesheet |
| [`assignments/`](assignments/) | Assignments for you to complete |
| [`slides/`](slides/) | Lesson slides: an interactive HTML version and a PDF version of each |

## HTML training

The files are listed in the order we learned them.

| File | Topic |
| --- | --- |
| [`about.html`](html-training/about.html) | Page structure: `html`, `head`, `title`, `body` |
| [`index.html`](html-training/index.html) | Lists: `ul`, `ol`, `li` |
| [`text-formatting.html`](html-training/text-formatting.html) | Links and images: `a href`, `img src` |
| [`contact/contact.html`](html-training/contact/contact.html) | File paths: `../` goes up one folder |
| [`comment.html`](html-training/comment.html) | Comments: `<!-- ... -->` |
| [`form.html`](html-training/form.html) | Form basics: `form`, `label`, `input`, `button` |
| [`advance-form.html`](html-training/advance-form.html) | Input types: text, email, password, number, tel, date, color, radio, checkbox, plus `select` |
| [`form-submit.html`](html-training/form-submit.html) | Submitting a form with `method="GET"` |
| [`profile.html`](html-training/profile.html) | The page `form-submit.html` sends you to |
| [`table-example.html`](html-training/table-example.html) | Tables: `table`, `tr`, `td` |

Images: `ravi.jpg` is used by `profile.html` and `contact/contact.html`. `images/mountain-road.png` is a spare photo you can use for practice.

## CSS training

| File | Topic |
| --- | --- |
| [`index.html`](css-training/index.html) + [`css/style.css`](css-training/css/style.css) | Box model: a `.box` with `width`, `padding` and `border`; the `*` selector resets `margin` and `padding` and sets `box-sizing: border-box` on every element |
| [`ranjit-portfolio/index.html`](css-training/ranjit-portfolio/index.html) + [`ranjit-portfolio/css/style.css`](css-training/ranjit-portfolio/css/style.css) | **Project: portfolio website, part 1 (the header).** Name and menu links on a blue background: `.header`, `.logo`, `.nav-item`, `text-decoration: none`, and a `:hover` effect with `background-color` and `border-radius` |

## Assignments

| File | Assignment |
| --- | --- |
| [`assignment.html`](assignments/assignment.html) | **Student Profile:** headings, paragraphs, a photo, text formatting (`b`, `strong`, `em`, `i`), lists and links |

The Student Profile shows a photo from `images/self.JPG`. To see it, make an `images` folder next to `assignment.html` and put your own photo inside, named `self.JPG`.

### Homework after Lesson 01

1. Finish your Student Profile with your own colors and fonts.
2. One CSS file, many pages: link the same `style.css` to `index.html`, `about.html` and `contact/contact.html` (hint: `../style.css`).
3. Style `table-example.html` with CSS. Remove `border` and `cellspacing`, and use `border-collapse`, `border` and `padding` instead.
4. Bonus: make `form.html` look nice with bold labels, bigger text and a colored button.
5. Revise HTML by playing the HTML quiz on Wayground.

## Slides

| Lesson | Slides | PDF |
| --- | --- | --- |
| 01 · HTML Recap → Intro to CSS | [`index.html`](slides/01-intro-to-css/index.html) | [`intro-to-css.pdf`](slides/01-intro-to-css/intro-to-css.pdf) |
| 02 · Box Model → Build Your Portfolio | [`index.html`](slides/02-box-model/index.html) | – |

- **PDF:** click it on GitHub to read it in your browser, or download it to read and print offline.
- **HTML slides:** download the repo and open `index.html` in your browser. They work offline, and you can edit the code on the slides and see the result live.

Keyboard shortcuts for the HTML slides:

| Key | Action |
| --- | --- |
| `→` / `Space` | Next |
| `←` | Previous |
| `M` | List of all slides |
| `F` | Fullscreen |
| `D` | Dark / light theme |
| `?` | Show all shortcuts |

## How to use these files

1. Click the green **Code** button on GitHub, then **Download ZIP**, and unzip it. (Or run `git clone` if you use Git.)
2. Open any `.html` file in your browser to see the page.
3. Open the same file in a code editor such as VS Code to read and change the code.

On GitHub, clicking an `.html` file shows its source code, not the web page. To see the page itself, download it and open it in your browser.
