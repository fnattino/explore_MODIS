# Explore MODIS datasets

Using `conda` (`mamba`) and the `environment.yaml` file we setup an environment with the relevant libraries:

```python
mamba env create -f environment.yaml
```

References:

* [MODIS/Terra Vegetation Indices 16-Day L3 Global 250m SIN Grid](https://lpdaac.usgs.gov/products/mod13q1v061/)
* [STAC CMR collection](https://cmr.earthdata.nasa.gov/cloudstac/LPCLOUD/collections/MOD13Q1.v061) (also in [STAC browser](https://radiantearth.github.io/stac-browser/#/external/cmr.earthdata.nasa.gov/cloudstac/LPCLOUD/collections/MOD13Q1.v061))
* [Read CMR data (HLS) in the cloud](https://lpdaac.usgs.gov/documents/842/HLS_Tutorial.html)
* [Zarr EOSDIS store](https://github.com/nasa/zarr-eosdis-store/tree/main): read HDF5/NetCDF files using Zarr library.
* Read MODIS HDF4 in Python:
  * [tutorial 1](https://www.earthdatascience.org/courses/use-data-open-source-python/hierarchical-data-formats-hdf/open-MODIS-hdf4-files-python/)
  * [tutorial 2](https://nordicesmhub.github.io/forces-2020/example-notebooks/read-hdf4-xarray.html)
