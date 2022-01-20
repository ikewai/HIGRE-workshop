
# Built-in Tools

The Hawaii Groundwater Recharge Tool provides users with tools for modifying land-cover and defining areas of interest directly from the in-tool map using leaflet's drawing tools.

## Defining Custom Areas

In the upper left corner of the map, there are drawing tools that can be used to draw custom areas on the map. The land cover for these areas can then be modified for analysis. Additionally, custom areas include their own groundwater-recharge metrics.

Three types of drawing tools are provided:

1. Polygon tool
    * Allows users to define an arbitrary number of shape vertices on the map to enclose an area.
2. Rectangle tool
    * Creates a simple rectangle by clicking and dragging.
3. Single cell tool
    * Allows for a single map cell to be selected for adding fine detail to areas.

## Updating Land-Cover Values

Once a set of areas have been created, the land cover can be modified by clicking on a land-cover type in the left panel.

Additionally, instead of converting the entire area to a single land-cover type, a land-cover mapping can be created using the "Create Advanced Mapping" button. This will bring up a menu allowing specific land-cover types within the selected area to be converted to a different land cover. For example, a mapping could be created that converts alien forest to native forest and grasslands to developed, low-intensity. A default land-cover type can also be specified which will convert any land-cover types with no specific rule.

## Changing The Rainfall Scenario

The "Climate" section in the left hand panel allows the rainfall scenario to be switched between the baseline rainfall and future projection. By default, switching the rainfall scenario will not change the default groundwater-recharge rates used by the application. Changing the rainfall scenario to the future projection will cause the application to report the change in rainfall between this and the baseline scenario for the entire map. To change this behavior, the "Update Default Scenario" option can be selected. This will cause groundwater-recharge rate changes from land-cover modifications to be compared to the groundwater-recharge rates for the selected rainfall scenario.

## Viewing Groundwater-Recharge Changes

Once the desired land-cover modifications are made and desired rainfall scenario is selected, switch to the groundwater-recharge visualization. This will display the estimated change in groundwater-recharge rates.

### Visualization Options

By default the map will display the modified groundwater-recharge for the island. Two color schemes are provided for this, a polychromatic orange-blue gradient and a monochromatic white-blue gradient based on preference. These can be changed with the "Color Scheme" dropdown in the left panel.

The visualization style can also be changed to show groundwater-recharge percent change or difference using the "Visualization Style" dropdown menu.

### Metrics Displays

The bottom panel displays computed metrics for the updated groundwater-recharge values. By default this will display metrics for the entire island. Metrics for different areas of interest can be displayed by selecting an option in the "Data Mode" section of the left panel. Four modes are provided.

1. Display data by cell
    * Clicking on the map selects a single map cell to display metrics for.
2. Display custom area data
    * One or more custom areas (the areas drawn on the map) can be selected and metrics will be displayed for these areas.
3. Display aquifer data
    * One or more aquifers can be selected to display metrics for.
4. Display full map data
    * The default option, displays metrics for the entire map.


### Caprock Toggle

Areas of caprock can be excluded from the computed metrics by toggling the "Include Caprock" option in the bottom panel when in full map or aquifer mode. The caprock boundaries can be viewed by enabling the caprock layer in leaflet's layer controls in the top right of the map (the same menu used to switch between the land-cover and groundwater-recharge visualizations).

## Generating a Report

A comprehensive report of the groundwater recharge rate changes can be generated by clicking the "Generate Report" button in the right panel. This will create a separate window in the tool containing a breakdown of the groundwater-recharge metrics for all the areas of interest on the map.

This report can be downloaded as a PDF by clicking the "Download as PDF" button in the upper right corner of this window.

---

[Previous: Application Layout](./1_app_layout.md)

[Next: Importing Custom Areas](./3_import_areas.md)