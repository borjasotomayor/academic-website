# Borja Sotomayor's Academic Website

This repository contains the source code for my academic website. You can see the website itself here:

**[https://people.cs.uchicago.edu/~borja/](https://people.cs.uchicago.edu/~borja/)**

The website is build with [Quarto](https://quarto.org/), using the [Quarto Academic Website Template](https://github.com/drganghe/quarto-academic-website-template) adapted by [Dr. Gang He](http://drganghe.github.io)

## Building

After [installing Quarto](https://quarto.org/docs/download/), run the following from the root of the repository to see a live preview of the website:

    quarto preview

To generate the static HTML files that can be uploaded to a web server, run the following:

    quarto render

The files will be located in the `build/` directory.
