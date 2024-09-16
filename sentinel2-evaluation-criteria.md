# Sentinel-2 Data Provider Evaluation Criteria

| Criteria Category | Specific Criteria | Description |
|-------------------|-------------------|-------------|
| Cloud Detection   | Overcorrection | Extent of over-removal of valid data points |
|                   | Undercorrection | Failure to remove cloud-contaminated data |
| Spectral Performance | Performance across landcover types | Accuracy across different landcover types |
|                       | Performance in varied topography | Accuracy in different terrains, including south slopes and shadows |
| Ease of Access    | Download options | Availability of straightforward download methods |
|                   | STAC protocol support | Support for SpatioTemporal Asset Catalog protocol |
|                   | GEE processing capability | Ability to process data directly on Google Earth Engine |
| Data Availability | Temporal extent | Years of data available |
|                   | Seasonal coverage | Availability throughout the year vs. only during growing season |
| Spectral Information | Available spectral bands | Number and types of spectral bands provided |
| Long-term Reliability | Project continuity | Likelihood of continued data production |
| Preprocessing     | Atmospheric correction algorithm | Method used for atmospheric correction |
|                   | Topographic correction | Application and method of topographic correction |
|                   | Co-registration | Use of image co-registration techniques |
| Special Features  | Unique processing techniques | Any provider-specific data enhancements |
| Quality Assessment | Displacement values | Provision of displacement information (for co-registered products) |
|                    | Confidence metrics | Availability of quality or confidence indicators |
| Support           | Technical assistance | Availability of technical support or user community |
| Derived Products  | Additional datasets | Availability of derived products (e.g., NDVI, Vegetation Health Index) |
| Update Frequency  | Data refresh rate | Frequency of new data availability or processing updates |
| Cost              | Pricing structure | Any costs associated with data access or processing (even if free) |
| Documentation     | User guides and technical docs | Quality and completeness of available documentation |
| Data Format/Projection | File formats and spatial reference | Available file formats and output map projections |

## Notes on Criteria

1. **Spatial Resolution**: Not included as it's the same across providers for Sentinel-2 data.
2. **Cost**: Included for completeness, even though most or all providers may offer free access.
3. **Documentation**: Included to assess the quality and availability of user guides and technical information, which can impact usability.
4. **Data Format/Projection**: Combined to cover both the file formats available and the spatial reference systems used.
5. **Derived Products**: Replaced "Ancillary Data" to focus on value-added products generated from the Sentinel-2 data.
6. **Update Frequency**: Added to reflect how often new or updated data becomes available from each provider.

This table now reflects a comprehensive set of criteria for evaluating Sentinel-2 data providers, tailored to your specific needs and considerations.
