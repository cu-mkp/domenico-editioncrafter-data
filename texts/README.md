# Texts Directory

1. [texts/](texts/) directory - all files associated with an edition's source material (i.e., transcriptions and translations)

## Generating EditionCrafter Data

EditionCrafter has an accompanying command line interface (CLI) that is used to generate the artifacts it displays. This software is written in Javascript, so you will need to have Node.js installed on your computer. Once Node.js is installed, run the following command to install the tool:

`npm install -g @cu-mkp/editioncrafter-cli`

For this project, use the following command from the base directory to generate the artifacts:

`editioncrafter process texts/domenico-edition.xml texts https://cu-mkp.github.io/domenico-editioncrafter-data/texts`

Replacing caryatidum.xml with the name of the XML you wish to update. Once these changes are commited to the main branch of this repo, they will be published by GitHub Pages and available for EditionCrafter to render on your website.

See the Getting Started guide on the EditionCrafter homepage for more information.

The images for this example were drawn from the following manifest supplied by the BnF:

https://gallica.bnf.fr/iiif/ark:/12148/btv1b7200356s/manifest.json