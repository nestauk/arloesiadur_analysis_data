# Industry composition data
Data for a visualisation presenting the composition of Wales economy and its Principal Areas by Industry. Includes information about the median salary and economic uniqueness of sectors, and estimates of future specialisation based on machine learning analysis.

## Data dictionary

* **Period**: 2011-2015
* **Unit of analysis**: locations (Wales and Welsh Local Authority districts)

Missing values indicated with *

See [here](https://arloesiadur.org/stories/analysing-industrial-data) for more information about data collection and processing

### Variables

* **location**: can be Wales or a Welsh Principal Area
* **industry**: industry
* **year**: year
* **employment**: number of employees in industry (rounded)
* **business_counts**: number of businesses in industry (rounded)
* **median_salary**: median salary in industry (£)
* **median_salary_decile**: median salary decile
* **uniqueness_score**: uniqueness score for industry based on complexity analysis (normalised index) 
* **uniqueness_decile**: uniqueness decile
* **high_prob_lads_n**: number of lads with high probability of becoming more specialised (only for location = Wales or London, otherwise it is *)
* **future_dev_prediction:** Probability that the location will gain specialisation in the area (only for LADs, missing (*) for Wales)
* **business_counts_lq**: business count Location quotient
* **employment_lq**: employment location quotient