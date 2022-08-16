# Frankfurt-Trees

Small project to analyze the trees of Frankfurt, based on data made available by the city's Grünflächenamt.

## Data

The data is available at the [Frankfurt's Open Data portal](https://www.offenedaten.frankfurt.de/dataset/baumkataster-frankfurt-am-main), and can be visualized by its [geo tool](https://geoportal.frankfurt.de/karte/?layerIds=55037,55033,55035,118,28&visibility=true,true,true,true,true&transparency=0,0,0,0,0&center=477500,5551000&zoomLevel=4#).

The coordinate system in use by the database is the ETRS89/UTM 32N (EPSG:25832), and should be handled accordingly.

## Goals

The following goals and vizualizations should be met for project completion:
:white_square: A map visualization of the trees' location;
:white_square: A chart correlating planting year and height;
:white_square: A chart of main regions by number of trees;
:white_square: A chart of change in the number of trees;
:white_square: A chart of trees by type of location;
:white_square: A chart of top locations, by type of location and number of trees;
:white_square: A chart of radius and age;
:white_square: A chart of radius and age per neighbourhood;
:white_square: A chart of radius and height;
:white_square: A chart of radius and height per neighbourhood;
:white_square: The street with most trees, and by neighbourhood.

### Stretch goals

These are the tasks that are not mandatory for the *done* status, but would be nice to have them.

- Automated database update;
- Map vizualization with tooltip containing information on the trees;
- Map vizualization with a selector of which metric / information to show;
- A Github page with such a dashboard.
