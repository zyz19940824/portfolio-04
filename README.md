# Portfolio

## Maps

**DUE:** April 26, 2019, Noon.

*Note:* This exercise is to be completed as part of your final exercise portfolio submission.


## Before You Begin

This visualizations should be built utilize `template.html` from your [`exercise-portfolio`](https://github.com/umiami-data-viz/exercise-portfolio).


## Instructions

Create one **choropleth map** and one **interactive map** using *only* [d3](https://d3js.org/) (and [lodash](https://lodash.com) if necessary).

Each visualization should be in a separate file (i.e. `choropleth.html`, `interactive-map.html`) in your exercise portfolio.

Make sure each visualization has all required details (i.e. a title, text description, labels, axes, legends, etc.) — not just the data!


### Data

#### GeoJSON

Included in `data/geojson` are two geoJSON files provided — `world.json` and `us-states.json` — depending on the visualizations you choose to create. For each map, you will need to select the correct geoJSON dataset to use as well as an acceptable projection.


#### UNESCO World Heritage Sites

Included in `data` is `unesco-world-heritage-sites.csv` which contains a list of countries and the number of UNESCO World Heritage Sites within its borders.


#### United States Veterans

Included in `data` is `united-states-veterans.csv` which contains a breakdown of veteran populations (and percentage of total population over 18) by state. These statistics are further broken down by time period (wars in which the veterans served).


#### Wonders of the World

Included in `data` is `seven-ancient-wonders.csv` and `seven-modern-wonders.csv`. These list the seven ancient and modern wonders, a timeframe of when the wonder was constructed and coordinates.


### Choropleth Map

Create a choropleth of either the UNESCO World Heritage Sites or United States Veterans. In the case of the latter, display either total veteran percentage (`veteran_pct`) of each state or the veteran percentage of a given war (i.e. `pct_terror` for the War on Terror (Afghanistan, Iraq), `pct_gulf` for the Gulf War (1991), `pct_wwii` for World War II, etc.)

In both cases, remember to merge your data with the geoJSON object created by d3. Use one of [d3-scale-chromatic's color schemes](https://github.com/d3/d3-scale-chromatic) for the map and legend.


### Interactive Map

Create a map which plots the locations of the Seven Ancient and Modern Wonders of the world. Merge the datasets in JavaScript. (*DO NOT* copy these files into one csv; import both csv files, and merge the data into one object.)

For each location, add an HTML tooltip which lists information about the site, such as the name and years needed to construct. Can you make the tooltip for the Ancient Wonders display more information?

*Bonus:* For an extra 2.5 points on your portfolio exercise grade, implement zoom/reset functionality on this map. Be sure to include limits.


## Submitting Your Work

**Email Prof. Brown with a link to your exercise portfolio no later than April 26, 2019, Noon.**

Late submissions or incomplete exercises will receive a zero (0).


## Review

This exercise is due as part of your final exercise portfolio submission. These will not be reviewed in class. Be sure to submit a working, detailed exercise as points will be deducted for incomplete or broken visualizations.


## Reminder

Students are expected to complete these visualizations individually. Do not copy/paste code from notes, exercises or the book. **Your code is expected to be unique.**

Students who have identical (or near-identical) code will earn a zero on the assignment when portfolios are graded.

**Good luck!**
