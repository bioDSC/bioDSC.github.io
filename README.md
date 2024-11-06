# Website of *bio*DSC (University of Amsterdam)

This repository contains the code and content to generate the website of the Biological Data Science Center of the University of Amsterdam. We use [Quarto](https://quarto.org), and specifically the [Quarto website](https://quarto.org/docs/websites/) functionality, to generate a static website from a special flavor of `.md` files: `.qmd`. 

## Workflow for maintaining this website

### Setting up
* [Install Quarto-CLI](https://quarto.org/docs/get-started/).
* `git clone` the repository to local machine.

### Editing pages
* `git pull` to make sure you're working with the most recent version of the code.
* Make edits in `.qmd` files, using your favorite text editor (e.g. VS Code or RStudio).
* To track your work locally, use `quarto preview`.
* When you are happy with your edits, use `quarto render` to generate HTML pages from the `.qmd` files.
* To publish the work, use git to make a commit and push to this repository.

### Adding a new blog post or workshop announcement

`.qmd` files in the `posts/` and `workshops/` folders are automatically listed on the corresponding pages of the website. So, to add a new blogpost, simply write a new `.qmd` file and add it to the `blogs/` folder. If you use images, place them in the `posts/post_images/` folder. Don't forget to `quarto render`, then push to this repository.

## Contributing

If you notice bugs on our website, don't hesitate to open a GitHub issue. If you are a UvA researcher and want to contribute content to our website (e.g. a guest blog entry), get in touch with one of the maintainers. For fast and easy intergration into the website, content in a `.md` file is preferred.

## Maintainers

Current maintainers of the bioDSC website are:

* Frans van der Kloet (BDA, University of Amsterdam)
* Martijn Wehrens (Mol Cyto, University of Amsterdam)
* Misha Paauw (GLS, University of Amsterdam)

## Inspiration

Resources that were helpful while making this website:

* [Customizing Quarto websites by Sam Csik](https://ucsb-meds.github.io/customizing-quarto-websites/#/title-slide)
* [A beginner’s guide to building a simple website with Quarto & Netlify](https://jadeyryan.com/blog/2024-02-19_beginner-quarto-netlify/)
* [The ultimate guide to starting a Quarto blog](https://albert-rapp.de/posts/13_quarto_blog_writing_guide/13_quarto_blog_writing_guide.html)