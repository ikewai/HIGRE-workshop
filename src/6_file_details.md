
# File Details

## File Formats

Land-cover and groundwater recharge rasters of two types are recognized by the application:

1. CoverageJSON (covJSON)
    * A JSON standard for representing gridded geospatial data
    * Information on this standard can be found [here](https://covjson.org/)
2. ASC
    * A simple ASCII format containing a 6 line header denoting positional data and a space separated grid of values

## Projection Files

Every gridded data file exported from the application comes with a projection (.prj) file. This application uses a Universal Transverse Mercator (UTM) map projection for its gridded data. This file contains information about the zone and datum used to create the grid's coordinates.

---

[Previous: Map State Export/Import](./5_map_state.md)

[Next: Other Application Components](./7_other_app_components.md)