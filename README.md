# SRR1_notebooks

## User Story 1: Access of pre-computed ARD data for Sentinel 1 and 2 over a large area 

This user story covers the access of pre-computed ARD Sentinel 1 and 2 data over a large area. Ten MGRS tiles are accessed. It is shown that the grids align which makes analysis and further processing more convenient and precise since resampling steps are not required anymore. The CARD4L compliant metadata is presented. 

## User Story 2: Interactive timeseries analysis from pre-computed and on-demand ARD data 

This user story shows how to retrieve time series trajectories from pre-computed and on-demand ARD data. The focus lies on facilitating the access to time series data through interactive selection of pixels or small polygons in the client and receiving time series directly. This allows for quick access and comparison of time series of spectral bands or indices such as NDVI for optical data or sigma to gamma ratio for SAR backscatter. 

## User Story 3: On-demand processing of Sentinel-1 data 

This user story demonstrates the capabilities of the ARD backscatter generation for Sentinel-1 data. CARD4L compliant data will be generated using the process ard_normalized_radar_backscatter including according metadata. The custom parametrization will be shown using the process sar_backscatter. 

## User Story 4: On-demand processing of Sentinel-2 data 

This user story demonstrates the capabilities of the ARD surface reflectance generation for Sentinel-2 data. CARD4L compliant data will be generated using the process ard_surface_reflectance including according metadata. The possibilities of custom parametrizations will be demonstrated as well as the differences between different atmospheric correction methods (e.g., FORCE, iCor).  
