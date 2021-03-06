## Visualization information for the tool

Automatic visualisation is created automatically from QGIS plugin. It uses Natural Breaks divison with ready defined colorscheme. QML-files for the visualisation:

- [CO2_t_grid](CO2_t_grid.qml) NOTA BENE! Maximum value can vary between different calculations, check the results before proceeding with the analysis!

- [CO2_sources](CO2_sources.qml) NOTA BENE! Different emission sources may vary in different situations, in this we have visualizes traffic, electricity, heating and renovation as the main sources of emissions.

### Additional visualizations

If you want to add visualization for the population grids, you can join the population information to the grid, you can use this file (population field is called 'v_yht'):

- [Population](Population.qml)

### Example

[Examples](CO2_visualisoinnit.pdf) of possible end results.

## SLD for GeoServer

[SLD's](visualizations_SLD) have been also created, they can be used e.g. with GeoServer.

[SLD for CO2 emmissions per grid](visualizations_SLD/co2_emissions.sld)

### Additional SLD-files from grids:

[SLD for population grids](visualizations_SLD/population.sld)

[SLD for top emission source per grid cell](visualizations_SLD/top_emission_source_per_grid_cell.sld)

Example with all grid layers:

![Example of SLD for grids](visualizations_SLD/sld_grids.png)

### SLD-file for zoning elements (not part of the plugin, but if you want to join grid information for zoning)

[SLD for top emission source per land use planning zones](visualizations_SLD/top_emission_source_per_land_use_planning_zones.sld), example:

![Zoning ](visualizations_SLD/seuranalueet_ei_laatikoita.JPG)
