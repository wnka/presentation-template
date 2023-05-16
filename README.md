# What

A template for writing presentations. 

1. Edit `content/_index.md`
2. Put images in `static/`
3. Run `hugo server` and see how it looks.

Completely "inspired" by [reveal-hugo](https://github.com/dzello/reveal-hugo) with some minor tweaks to my taste.

# Printing

The built in printing/PDF generation for reveal.js SUCKS.

Use `decktape` which is available [here](https://github.com/astefanutti/decktape).

``` sh
decktape --pdf-author "You" --pdf-title "Great Presentation" -s 1920x1080 http://localhost:1313 out.pdf
```

This will be usable.

# Dependencies

1. [Hugo](https://gohugo.io/)

I think that's it.
