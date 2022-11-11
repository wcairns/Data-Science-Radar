# Data-Science-Radar
# **Features**

- Suitable for light docs site of a few pages.
- No HTML or Liquid coding needed. Just write content in markdown.
- No coding experience need to setup or work on.
- No Jekyll config, theme or packages to install.
- Uses a default minimal theme provided by GitHub - this is similar to viewing pages on GitHub itself but is cleaner on the edges.
- The build will add a homepage link to the top of each page. That is `h1`, so you first heading on the page should be an `h2`.
- There's an _Improve this page_ button in the bottom right of eac hpage.
- This pattern for a GH Pages site works using content in your `docs` directory. But you can also move everything to the root, such as if the entire repo is documentation, or if you are making a website that is not about documetnation. Just configure GH Pages to use the appropriate path.


## About

Content here.
```

## Homepage

The homepage needs be available as `/` i.e. `/index.html` when the site is rendered.

Therefore your homepage should be named `index.md`.

Or, name it `README.md` and use the following Jekyll frontmatter:

```liquid
---
permalink: /
---


## Navigation
