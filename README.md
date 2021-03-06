#### Phylogeography of Zika virus from 1997 - Sep 2017

This analysis was produced using data collected and generated as part of a large collaborative study to identify how Zika virus spread to Florida, USA during the 2016-16 Zika virus pandemic. For more details, please see [Grubaugh et al. 2017](https://www.nature.com/articles/nature22400). The video shows the spatio-temporal diffusion of viral lineages between 1997 and 2017 that was generated by reconstructing the ancestral phylogeny of Zika virus. 

All genomic sequences used in the analysis are publicly available on GenBank. Tree was generated using [BEAST v1.8.4](http://beast.community/) under a SRD06 nucleotide substitution model and a relaxed molecular clock along with a Bayesian Skyline model. The BEAST XML file is available in [data](https://github.com/andersen-lab/zika-phylogeography/tree/master/data). The phylogeographic diffusion process was realised using a discrete state asymmetric CTMC. 

Rendered video is for use under [CC-BY-SA-4](https://choosealicense.com/licenses/cc-by-sa-4.0/) and available in [movie](https://github.com/andersen-lab/zika-phylogeography/tree/master/movie).

Rendered video on [Youtube](https://youtu.be/ul1KYj13Isw).

#### Inspired by [Phylogeography of 2014-2015 Ebola virus epidemic by Gytis Dudas](https://github.com/ebov/space-time).

#### Dependencies

* [baltic](https://github.com/blab/baltic)
* [Python 2.7](https://www.python.org/downloads/release/python-2714/)
* [basemap](http://matplotlib.org/basemap/)
* [pandas](https://pandas.pydata.org/)
* [numpy](http://www.numpy.org/)

#### Made with [Natural Earth](http://www.naturalearthdata.com/).

#### License
All content outside of [data/](https://github.com/andersen-lab/zika-phylogeography/tree/master/data) is  licensed under [CC-BY-SA-4](https://choosealicense.com/licenses/cc-by-sa-4.0/).
Natural Earth shapefiles in [data/ne_10m_admin_0_countries/](https://github.com/andersen-lab/zika-phylogeography/tree/master/data/ne_10m_admin_0_countries) are in public domain.

**Disclaimer**. Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!

---
**Andersen Lab**  
The Scripps Research Institute  
La Jolla, CA, USA  
[data@andersen-lab.com](mailto:data@andersen-lab.com)
