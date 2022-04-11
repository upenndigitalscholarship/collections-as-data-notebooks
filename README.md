# Collections As Data Notebooks at Penn Libraries

These notebooks contain tutorials and examples for working with collections data from Penn Libraries.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/upenndigitalscholarship/collections-as-data-notebooks/HEAD)

## Working With Colenda Data
[Colenda Digital Repository at Penn Libraries](https://colenda.library.upenn.edu/) is a digital repository for digitized and born-digital material. It provides direct access and long-term stewardship for these important resources. Much of Colenda’s content consists of materials owned and digitized by the Penn Libraries, including significant collections that have been donated.

These notebooks use data from the [Arnold and Deanne Kaplan Collection of Early American Judaica](https://kaplan.exhibits.library.upenn.edu/) to explore how to work with data from Colenda.

* Explore Colenda Records (kaplan_explore_records): In this notebook we'll have a preliminary look at data harvested from Colenda. What kind of data and files can we access in Colenda? We'll introduce how to calculate basic shape/stats of the data, split and concatenate columns, and access images in the collection.

* Explore Colenda Items Over Time (kaplan_explore_time): In this notebook we'll explore the temporal dimensions of data harvested from Colenda. When were items created, collected, or used? To do that we'll extract the nested temporal data, see what's there, and create a few charts.

* Explore Colenda Items by Place (kaplan_explore_places): In this notebook we'll explore the spatial dimensions of data harvested from Colenda. What places are associated with these items? To do that we'll extract the spatial data, see what's there, and create a few maps.

## Working with OPenn Data

--
# Credits

Created by [Emily Esten](https://www.library.upenn.edu/people/staff/emily-esten). 

Judaica Digital Humanities at the <a href="http://library.upenn.edu">Penn Libraries</a> (also referred to as Judaica DH) is a robust program of projects and tools for experimental digital scholarship with Judaica collections, informed by digital humanities, Jewish studies, and cultural heritage approaches. Visit our [website](judaicadh.library.upenn.edu).

The pre-harvested dataset for this notebook works with items from the **Arnold and Deanne Kaplan Collection of Early American Judaica**. Donated to the University of Pennsylvania Libraries in 2012 by the Kaplans, and growing each year, this collection teaches us about the everyday lives, families, communal institutions, religious organizations, voluntary associations,  businesses, and political circumstances of Jewish life throughout the western hemisphere over four centuries. More information about the collection can be found at [https://kaplan.exhibits.library.upenn.edu](https://kaplan.exhibits.library.upenn.edu). 

This notebook references existing code and Jupyter notebooks, including: 
* [GLAM Workbench for the National Museum of Australia](https://doi.org/10.5281/zenodo.3544747) sponsored by the [Humanities, Arts and Social Sciences (HASS) Data Enhanced Virtual Lab](https://tinker.edu.au/).
* [Library of Congress Data Exploration: IIIF](https://github.com/LibraryOfCongress/data-exploration/blob/26510c3f4da0bc85dfa87e82141173b1830e9d64/IIIF.ipynb).
* Gustavo Candela, María Dolores Sáez, Pilar Escobar, Manuel Marco-Such, & Rafael C.Carrasco. (2020, May 8). hibernator11/notebook-iiif-images: release1.1 (Version 1.1). Zenodo. [http://doi.org/10.5281/zenodo.3816611](https://zenodo.org/badge/latestdoi/255172461). 
* [Genes for Project Cognoma](https://github.com/cognoma/genes/blob/721204091a96e55de6dcad165d6d8265e67e2a48/2.process.py)
