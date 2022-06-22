# Yohello

This is the source of [this](https://ktvng.github.io/yohello/) website.

## Build

There is a Github Action in place to deploy any changes to `index.md` to the
`index.html` site when pushing to `master` branch.

To generate the HTML file from Markdown manually,
[pandoc](https://github.com/jgm/pandoc) is used:

```
pandoc --standalone --metadata pagetitle="nohello" --css "assets/css/pandoc.css" --output=index.html index.md
```

## Acknowledgements

This website was inspired by the original at
[nohello.com](https://www.nohello.com/) and by the "canonical" open source 
version found [here](https://sbmueller.github.io/nohello/). Acknowledgements go to the original
anonymous author and the creators of the open source "mirror". The 
[Stylesheet](https://gist.github.com/forivall/7d5a304a8c3c809f0ba96884a7cf9d7e#file-gh-pandoc-css)
is available licensed under MIT license, Copyright (c) 2016-2017 Emily M Klassen.

I felt the need to put a quirky spin on a timeless classic.
