<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-zlib/brand/main/social/go-ruby-zlib.png" alt="go-ruby-zlib/go-ruby-zlib.github.io" width="720"></p>

# go-ruby-zlib.github.io

The organization's institutional landing page, served at
<https://go-ruby-zlib.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-zlib/docs](https://github.com/go-ruby-zlib/docs), served at
<https://go-ruby-zlib.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
