# Replication of [Henderson et al. 2019](https://www.nature.com/articles/s41593-019-0457-5)
Mathieu Bourdenx - Thomas E. Paul - 2021

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5379631.svg)](https://doi.org/10.5281/zenodo.5379631)

This repository contains the article and figures for the replication, now published in [ReScience C](https://rescience.github.io/). 
The code to reproduce the figures is located in another [repository](https://github.com/MathieuBo/PathoSpreading).



### [ReScience C](https://rescience.github.io/) article template

This repository contains the Latex (optional) template for writing a ReScience
C article and the (mandatory) YAML metadata file. 

#### Usage

For a submission, fill in information in
[metadata.yaml](./metadata.yaml), modify [content.tex](content.tex)
and type:

```bash
$ make 
```
This will produce an `article.pdf` using xelatex and provided font. Note that you must have Python 3 and [PyYAML](https://pyyaml.org/) installed on your computer, in addition to `make`.

After acceptance, you'll need to complete [metadata.yaml](./metadata.yaml) with information provided by the editor and type again:

```bash
$ make
```
(C) 2015-2020, Nicolas Rougier + co-authors GPL-3+, Apache v2+, SIL Open Font License

This set of template files is free-licensed. The files contained in
the sub-directories roboto/; source-code-pro/; source-sans-pro/;
source-serif-pro/; have their free licences indicated with a
"*License.txt" file. All other files, including this one, are licensed
under the GPL version 3 or later, at your choosing, by Nicolas Rougier
and co-authors, 2015-2020. See the file COPYING for details of the
GPL-3 licence.
