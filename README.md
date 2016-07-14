Fennica: tools and analyses for the Finnish national bibliography
============================================

This repository contains automated analysis of the Finnish national bibliography, [Fennica](http://www.kansalliskirjasto.fi/kirjastoala/fennica.html), together with full soure code. Fennica includes metadata for over 70,000 documents printed in Finland between 1488-1955, and is analyzed in parallel with [Kungliga](https://github.com/ropengov/kungliga), a related collection of bibliographic metadata from the Swedish National library.

For more info of the overall research project funded by Academy of
Finland 2016-2019, see the [project
page](https://www.helsinki.fi/en/researchgroups/digital-humanities-helsinki/projects#section-13696).


### Analysis overview

The data is summarized in the following automatically generated files:

 * [Fennica bibliography: an overview](https://github.com/rOpenGov/fennica/blob/master/inst/examples/overview.md)
 * Knowledge production in Finland/Sweden 1470-1828: Digital Humanities 2016 conference presentation slides ([PDF](https://github.com/rOpenGov/fennica/blob/master/inst/examples/20160715-slides-Krakow.pdf)) and [code](inst/examples/20160715-slides-Krakow.Rmd)
 * [Digital History in Finland seminar, University of Helsinki, Dec 9, 2015](https://github.com/rOpenGov/fennica/blob/master/inst/examples/20151209-HelsinkiDH.md)
 * [Analyses on specific publication places and other topics](https://github.com/rOpenGov/fennica/tree/master/inst/examples) (see the .md files) 
 * [Further notes on preprocessing](https://github.com/rOpenGov/fennica/blob/master/inst/examples/summary.md)

The analyses include several steps including XML parsing, data
harmonization, removing unrecognized entries, enriching and organizing
the data, carrying out statistical summaries, analysis, visualization
and automated document generation. The full source
code](https://github.com/rOpenGov/fennica/blob/master/inst/examples/main.md
is provided in this repository.

The full source code and analysis outputs can be freely reused under
the [BSD 2 clause](https://opensource.org/licenses/BSD-2-Clause)
(FreeBSD) open source licence. The analyses are based on the
[R](http://r-project.org) statistical programming environment, and
rely on the custom
[bibliographica](https://github.com/ropengov/bibliographica) package
for bibliographic data analysis, as well as many other R packages. The
original raw data is available only on a separate agreement, so we are
here publishing only the statistical summaries and our own analysis
code.


### Contact

The tools are under active open development and the tools, analysis,
and documentation are being constantly updated. You can support the project by

  * [sending suggestions and bug reports](https://github.com/ropengov/fennica/issues)
  * [pull requests](https://github.com/ropengov/fennica/) (we will acknowledge contributions)
  * join IRC at !ropengov@Freenode
  * [star this github project](http://ropengov.github.io/contribute/)


### Acknowledgements


The project is part of [rOpenGov](http://ropengov.github.io/).


Main contributors:

  * [Leo Lahti](https://github.com/antagomir/)
  * [Mikko Tolonen](https://github.com/orgs/rOpenGov/people/tolonen)
  * [Jani Marjanen]()  
  * [Hege Roivainen](hegroiva)  
  * [Niko Ilomaki](https://github.com/NVI/)


Funding:

  * [Academy of Finland](https://www.kansalliskirjasto.fi/en/projects/comhis-computational-history-and-the-transformation-of-public-discourse-in-finland-1640)


Special thanks for data and other support:

  * [Finnish National library](https://www.kansalliskirjasto.fi/en/)

  * [Väestörekisterikeskus](http://vrk.fi/) Finnish first name-gender
    mappings and demographic information

  * [Maanmittauslaitos](http://mml.fi) Geographic information

  * [Tilastokeskus](http://www.tilastokeskus.fi/) Demographic information

  * [Open Street Map](https://www.openstreetmap.org) Geographic information
  
  * [Open Knowledge Finland ry.](http://fi.okfn.org/)

