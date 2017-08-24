# [In what tech topics do different parts of Wales specialise?](https://arloesiadur.org/themes/what-is-the-structure-of-the-tech-community-network-in-wales)

## Dataset 1: tags.csv

### Raw Data Source
* [Meetup](https://www.meetup.com/)

### Features
* **tag_name (str)**: Name of tags used by Meetup groups.
* **topic_name (str)**: The thematic category of a tag.
* **broad_topic (str)**: Aggregated version of the Topic.

## Dataset 2: tag_count.csv

### Raw Data Source
* [Meetup](https://www.meetup.com/)

###Features
* **tags (str)**: Name of tags used by Meetup groups.
* **count (int)**: Number of times the tag was used across the UK.

## Dataset 3: reduced_network.csv

### Raw Data Source

### Features
* **Source (str)**: Name of tags/source nodes used by Meetup groups.
* **Target (str)**: Number of tags/target nodes used by Meetup groups. This dataset leads to a maximum spanning tree.
* **Weight (int)**: Co occurrence of tags.

## Dataset 4: lq_tags_welsh_tags.csv

### Raw Data Source
* [Meetup](https://www.meetup.com/)
* [GeoJSON](http://martinjc.github.io/UK-GeoJSON/)

### Features
* **tag_name (str)**: Name of tags used by Meetup groups.
* **year (str)**: Year of reference.
* **Cardiff (float)**: Comparative advantage of Cardiff for a specific tag and year, in comparison to the rest of the UK.
* **Gwynedd (float)**: Comparative advantage of Gwynedd for a specific tag and year, in comparison to the rest of the UK.
* **Monmouthshire (float)**: Comparative advantage of Monmouthshire for a specific tag and year, in comparison to the rest of the UK.
* **Pembrokeshire (float)**: Comparative advantage of Pembrokeshire for a specific tag and year, in comparison to the rest of the UK.
* **Swansea (float)**: Comparative advantage of Swansea for a specific tag and year, in comparison to the rest of the UK.
* **Blaenau Gwent (float)**: Comparative advantage of Blaenau Gwent for a specific tag and year, in comparison to the rest of the UK.
* **Carmarthenshire (float)**: Comparative advantage of Carmarthenshire for a specific tag and year, in comparison to the rest of the UK.

## Dataset 5: lq_tags_wales_overall.csv
### Raw Data Source
* [Meetup](https://www.meetup.com/)
* [GeoJSON](http://martinjc.github.io/UK-GeoJSON/)

### Features
* **tag_name (str)**: Name of tags used by Meetup groups.
* **year (str)**: Year of reference.
* **Wales (float)**: Comparative advantage of Wales for a specific tag and year, in comparison to the rest of the UK.

## Dataset 6: network.json

### Raw Data Source
* [Meetup](https://www.meetup.com/)

**Note**: This JSON is the layout for the maximum spanning tree of the reduced_network.csv.
