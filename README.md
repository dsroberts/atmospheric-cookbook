<img src="https://github.com/COSIMA/logo/blob/master/png/logo_word.png" width="800"/>
<br/> <br/>

<a href="https://cosima-recipes.readthedocs.io/en/latest">
    <img alt="latest docs" src="https://img.shields.io/badge/docs-latest-blue.svg">
</a>

# Atmospheric Cookbook

An Atmospheric Cookbook 📔 of Recipes for analysing regional or global atmospheric model output. 👩🏽‍🍳 👨🏻‍🍳

We explain: a "recipe" here is an example an analysis of some atmospheric model output or some atmosphere-related observational datasets.
Each "recipe" comes in a self-contained and well-documented Jupyter notebook.
All the recipes combined form a cookbook 📒!

To access the data used in these recipes you need an account with the Australian-based [National Computational Infrastructure (NCI)](https://nci.org.au/).

To **get started**, clone this repository in your local space on one of the NCI HPC machines so you can have access to model output. You should then be able to run these recipes (i.e., example analyses) through an [Australian Research Environment (ARE)](https://are.nci.org.au/) JupyterLab session running python or via any other way you might want to run a Jupyter notebook on an NCI HPC machine. You need to join projects _hh5_, _xp65_, _ik11_, _cj50_ and _ol01_ to run the recipes and access the data analysed.

If you plan to use an ARE session, then remember to include the projects in the _Storage_ line: `gdata/xp65+gdata/ik11+gdata/cj50+gdata/hh5+gdata/ol01` as well as any of your own project you need access to. In _Module directories_, set `/g/data/hh5/public/modules` and in _Modules_ set `conda/analysis3`. Use a _Compute Size_ of `large` or greater.

If you have never used the NCI see these [first steps instructions](https://access-hive.org.au/getting_started/first_steps/) and [getting started with ARE](https://access-hive.org.au/getting_started/are/).

### Contributing

Have you made a recipe for analysing something that is not already included in this cookbook?
You are more than welcome to share it and include it in the cookbook!
Consider **contributing your recipe back to the repository**.
We are always delighted to expand our cookbook with more recipes.
If the process of contributing to the repository sounds a bit intimidating to you, rest assured that we will guide you and help you with submitting your contribution.

To make a contribution just raise [an issue](https://github.com/COSIMA/cosima-recipes/issues) explaining briefly what the contribution you want to make is and we'll help out with the process!


## Contents


### [Recipes](https://cosima-recipes.readthedocs.io/en/latest/recipes.html)
The main part of this cookbook: All the recipes! These are Jupyter notebooks for either simple or not-so-simple diagnostics and analyses. All notebooks are aimed to be self-contained and  well-documented and explained.
If you can find a recipe that suits your purposes, then this is the best place to start.
