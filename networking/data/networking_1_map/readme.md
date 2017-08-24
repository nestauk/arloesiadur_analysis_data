# [What are the connections between tech communities in Wales and other parts of the UK?](https://arloesiadur.org/themes/what-are-the-connections-between-tech-communities-in-wales-and-other-parts-of-the-uk)

## Dataset 1: inward_broad_topics_probs.csv

### Raw Data Source
* [Meetup](https://www.meetup.com/)
* [GeoJSON](http://martinjc.github.io/UK-GeoJSON/)

### Features 
* **member_registered_location (str)**: Local Authority where a Meetup user was registered.
* **Cardiff (float)**: Probability of a user to leave the LAD where he/she registered and visit Cardiff for a Meetup event on a specific Topic.
* **Gwynedd (float)**: Probability of a user to leave the LAD where he/she registered and visit Gwynedd for a Meetup event on a specific Topic.
* **Monmouthshire (float)**: Probability of a user to leave the LAD where he/she registered and visit Monmouthshire for a Meetup event on a specific Topic.
* **Pembrokeshire (float)**: Probability of a user to leave the LAD where he/she registered and visit Pembrokeshire for a Meetup event on a specific Topic.
* **Swansea (float)**: Probability of a user to leave the LAD where he/she registered and visit Swansea for a Meetup event on a specific Topic.
* **Topic (str)**: The thematic category of an observation.

## Dataset 2: outward_broad_topics_probs.csv

### Raw Data Source
* [Meetup](https://www.meetup.com/)
* [GeoJSON](http://martinjc.github.io/UK-GeoJSON/)

### Features 
* **member_registered_location (str)**: Local Authority where a Meetup user was registered. Only Welsh local authorities are used.
* **Topic (str)**: The thematic category of an observation.
* The rest of the columns contain non-Welsh Local Authorities and their values show the probability for a Meetup user to visit these areas from a Welsh LAD.
