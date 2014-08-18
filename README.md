jandr-wedding-site
==================

My sister's wedding website. This page renders at http://ehsteve.github.io/jandr-wedding-site.

# Testing Locally

To setup your machine to run this site locally, you'll first need to install a few things. Please follow the 
[installation instructions](https://help.github.com/articles/using-jekyll-with-pages) provided by github.

You will likely want test any changes you've made to the site. To do this you'll have the run Jekyll and host the site locally. This can be done by running the following command inside the site directory

    bundle exec jekyll serve --watch

This will create a page hosted locally at http://localhost:4000.

# Editing

To edit the text on the website edit the [index.html file](https://github.com/ehsteve/jandr-wedding-site/blob/gh-pages/index.html). Only edit the text itself and do not mess with the html tags.

To edit the color of the page edit the `background-color` code in the following code block

    .bg-primary {
        color: #fff;
        background-color: #66ccff;
    }

located in the file [css/bootstrap.min.css](https://github.com/ehsteve/jandr-wedding-site/blob/gh-pages/css/bootstrap.css)
