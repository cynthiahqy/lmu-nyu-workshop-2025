# xmap demo

The `xmap` package implements a new data structure for mapping data between statistical classifications. I am still figuring out how to build out smooth and user-friendly workflows for transforming and harmonising data using this data structure. In this workshop, I want to explore the how best to support the import and/or specification of mappings between classifications, and the potential of using LLMs in this task.

## Set up

### R Package Installation

Install the development version of the package in a recent version of R (>4.1): [`remotes::install_github("cynthiahqy/xmap")`](https://github.com/cynthiahqy/xmap)

### LLM Access 

You need some access to an LLM. Ideally via ellmer + API key (see https://ellmer.tidyverse.org for setup instructions), but using web-based chat (e.g. chatGPT.com, claude.ai) is also fine.

### BYO Example Task and/or Data

Bring a small sample of data from your own category harmonisation task. This will likely be two classifcations that you need to map between, and a subset of the data you want to merge/integrate -- e.g. hierarchical adminstrative areas [(simple example)](https://cynthiahqy.github.io/xmap/articles/xmap.html#example-country-state-mappings), standard occupation or industry codes

