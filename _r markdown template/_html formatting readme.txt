Changing font in HTML Document in Markdown

Place this in the YAML header:

---
output:
  html_document:
    css: style.css
---

Create a CSS Style sheet, saving the following in a file named: style.css

/* Whole document: */
body{
  font-family: Helvetica;
  font-size: 16pt;
}
/* Headers */
h1,h2,h3,h4,h5,h6{
  font-size: 24pt;
}