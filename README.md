Do not rely on GitHub to build the site. We use jekyll-scholar, which is an unsupported plugin, so we need to build the site statically and push that.

See [GitHub Pages & Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)

To serve locally run

```bash
bundle exec jekyll serve
```

To build static site locally run

```bash
bundle exec jekyll build
```

and push contents of docs folder to GitHub.
