# PANDOC STYLES

List of styles for `pandoc`.

## `style.documents.css` - using wkhtmltopdf engine

Live transform with:

```bash
ls lorem.md style.documents.css|entr -s 'pandoc --css=style.documents.css -s --pdf-engine=wkhtmltopdf -o lorem.pdf lorem.md'
```

