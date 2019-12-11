# kaggle-2019-BigQuery-Geotab-Intersection-Congestion
This repository contains some of my codings for the 2019 kaggle BigQuery Geotab competition (https://www.kaggle.com/c/bigquery-geotab-intersection-congestion).

The challange was to predict six measures for cars approaching intersections in four US cities.

My objective in the competition was to tryout BigQuery (BQ) including the basic ML features. Therefore the notebooks rely as much as possible on BQ. All features are generated in BQ with varying SQL-techniques. The prediction model is also build in BQ.

## Overview of notebooks

- **BigQuery-GeoTab [BQML]**: My final solution for the competition
- **BQML population of zip code per intersection:** Feature of population per zipcodes and intersections
- **BQML incl. intersecition clusters:** Early submission to the competition including clustering
