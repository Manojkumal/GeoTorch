# GeoTorch: A Spatiotemporal Deep Learning Framework

GeoTorch is a python library on top of PyTorch and Apache Sedona.

## GeoTorch Modules
GeoTorch contains various modules for data preprocessing, ready-to-use raster and grid datasets, and neural network models:

* Datasets: Conatins processed popular datasets for raster data models and grid based spatio-temporal models. Datasets are available as ready-to-use PyTorch datasets.
* Models: PyTorch wrapper for popular raster data models and grid based spatio-temporal models.
* Transforms: Various tranformations operations that can be applied to dataset samples during model training.
* Preprocessing: Supports preprocessing of raster and spatio-temporal datasets in a scalable settings on top of Apache Spark and Apache Sedona. Users don't require the coding concepts of Apache Sedona and Apache Spark. They only need to code on Python while PySpark and Apache Sedona implementations are a black box to them.

## Dependency Set up
Following libraries need to be set up before using GeoTorch.

##### Dependencies for Deep Learning Module:
1. PyTorch 1.10
2. Rasterio
3. Scikit-image

##### Dependencies for Preprocessing Module:
1. PySpark 3.0.0
2. Apache Sedona 1.2.0-incubating

## Documentation
Details documentation on installation, API, and programming guide is available on [GeoTorch Website](https://kanchanchy.github.io/geotorch/).

## Other Contributions of this Project
We also contributed to [Apache Sedona](https://sedona.apache.org/) to add transformation and write supports for GeoTiff raster images. This contribution is also a part of this project. Contribution reference: [Commits](https://github.com/apache/incubator-sedona/commits?author=kanchanchy)


