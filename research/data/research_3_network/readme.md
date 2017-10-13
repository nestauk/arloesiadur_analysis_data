# Reasearch capabilities data
Data for a network visualisation representing existing research collaboration networks in Wales and opportunities for new collaborations.

* **Period**: 2006-2016 (totals) 
* **Source**: [Gateway to Research](http://gtr.rcuk.ac.uk/) 
* **Unit of analysis:** Organisations (including universities and businesses collaborating in Research Council-funded research projects with universities)

See [here](https://arloesiadur.org/stories/how-we-used-research-data-in-arloesiadur) for more information about data collection and processing

The data is available in 2 files:

## node_metadata.csv

### Variables:
* **active_in_topic:** Research topics that the organisation is active on
* **lad:** Principal area where the organisation is based
* **lat:** Latitude
* **lon:** Longitude
* **org:** Name of the organisation
* **project_count:** Number of projects the organisation has participated on
* **recommendations:** Other organisations to collaborate with

## 19_5_2017_revised_edge_list.csv

### Variables
* **n1:** Name of node 1 (organisation)
* **n2:** Name of node 2 (organisation)
* **weight:** Number of collaborations