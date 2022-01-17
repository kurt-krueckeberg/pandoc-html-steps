# Use Pandoc to Generate html with Custom .css and html Template

### Steps

- Generate Default html Template

```bash
pandoc -D html > default-template.html
```

- Invoke Pandoc using custom CSS and default template

```bash
pandoc -s name-fo-file.md -c custom.css --template template.html -o name-of-fileE.html
```


### Template Resources

https://github.com/ryangrose/easy-pandoc-templates
