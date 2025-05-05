# GLS_FCS30_2000-2022_annual_China

## Description
Dataset
- GLC_FCS30: global land-cover product with fine classification system at 30 m using time-series Landsat imagery 2000-2022
- Official data access: data.casearth.cn/dataset/6523adf6819aec0c3a438252
- Spatial scope: China
- Time scale: 2000-2022

## Process
- The data is freely available on the official website, but the dataset itself is too large, with more than seventy tif files nationwide alone, and each tif file packaged with 23 sub-maps, making it difficult to use directly.

- Frequently encountered memory overflow problems when I tried to use my personal pc for merge operations.Because of the difficulties in data processing, only five years of data are currently available on the market.

- After I downloaded the data from the official website, I extracted all the tif raster data of China region using the school supercomputing platform, split all the sub-maps from 2000-2022 and merged them to get 23 annual tif files, and added the tif statistical data using arcgis.

## Assets
- https://pan.baidu.com/s/1OcFmWQxIHenZJoWfocNRVQ?pwd=hucz
- Don't forget to star if it helps😊💕


