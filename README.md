# Etc

## Notes

FastAI
* progressive resizing = train a model at 64x64 then 128x128 then256x256
* start w/ a model that's already somewhat trained 
* if train loss > valid loss, you're underfitting.  try more epocs or training unfrozen at a lower learning rate
* 1/2 precision training https://docs.fast.ai/basic_train.html#to_fp16
* Tensor = an array.
* Tensor = data in a rectangular pattern.  Could be Rank (number of dimensions) 1, 2, 3, etc.
* In math, normally it’s rows x columns.  So a 640 x 480 photo (640 width x 480 height) would normally be referred to as 480 x 640 when taking about math.
* Rank = number of axises.  An image is rank 3 (w x h x d).
* Vector = 1 dimensional array
* Matrix = 2 dimensional array
* Coefficients = paramaters
* Matrix Product = Matrix Multiplication 

## InterestingStuff
Things to come back to later...

### GIS
* [National Map](https://viewer.nationalmap.gov/basic/) (geo data and imagery download)
* [GIS Geography](https://gisgeography.com/) (lots of good info on GIS)
* [GDAL](https://www.gdal.org/gdal_translate.html) (geo data and imagery manilulation from command line)
* [Video: Intro to GDAL](https://www.youtube.com/watch?v=N_dmiQI1s24)
* [QGIS](https://www.qgis.org/en/site/index.html) (open source GIS software similar to ESRI)
