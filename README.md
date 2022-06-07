# Use Pandoc to Generate html with Custom .css and html Template

### Steps

- generate default pandoc html template

```bash
pandoc -D html > default-template.html
```

- invoke pandoc using custom CSS and default template

```bash
pandoc -s name-fo-file.md -c custom.css --template template.html -o name-of-file.html
```

OR

If `$styles.html()$` line in your pandoc template, you must have a **styles.html** file that has the CSS to be used. IT will--I think--be read inline.

### Free Pandoc Templates

[Easy Pandoc Template](https://github.com/ryangrose/easy-pandoc-templates)
