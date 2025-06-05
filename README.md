# xmap demo

The [`xmap` package](https://cynthiahqy.github.io/xmap/index.html) implements a new data structure for mapping data between statistical classifications. I am still figuring out how to build out smooth and user-friendly workflows for transforming and harmonising data using this data structure. In this workshop, I want to explore the how best to support the import and/or specification of mappings between classifications, and the potential of using LLMs in this task.

## Resources

- slides: <https://cynthiahqy.github.io/talk_LMU-20250604/>
- STATA script example: <https://github.com/cynthiahqy/example_narrow-occpns>

## Talk Abstract

> Social science research often involves harmonising data from multiple sources. For example, analysts often must resolve differences between country-specific occupation classification standards to compare labour statistics from multiple countries. Harmonised datasets involve both domain expertise and technical data-wrangling skills. Unfortunately, details of the harmonisation logic are often lost in the idiosyncrasies of bespoke data preparation scripts and ad-hoc documentation, making it difficult for others to validate or reuse harmonisation efforts. The {xmap} package addresses these challenges with a new framework and tools for data harmonisation using 'crossmap' tables. The crossmap framework unifies and simplifies the specification, implementation, validation, and documentation of recoding, aggregating and splitting operations. Crossmaps extend existing crosswalk/look-up table approaches to support one-to-many and many-to-many relationships between alternative classification standards, in addition to one-to-one and many-to-one recoding. The package also provides built-in safeguards to avoid data leakage and graph-based methods for standardised documentation.

### R Package Installation

Install the development version of the package in a recent version of R (>4.1): [`remotes::install_github("cynthiahqy/xmap")`](https://github.com/cynthiahqy/xmap)

### LLM Access 

You need some access to an LLM. Ideally via ellmer + API key (see https://ellmer.tidyverse.org for setup instructions), but using web-based chat (e.g. chatGPT.com, claude.ai) is also fine.

### BYO Example Task and/or Data (OPTIONAL)

Bring a small sample of data from your own category harmonisation task. This will likely be two classifcations that you need to map between, and a subset of the data you want to merge/integrate -- e.g. hierarchical adminstrative areas [(simple example)](https://cynthiahqy.github.io/xmap/articles/xmap.html#example-country-state-mappings), standard occupation or industry codes

