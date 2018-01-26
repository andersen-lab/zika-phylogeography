## Phylogeography of Zika virus from 1997 - Sep 2017

This analysis was produced based on data collected and generated as part of a large collaborative study to identify how Zika virus spread to Florida, USA during the 2016-16 Zika virus pandemic. For more details, please see [Grubaugh et al. 2017](https://www.nature.com/articles/nature22400).. The video shows the spatio-temporal diffusion of viral lineages between 1997 and 2017 that was generated by reconstructing the ancestral phylogeny ogf Zika virus. 

All genomic sequences are publicly available on GenBank. Tree was generated using [BEAST v1.8.4](http://beast.community/) under a SRD06 nucleotide substitution model and a relaxed molecular clock along with a Bayesian Skyline model. The BEAST XML file is available in [data](data/). The phylogeographic diffusion process was realised using a discrete state asymmetric CTMC. 

Rendered video for use under [CC-BY-SA-4](https://choosealicense.com/licenses/cc-by-sa-4.0/) available in [movie](movie/).

Rendered video on [Youtube](https://youtu.be/ul1KYj13Isw).

#### Inspired by [Phylogeography of 2014-2015 Ebola virus epidemic by Gytis Dudas](https://github.com/ebov/space-time).

#### Dependencies

* [baltic](https://github.com/blab/baltic)
* [Python 2.7](https://www.python.org/downloads/release/python-2714/)
* [basemap](http://matplotlib.org/basemap/)
* [pandas](https://pandas.pydata.org/)
* [numpy](http://www.numpy.org/)

#### Made with [Natural Earth](http://www.naturalearthdata.com/). 
![Natural Earth](NEV-Logo-color.png)

#### License
All content outside of [data/](data/) is  licensed under [CC-BY-SA-4](https://choosealicense.com/licenses/cc-by-sa-4.0/).
Natural Earth shapefiles in [data/ne_10m_admin_0_countries/](data/ne_10m_admin_0_countries/) are in public domain.

---
**Andersen Lab**  
The Scripps Research Institute  
La Jolla, CA, USA  
[data@andersen-lab.com](mailto:data@andersen-lab.com)
