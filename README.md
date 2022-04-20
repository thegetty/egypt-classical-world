This is the repository for *Egypt and the Classical World: Cross-Cultural Encounters in Antiquity*, edited by Jeffrey Spier and Sara E. Cole. This digital book was first published June 21, 2022, by the J. Paul Getty Museum. It is available online at [https://www.getty.edu/publications/egypt-classical-world/](https://www.getty.edu/publications/egypt-classical-world/) and may be downloaded free of charge in multiple formats.

## About the Book

From Mycenaean weaponry found among the cargo of a Bronze Age shipwreck off the Turkish coast to the Egyptian-inspired domestic interiors of a luxury villa built in Greece during the Roman Empire, *Egypt and the Classical World* documents two millennia of cultural and artistic interconnectedness in the ancient Mediterranean. This volume gathers pioneering research from the Getty scholars' symposium that helped shape the major international loan exhibition *Beyond the Nile: Egypt and the Classical World* (J. Paul Getty Museum, 2018).

Generously illustrated essays consider a range of artistic and other material evidence, including archaeological finds, artworks, papyri, and inscriptions, to shed light on cultural interactions between Egypt, Greece, and Rome from the Bronze Age, to the Late Period and Ptolemaic dynasty, to the Roman Empire. The military's role as a conduit of knowledge and ideas in the Aegean and an in-depth study of hieroglyphic Egyptian inscriptions found on Roman obelisks offer but two examples of scholarly lacunae addressed by this publication. Specialists across the fields of art history, archaeology, Classics, Egyptology, and philology will benefit from the volume's investigations into syncretic processes that enlivened and informed nearly twenty-five hundred years of dynamic cultural exchange.

## Using this Repository

This is one in series of multiformat publications using [Quire](http://quire.getty.edu)™, Getty’s new publishing framework. Quire is currently in beta, with the goal of it being released as free and open source software in the future. In the meantime, users are encouraged to request access at http://bit.ly/quire-signup. This repository can also be run locally to build the online site (but not the PDF or ebook formats) with [Hugo](https://gohugo.io/), the [static site generator](https://www.smashingmagazine.com/2015/11/modern-static-website-generators-next-big-thing/) at the core of Quire.

We are dedicated to maintaining this publication for years to come at the permanent URL, [https://www.getty.edu/publications/egypt-classical-world/](https://www.getty.edu/publications/egypt-classical-world/), and in its various formats and incarnations. For any updates to the book, we will be following something between an app and traditional book publication model. Updates will only be made in regulated chunks as formal revisions and new editions and will always be thoroughly documented here in the repository, as well as in the revision history included with each of the book’s many formats.

The primary content pieces of the book can be found in the `data` and `content` directories. The master branch represents the current, published edition at all times, and the revisions branch, when present, will show changes currently under consideration. We invite you to submit suggestions or corrections via pull request on the revisions branch, by posting an issue, or by emailing us at [pubsinfo@getty.edu](mailto:pubsinfo@getty.edu).

## Development Notes

This project was last built with the following software versions:

- Quire 0.20.2
- Node 14.18.1 / npm 6.14.15
- Hugo 0.82.1
- PrinceXML 14.2
- Pandoc 2.17.1.1

While version 0.20.2 of the core Quire Default Theme was used, a number of customizations were made:

- Custom cover design and font
- Copyright statements added to the end of each essay
- Custom font added to display Egyptian transliterations in essay 7

Within the theme itself, changes were made to the `source/css/variables.scss` and `source/css/print.scss` files. Outside of the theme, customizations can be found in the project’s `layouts` directory, and in `static/css/custom.css`.

### Images Submodule

Many of figure images for *Egypt and the Classical World* are licensed from third parties for use exclusively in this publication. As such, they are kept in a separate, private repository, https://github.com/thegetty/egypt-classical-world-images/, which is linked to this main publication repository as a submodule in `static/img/figures/`. When cloning this repo for further development, you’ll permissions for the private repository and will need to clone recursively in order to clone both the main repo and the submodule.

```
git clone --recursive https://github.com/thegetty/egypt-classical-world.git
```

## License

© 2022 J. Paul Getty Trust

Unless otherwise indicated, the text of this work and figs.1.4a–b are licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). All other images are reproduced with the permission of the rights holders acknowledged in captions and expressly excluded from the CC BY-NC license covering the rest of this publication. These images may not be reproduced, copied, transmitted, or manipulated without consent from the owners, who reserve all rights.