# Arcadia Workflows Documentation Site

This repository hosts Arcadia Science's workflows documentation site built with [Quarto](https://quarto.org/) and rendered with Github Pages.

## Build Instructions

1.  Install `quarto` on your machine following [these instructions](https://quarto.org/docs/get-started/). If you are new to contributing to Quarto websites, check out [this guide](https://quarto.org/docs/websites/).

2.  Clone this repository with `git clone https://github.com/Arcadia-Science/arcadia-metagenomics-workflows.git`

3.  This site was built using option 1 of the instructions for rendering with Github pages [described here](https://quarto.org/docs/publishing/github-pages.html). The website is rendered to the `docs` directory by modifying the `_quarto.yml` file

4.  Add `touch .nojekyll` to the directory

5.  Then `push` your commits to Github, where the Github Pages is rendered from the `docs/` directory. In a new repository navitage to "Pages" and select render from `main` and `docs/`

## Contributing

If you would like to contribute to this documentation site, follow the instructions above to install Quarto, fork to your personal Github account and clone to your local machine. The individual documentation pages are located in the `pages/` directory. To preview your changes locally before creating a pull request, enter `quarto preview` in the terminal where the directory is located. To render your changes, enter `quarto render`. Then create a Pull Request describing your changes.
