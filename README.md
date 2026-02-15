# ICBO 2026: International Conference on Biomedical Ontology

This repository hosts the documents for the [ICBO 2026 website](https://icbo-conference.github.io/icbo2026/). The website is built using `mkdocs` and the deployment of the website is controlled using the GitHub action `.github/workflows/build-deploy-documentation.yaml`. The GitHub action has been configured to run if any changes are made to `mkdocs.yaml`, files in the `docs/` or `docs/images/` directories, or after a pull request is merged.

## Editing website content

The website content is contained in the `docs/` directory. Editing any of the `*.md` files **should** fire off an action to build and deploy the website. This GitHub action can be checked by navigating to the `Actions` page.

After the action has finished running (it will have green check), verify that the edits are displayed on the website.

## Adding new webpages

Adding new webpage takes two steps:

1. Create the new `md` file in the `docs/` directory.
2. Edit the `nav` section of `mkdocs.yml` to reference the new document and its title.

## Manually deploying the website

If (for some reason) the GitHub action does not fire, you can manually run it. First, on the `Actions` page, select the `Build and Deploy Static Mkdocs Documentation` workflow, then click on the `Run workflow` button.

## Tutorials (Help)

- [Markdown tutorial](https://www.markdownguide.org/basic-syntax/)
- [HTML tutorial](https://www.w3schools.com/html/)
- [MkDocs documentation](https://www.mkdocs.org/)
