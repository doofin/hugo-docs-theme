# Compose

Compose is a [Hugo](https://gohugo.io/) theme for documentation or Wiki sites.

![Hugo Compose Theme](https://raw.githubusercontent.com/onweru/compose/master/images/tn.png)


## ExampleSite

try it locally:
```bash
git clone --recurse-submodules --depth 1 https://github.com/onweru/compose.git
cd compose/exampleSite/
hugo server --themesDir ../..
```

Note: You must edit `hugo.toml` to set the `theme` parameter to the directory name of the theme directory when you change themes!

The [exampleSite](https://github.com/onweru/compose/tree/master/exampleSite) is also theme's [user guide](https://composedocs.netlify.app/docs/compose/install-theme/) .

## Features

1. Documentation
2. Tina CMS support. Ships with configuration
3. Gallery Support
4. Native lazy loading of images
5. Live search
6. Flowcharts, Piecharts, doughnut & bar charts support
7. Searchable & Sortable tables
8. Syntax highlighting
9. Mermaid Support

## Project architecture
The theme uses the following technologies:
- sass for styling, under the `layouts/partials/head/index.html`, which invokes hugo's sass processor


To learn more about directory structure, see [Hugo directory structure](https://gohugo.io/getting-started/directory-structure/)

## License

This theme is available under the [MIT license](https://github.com/onweru/compose/blob/master/LICENSE).
