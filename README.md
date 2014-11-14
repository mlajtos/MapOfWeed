# The Map of Weed

This repository is dedicated to creating The Map of Weed.

## Goal

There are many different strains of Cannabis. Every strain has its own characteristic set of effects on the human body and mind. One can easily get lost in the complexity of the effects, flavors and conditions when to use one or another strain. To ease this frustration, one needs a simple way to find structure in all the complexity of this herb.

## Data

[Leafly.com](http://leafly.com/) provides best source of the data on the strains. Every strain has few attributes which describe the effects, flavor and other features of the strain. All available informations can be accessed by an API which provides a way to collect the this dataset and leverage it to create *The Map of Weed*.

## Method

Every strain has a number of attributes that are specific for each strain. One can represent a strain by vector of numerical attributes which enables to directly compare strains in the high-dimensional space. [t-SNE](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding) is algorithm designed to reduce dimensionality and at the same time preserve structure of the high-dimensional data. This leads to visualizations that can display the complexity of the high-dimensional space embedded in low dimensional space.

## Output

The output of this experiment will be an interactive map of all Cannabis strains in form of scatter plot, where one can examine all strains in a visual fashion, while allowing to filter them based on the interactive controls.
