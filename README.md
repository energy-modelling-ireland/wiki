# Ireland Energy Wiki Website

This repository contains the source files for the [`ireland-energy-wiki`](https://energy-modelling-ireland.github.io/) website which hosts an actively maintained collection of Irish energy research resources.  

---

## How the Wiki works

### Content

All content for each page on the site is contained in a `Markdown` (md) file in the `docs/` folder. 

`Markdown` is a simple language:

1. Bullet-pointing:
```
- 1
- 2
```

2. Linking images & pages:
```
![The Wiki Logo](docs/logo.png)
```
![The Wiki Logo](docs/logo.png)
```
[Data Sources](Data-Sources.md)
```

> Where more control is required (i.e. styling images or tables) `Markdown` files understand `HTML`.

### Publishing

When changes are made to the `docs/` folder `Github Actions` uses `mkdocs` to convert the `Markdown` files to `HTML`, `css` and `JavaScript`.  It then publishes these files.  The workflow content is written in `.github/workflows/publish.yml`. 
