---
title: Home
---

[<img src="https://simpleicons.org/icons/github.svg" style="max-width:15%;min-width:40px;float:right;" alt="Github repo" />](https://github.com/yihui/hugo-xmin)

# Donna Wrublewski

**XMin** is a Hugo theme written by [Yihui Xie](https://yihui.name) in about four hours: half an hour was spent on the Hugo templates, and 3.5 hours were spent on styling. The main motivation for writing this theme was to provide a really minimal example to beginners of Hugo templates. This XMin theme contains about 130 lines of code in total, including the code in HTML templates and CSS (also counting empty lines).


```bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
       6 ./professional/index.html
      49 ./website/content/post/2015-07-23-r-rmarkdown.html
      66 ./website/public/note/index.html
      61 ./website/public/note/2017/06/13/a-quick-note/index.html
      56 ./website/public/note/2017/06/14/another-note/index.html
     113 ./website/public/index.html
      64 ./website/public/post/2015/07/23/lorem-ipsum/index.html
      95 ./website/public/post/2015/07/23/hello-r-markdown/index.html
      71 ./website/public/post/index.html
     198 ./website/public/post/2016/02/14/a-plain-markdown-post/index.html
      51 ./website/public/css/style.css
       7 ./website/public/css/fonts.css
      46 ./website/public/404.html
     151 ./website/public/about/index.html
      61 ./website/public/tags/tutorial/index.html
      61 ./website/public/tags/pandoc/index.html
      86 ./website/public/tags/index.html
      61 ./website/public/tags/plot/index.html
      61 ./website/public/tags/blogdown/index.html
      66 ./website/public/tags/markdown/index.html
      61 ./website/public/tags/rstudio/index.html
      61 ./website/public/tags/r-markdown/index.html
      61 ./website/public/tags/mathjax/index.html
      61 ./website/public/tags/regression/index.html
      62 ./website/public/categories/index.html
      61 ./website/public/categories/hugo/index.html
      76 ./website/public/categories/example/index.html
      61 ./website/public/categories/r/index.html
       4 ./website/layouts/partials/foot_custom.html
       5 ./website/themes/hugo-xmin/layouts/404.html
      12 ./website/themes/hugo-xmin/layouts/_default/single.html
      20 ./website/themes/hugo-xmin/layouts/_default/list.html
      13 ./website/themes/hugo-xmin/layouts/_default/terms.html
       0 ./website/themes/hugo-xmin/layouts/partials/foot_custom.html
       0 ./website/themes/hugo-xmin/layouts/partials/head_custom.html
       9 ./website/themes/hugo-xmin/layouts/partials/footer.html
      20 ./website/themes/hugo-xmin/layouts/partials/header.html
      51 ./website/themes/hugo-xmin/static/css/style.css
       7 ./website/themes/hugo-xmin/static/css/fonts.css
    2075 total
```

I can certainly further reduce the code, for example, by eliminating the CSS, but I believe a tiny bit of CSS can greatly improve readability. You cannot really find many CSS frameworks that only contain 50 lines of code.

Although it is a minimal theme, it is actually fully functional. It supports pages (including the home page), blog posts, a navigation menu, categories, tags, and RSS. With [a little bit customization](https://github.com/yihui/hugo-xmin/blob/master/exampleSite/layouts/partials/foot_custom.html), it can easily support LaTeX math expressions, e.g.,

`$${\sqrt {n}}\left(\left({\frac {1}{n}}\sum _{i=1}^{n}X_{i}\right)-\mu \right)\ {\xrightarrow {d}}\ N\left(0,\sigma ^{2}\right)$$`

All pages not under the root directory of the website are listed below. You can also visit the list page of a single section, e.g., [posts](/post/), or [notes](/note/). See the [About](/about/) page for the usage of this theme.
