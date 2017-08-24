# [How have tech networks changed over time?](https://arloesiadur.org/themes/how-have-tech-networks-changed-over-time)

## Dataset 1: attendant_cooccurrence_in_groups.csv

### Raw Data Sources
* [Meetup](https://www.meetup.com/)

### Features
* **group1 (str)**: Name of a Meetup group.
* **group2 (str)**: Name of a Meetup group.
* **year (str)**: The year for which the co occurrence is examined.
* **normalised_attendant_cooccurrence (float)**: Takes values in the range [0,1]. Shows the strength of the overlap between groups, where overlap is the number of users that attended events of both groups in the same year.

## Dataset 2: groups_attendants_events.csv

### Raw Data Sources
* [Meetup](https://www.meetup.com/)

### Features
* **group_name (str)**: Name of a Meetup group.
* **event_date (str)**: The year of reference.
* **number_of_events (int)**: Number of events a Meetup group organised in a specific year.
* **number_of_attendants (int)**: Number of users that attended the events of a Meetup group organised in a specific year.

## Dataset 3: metadata.csv

### Raw Data Sources
* [Meetup](https://www.meetup.com/)
* [GeoJSON](http://martinjc.github.io/UK-GeoJSON/)

### Features
* **link (str)**: URL to the profile of a group on Meetup.com.
* **main_topic (str)**: Topic with the highest probability of a Meetup group.
* **LAD13NM_LGDName (str)**: Local Authority of the Meetup group. Only Welsh groups are contained.
* **clean_description (str)**: Description of the Meetup group, as it was found on Meetup.com.