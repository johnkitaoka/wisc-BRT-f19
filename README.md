# Redundant Bus Routes in the City of Madison

With the new BRT transportation system months away from breaking ground, we set out to find any inefficiencies that this rapid transportation system would cause to the existing traffic network. This repository contains Jupyter notebooks as well as various public data samples in order to log current progress. 

## Methodology

Establishing a solid visual context was the first concern, using Geopandas and DataFrame. The data contained geographic measures so route overlays were possible within a single plot. 

<image></image>

Preprocessing involved categorization of certain existing bus stops within walking distance to a proposed BRT stop location. Since the new transportation network is centered around rapid transportation, the difference in timing involved with each route arrival and departure was minimal. 
We classified walking distance as within a half kilometer, or about a 5 minute walk. 

<image></image>


### Results

On average, about 17% of the total existing bus stops were redundant. However, a closer look at the findings reveals that those inefficient bus stops had about 16% higher ridership, located in most high-density areas of the city. 
Certain routes also had much higher proportions of inefficient stops than others.

<image></image>

Of these routes, we reccommend elimination of routes 25, 67, 12 and 1 because these routes alone would cost an excess of $132, 000 annually to maintain based off of budget estimates of $2,500 per stop.


## Authors

* **John Kitaoka**  - [John's Github](https://github.com/johnkitaoka)
* **Hunter Olson**  - [Hunter's Github](https://github.com/hjolson01)
* **Jin Woo Lee**  - [Jin's Github](https://github.com/jinlee487)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
