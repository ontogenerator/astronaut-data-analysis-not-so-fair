[![DOI](https://zenodo.org/badge/776011771.svg)](https://zenodo.org/doi/10.5281/zenodo.12699084)

## Not so FAIR astronaut data analysis code

This repository contains a helper software project with some code to be used 
for the [FAIR research software course](https://github.com/carpentries-incubator/fair-research-software). 

This repository is an example of "not so FAIR" software that is meant to be improved over the course to show examples of better 
and more FAIR software practices. 

Various branches of this repository represent the state of the code as it should be at the start of each of the course episodes:

- [branch 01-introduction](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/01-introduction) matches the code at the start of episode ["1. Course introduction"](https://carpentries-incubator.github.io/fair-research-software/01-introduction.html)
- [branch 02-fair-rs](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/02-fair-rs) matches the code at the start of episode ["2. FAIR research software"](https://carpentries-incubator.github.io/fair-research-software/02-fair-research-software.html)
- [branch 03-tools](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/03-tools) matches the code at the start of episode ["3. Tools and practices for FAIR RS development"](https://carpentries-incubator.github.io/fair-research-software/03-tools.html)
- [branch 04-version-control](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/04-version-control) matches the code at the start of episode ["4. Version control"](https://carpentries-incubator.github.io/fair-research-software/04-version-control.html)
- [branch 05-code-readability](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/05-code-readability) matches the code at the start of episode ["5. Code readability"](https://carpentries-incubator.github.io/fair-research-software/05-code-readability.html)
- [branch 06-code-testing](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/06-code-testing) matches the code at the start of episode ["6. Code testing"](https://carpentries-incubator.github.io/fair-research-software/06-code-testing.html)
- [branch 07-documenting-code](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/07-documenting-code) matches the code at the start of episode ["7. Documenting code"](https://carpentries-incubator.github.io/fair-research-software/07-documenting-code.html)
- [branch 08-open-collaboration](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/08-open-collaboration) matches the code at the start of episode ["8. Open project collaboration & management"](https://carpentries-incubator.github.io/fair-research-software/instructor/08-open-collaboration.html)
- [branch 09-code-ethics](https://github.com/carpentries-incubator/astronaut-data-analysis-not-so-fair/tree/09-code-ethics) matches the code at the start of episode ["9. Ethical considerations for research software"](https://carpentries-incubator.github.io/fair-research-software/instructor/09-code-ethics.html)
- Finally, repository [astronaut-data-analysis-fair repository](https://github.com/carpentries-incubator/astronaut-data-analysis-fair) contains the code that participants should have at the end of the course (an example of a good software project structure and code)


### What the code does
The code uses the [NASA data on human space walks (Extravehicular activities - EVAs)](https://data.nasa.gov/Raw-Data/Extra-vehicular-Activity-EVA-US-and-Russia/9kcy-zwvn/data_preview), 
exported/downloaded in JSON format, does some analysis over this data, plots a few graphs and saves the data in CSV format. 

### Things to improve
There is a number of things that are wrong or not so FAIR with this code and that can be improved. We maintain that list at issue
https://github.com/carpentries-incubator/astronout-data-analyses-bad/issues/2.

### Better code
An example of better and more FAIR code that participants should strive to achieve when writing their reseach software 
can be found at the [astronaut-data-analysis-fair repository](https://github.com/carpentries-incubator/astronaut-data-analysis-fair), 
to be used in conjuction with this repository during the course - this is the code that participants should have at the end of the course.

### Acknowledgements

#### Data

The data used on in this project was obtained from NASA as follows.

Data source: https://data.nasa.gov/Raw-Data/Extra-vehicular-Activity-EVA-US-and-Russia/9kcy-zwvn/about_data.

Either export data from the above page using the `Export` button or download in JSON format from command line as: 

`curl https://data.nasa.gov/resource/eva.json --output eva-data.json`

**Note: the original data has been modified for the purposes of this tutorial by inserting a semicolon separator after each name in the `crew` field.**

#### HIFIS 
The idea for this software has been borrowed from the ["Astronaut analysis" workshop material](https://gitlab.com/hifis/hifis-workshops/make-your-code-ready-for-publication/astronaut-analysis) 
by [Helmholtz Federated IT Services (HIFIS)](https://gitlab.com/hifis).

#### Software Sustainability Institute and UKRN

This work has been supported by the [UK's Software Sustainability Institute](https://software.ac.uk) via the [EPSRC, BBSRC, ESRC, NERC, AHRC, STFC and MRC grant EP/S021779/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/S021779/1)
and [UK Reproducibility Network (UKRN)](https://www.ukrn.org/).


#### Software Sustainability Institute and UKRN

This work has been supported by the [UK's Software Sustainability Institute](https://software.ac.uk) via the [EPSRC, BBSRC, ESRC, NERC, AHRC, STFC and MRC grant EP/S021779/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/S021779/1)
and [UK Reproducibility Network (UKRN)](https://www.ukrn.org/).
