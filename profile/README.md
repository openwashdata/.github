<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/openwashdata/brand/v1.1.0/logos/OWD-logo-05.png">
  <img src="https://raw.githubusercontent.com/openwashdata/brand/v1.1.0/logos/OWD-logo-01.png" alt="openwashdata" width="260">
</picture>

## Open data for water, sanitation and hygiene

openwashdata is a community that applies the FAIR principles to data from the water, sanitation and hygiene (WASH) sector, and teaches the skills to do it. The website is [openwashdata.org](https://openwashdata.org/).

### Find and install data

The [data catalogue](https://openwashdata.org/pages/gallery/data/) lists every R data package in this organisation. Each package has its own website and documentation. Install a package from GitHub, here with washmalawi as the example:

```r
# install.packages("devtools")
devtools::install_github("openwashdata/washmalawi")
```

Packages with a DOI are also built on the [openwashdata R-universe](https://openwashdata.r-universe.dev).

### Publish your data

The [FAIR Data Publishing guide](https://openwashdata.github.io/fair-publishing/) explains how to publish a dataset as an R data package with [washr](https://openwashdata.github.io/washr/). To propose a dataset, open an issue in [openwashdata/data](https://github.com/openwashdata/data/issues).

### Take part

- Subscribe to the [newsletter](https://openwashdata.org/pages/newsletter/), one email a month with a dataset, a story and the community's news.
- Join the [Matrix chat](https://matrix.to/#/#openwashdata-lobby:staffchat.ethz.ch), the community room that is open to everyone.
- Contribute on GitHub. The code, the data packages, the course and the website are open. Please read the [Code of Conduct](https://openwashdata.org/code_of_conduct) first.

***

Supported by the [Open Research Data Program of the ETH Board](https://ethrat.ch/en/eth-domain/open-research-data/) and [Global Health Engineering, ETH Zurich](https://ghe.ethz.ch/).
