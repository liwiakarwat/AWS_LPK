# ASEiED project - Measuring System

## Contributors
* Piotr Nieścior
* Liwia Karwat
* Jakub Giembicki

## Descroption (task 1)

### Problem
Analyze the data containing information on elevation variation by selecting groups of areas with the highest growth (continental Europe). Elevation growth in a given location should be measured from at least 10 measurement points. Determine 5 groups of areas in relation to the average value of height increase. Please plot the detected areas on the map.

### Technologies
* Amazon EMR
* S3 cloud storage
* JupyterEnterpriseGateway 2.1.0, Spark 2.4.8, Livy 0.7.1

### Dataset
From Amazon Simple Storage Service (Amazon S3) we can download a global dataset providing bare-earth terrain heights. We are using the terrarium format. Link to source dataset:
https://registry.opendata.aws/terrain-tiles/

### Solution
We solved the problem used the the numpy.gradient method and PySpark kernel.
The result image of the detected areas with 5 groups of specific height increase below:\
![](https://github.com/liwiakarwat/AWS_LPK/blob/main/image.png)

