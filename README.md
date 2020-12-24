## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/arial-jiang/arial-jiang.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/arial-jiang/arial-jiang.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


Trip PWA
----

> Very simple code to demonstrate Progressive Web Apps.

### Usage

This demo app runs on `localhost`.

```bash
npm install http-server -g
http-server -c-1 # with cache disabled
```

Then open <http://localhost:8080> with Chrome.

Change `cacheStorageKey` in `sw.js` to update app version.

### Trouble shooting

* Why `-c-1` to disable cache?

`sw.js` can be cached by HTTP Caches, then in debugging we could get unexpected behaviors. Disable the cache to simplify the problem.

### License

MIT
