
# Local Government Election Results as Hexbin-Maps

Vizualisation of the local government elections results in Baden-Wuerttemberg in 2014. The maps show where the most important parties had there strongholds. Strongest color = highest voting rates.

## Vizualisation

Used the [d3-hexbin-plugin](https://github.com/d3/d3-hexbin) to transform single lat-lon-points of the local communities into a heatmap based on hexagonal objects

## Data Source

The election data is published by the statistical office of Baden-Wuerttemberg as a [single csv-file for every community](https://www.statistik-bw.de/Wahlen/Kommunal/02045000.tab?R=GS111000). Used small scraping script to create one single file for all results.
