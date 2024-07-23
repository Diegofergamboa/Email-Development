# Course Review

## Introduction to HTML Email

1. Markup Validation Service from the W3.
2. CanIEmail - used in Email Development.
3. Everything needs to be included in our HTML file.
4. Our images need live or direct links.
5. We can’t link external CSS files.
6. We principally use `<table>` elements and MSO statements for Windows Outlook.
7. 600px max-width design.
8. Our email has many tests across all the platforms.

***

## Description

1. Images and videos embedded in Google Drive are not a good idea.
2. It is a good idea to use GitHub and Mailship to upload the images; this is a free option.
3. The quantity of emails and apps used for it can be seen on Litmus.
4. It is important to check the statistics to see the light or dark mode view.

***

## HTML Crash Course

1. HTML5 is from 2014.
2. Meaning of HyperText Markup Language.
3. We have opening tags, close tags, and content.

***

## `<head>`

1. Charset is the Unicode Transformation Format, for the support.
2. HTTP-equiv - content X-UA-Compatible to specify which version will run if the browser is Internet Explorer.
3. Name, content, and initial scale are important for zoom or adaptability in different devices depending on the screen.

***

## Tags 

This is the format for paragraphs: `<p></p>`
- If I want to add a line break into the `<p>` tag, some `<br>` tags are needed inside the `<p>` Example: `<p>First <br> Second </p>`
- The headings are important to show the hierarchy, from `<h1>` to `<h6>`, and these will take the standard values of the browser.
- The major browsers use a 16px measurement for 1em, depending on the body hierarchy size.

**Text Formatting:**

- Bold Text: `<p>First <b>Bold</b></p>`
- Important Text: `<p>First <strong>Important</strong></p>`
- Italic Text: `<p>First <i>Italic text</i></p>`
- Emphasized Text: `<p>First <em>Italic text</em></p>`
- Underlined Text: `<p>First <u>Underlined text</u></p>`
- Inserted Text: `<p>First <ins>Inserted text</ins></p>`
- Smaller Text: `<p>First <small>Smaller text</small></p>`
- Bigger Text: `<p>First <big>Bigger text</big></p>`
- Subscript Text: `<p>First <sub>Subscript text</sub></p>`
- Superscript Text: `<p>First <sup>Superscript text</sup></p>`
- Marked Text: `<p>First <mark>Marked text</mark></p>`
- Deleted Text: `<p>First <del>Deleted text</del></p>`

**Links:**

For the links, we can use the following structure:
```html
<a href="https://www.google.com" target="_blank" title="This is a title from the tag">This is a simple text inside an anchor text</a>
