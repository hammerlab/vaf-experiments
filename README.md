# About 
This repository contains a series of Python notebooks (structured as blog posts) that are meant to walk the reader through understanding how to use variant calls to make educated guesses about the tumor biology. The ultimate goal is to build a utility from scratch that will take a Variant Call Format (VCF) file as input and output an annotated version of it with metrics of clonality, purity and heterogeneity.

# Table of Contents

* [0 - What is a variant allele frequency?](./0%20-%20What%20is%20a%20variant%20allele%20frequency%3F.ipynb)

# Setup
For exploration in read-only mode, there is no need to install additional software or libraries. All notebooks can be browsed within the GitHub repository [through its integration with nbviewer](http://blog.jupyter.org/2015/05/07/rendering-notebooks-on-github/).

The suggested way to interact with and modify these notebooks is to first create an isolated Python environment using [miniconda](http://conda.pydata.org/miniconda.html) utility and then installing all the requirements as follows:

```bash
$ conda create --name vafexperiments python
$ source activate vafexperiments
$ pip install -r requirements.txt
$ jupyter notebook  # and browse individual notebooks
```