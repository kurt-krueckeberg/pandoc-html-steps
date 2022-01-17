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


### Free Pandoc Templates

[Easy Pandoc Template](https://github.com/ryangrose/easy-pandoc-templates)
