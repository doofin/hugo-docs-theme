# Compose

Compose is a [Hugo](https://gohugo.io/) theme for documentation or Wiki sites.

![Hugo Compose Theme](https://raw.githubusercontent.com/onweru/compose/master/images/tn.png)

Features:

1. Documentation
2. Mermaid Support for diagrams and flowcharts
3. Flowcharts, Piecharts, doughnut & bar charts support
4. Gallery Support
5. Native lazy loading of images
6. Live search
7. Searchable & Sortable tables
8. Syntax highlighting
9. Tina CMS support. Ships with configuration


## Demo site
try it locally:
```bash
git clone --recurse-submodules --depth 1 https://github.com/onweru/compose.git
cd compose/exampleSite/
hugo server --themesDir ../..
```

Note: You must edit `hugo.toml` to set the `theme` parameter to the directory name of the theme directory when you change themes!

The [exampleSite](https://github.com/onweru/compose/tree/master/exampleSite) is also theme's [user guide](https://composedocs.netlify.app/docs/compose/install-theme/) .

## Deployment
Deploy to github pages, see hugo docs:
https://gohugo.io/host-and-deploy/host-on-github-pages/

Basic steps:
- configure your repo settings in github
- add a github action file under `.github/workflows/gh-pages.yml`
- change `hugo.toml` for cache


## Project architecture
The theme uses the following technologies:
- sass for styling, under the `layouts/partials/head/index.html`, which invokes hugo's sass processor


To learn more about directory structure, see [Hugo directory structure](https://gohugo.io/getting-started/directory-structure/)

## License

This theme is available under the [MIT license](https://github.com/onweru/compose/blob/master/LICENSE).
