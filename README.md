## Trident Systems website: *trident-systems-lp.github.io*

This repository is the source of the main public website for Trident Systems LP.  It is designed to be accessible at <http://www.tridentsystems.co.nz/>; it is developed using github pages and so can also be viewed at <http://trident-systems-lp.github.io/>.

This is a static website using [GitHub pages](https://pages.github.com/) and the *Feeling Responsive* [Jekyll](https://jekyllrb.com) theme <http://phlow.github.io/feeling-responsive/>.

Pages are written using extended markdown <https://kramdown.gettalong.org/syntax.html>.
This supports switching between Markdown and HTML, so bulk bits of text can use Markdown for readability and HTML elements like `<div>` can be used to give aditional structure.

Files that are processed by jekyll need to start with a [YAML](http://www.yaml.org) front matter between two lines of three hyphens like so:
~~~
---
layout: page
title: "An example page"
permalink: "/example/"
---
~~~
This is the bare minimum needed for the front matter of a page, there are also many optional things defined by jekyll and *Feeling Responsive*; such as meta_title, which changes the text displayed in the browser tab. The layout is a .html file in the _includes folder.
You can also add your own data to access later.

Jekyll uses [Liquid](http://shopify.github.io/liquid/) templating syntax: use `{{ }}` to access objects - use page.foo to access stuff defined in the front matter and site.data.baa to access stuff defined in the _data folder.
Use `{% %}` for logic and control flow stuff, as well as includes - snippets of HTML in the _includes folder.
