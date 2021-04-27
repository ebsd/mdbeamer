This is a base template for generating *Beamer* presentations from *Markdown*
source, with a custom theme.

See: <http://blog.rom1v.com/2014/02/des-slides-beamer-en-markdown/>

### Install dependencies

    sudo apt-get install pandoc \
                         texlive-latex-base \
                         texlive-lang-french \
                         texlive-fonts-recommended \
                         latex-beamer \
                         impressive

### Compile

    make

### Run

    make run

### Adapt

 * Edit `slides.md`;
 * Change the logos and colors in `beamerthemeCustom.sty`.

### yaml

```
# vider le contenu de title, authors et date pour une première page vide
title: "Titre"
author: "Auteur"
date: "xx.xx.20xx"
output: 
  beamer_presentation:
classoption: "aspectratio=169"
```
