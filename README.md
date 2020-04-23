# Sidewalk Widths DC

Inspired by [Sidewalk Widths NYC](https://github.com/meliharvey/sidewalkwidths-nyc)

Sidewalk Widths DC uses [Washington DC's](https://opendata.dc.gov/datasets/sidewalks) to produce a map of sidewalk widths for the District.

This repo contains the notebooks to reproduce this work, as well as the finished Sidewalk Width dataset in GeoJSON format.

## Link
[www.sidewalkwidths.dc](http://www.sidewalkwidths.dc)

## Methodology

1) Polygons from DC open data
![Sidewalk Polygons](assets/sidewalk_polygons.png)

1) Dissolve adjacent sidewalk polygons
![Sidewalk Polygons Dissolved](assets/sidewalk_polygons_dissolved.png)

2) Find sidewalk centerlines
![Centerlines](assets/centerline.png)

3) Remove short ends and simplify
![Centerlines Simplified](assets/centerline_simplified.png)

4) Measure distance from centerlines to original polygon
![Centerlines Widths](assets/centerline_widths.png)
