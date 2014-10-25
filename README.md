# Scaling Up: Image Processing and Analytics using Spark
__[The presentation](https://rawgit.com/4Quant/xrm-big-data/master/xrmBigDataPres.html)__
## Kevin Mader (4Quant and ETH Zurich)
The presentation given at the XRM 2014 Big Data satellite workshop on image processing on large, diverse datasets using [Apache Spark](http://spark.apache.org) as a back-end.

Kevin Mader is a lecturer in the X-ray Microscopy Group within the Department for Information Technology and Electrical Engineering at ETH Zurich. His research focuses on turning big hairy 3D images into simple, robust, reproducible numbers without resorting to black boxes or magic. In particular, as part of several collaborations, he is currently working on automatically segmenting full animal zebrafish images, characterizing rheology in 3D flows, and measuring viral infection dynamics in cell lines.

## Abstract
With improvements in flux, detector efficiency, and reconstruction algorithms, the rate at which image data is produced in Synchrotron-based X-ray Tomographic Microscopy is staggering. At the TOMCAT beamline of the Swiss Light Source, this rate reaches 8GB per second [1], higher than even multinational companies with dedicated IT staff like Facebook or Instagram usually handle. We have developed a scalable framework based on Apache Spark and the Resilient Distributed Datasets proposed in [2] for parallel, distributed, real-time image processing and quantitative analysis. The framework extends easily from single machines to clusters and even cloud-based solutions. With sufficient computational power, real-time data exploration and hypothesis testing over millions of structures is possible. The tools have been tested on clusters containing thousands of machines and images containing more than 100 billion voxels. The flexible infrastructure [3] offers a full spectrum of filtering, segmentation, shape, distribution, and connectivity metrics for cellular materials and networks. It can furthermore be adapted and integrated with the availability of 3rd party libraries to handle new studies or different types of analysis (like spectral-imaging) without significant changes. The framework paves the way for a new era of detailed, customizable investigations of studies with high sample counts ranging from long-term dynamics and evolution experiments to investigations of drug-gene interactions.

### References

- [1] Mokso, R., Marone, F., & Stampanoni, M. (2009). Real-Time Tomography at the Swiss Light Source. In AIP Conf. Proc. SRI2009.
- [2] Zaharia, M., Chowdhury, M., Das, T., Dave, A., Ma, J., McCauley, M., … Stoica, I. (2012). Resilient distributed datasets: a fault-tolerant abstraction for in-memory cluster computing, 2.
- [3] Mader, K, Donahue, LR., R. Müller, M. Stampanoni, High-throughput, Scalable, Quantitative, Cellular Phenotyping using X-Ray Tomographic Microscopy, IWBBIO 2014, (Accepted)

## Learn more at 
- 4Quant: From Images to Statistics - http://www.4quant.com
 - DeepZoom images: http://people.ee.ethz.ch/~maderk/dz/tomcat.html
- Spark Demo from this presentation - https://gist.github.com/kmader/755c2d99c23f4cbe2e74
- Setting up Spark on a Cluster
 - using Sun Grid Engine - https://github.com/4Quant/sge_spark
 - using MPI Jobs - https://bitbucket.org/skicavs/spark-on-brutus)
- Setting up Spark on the Cloud https://4quant.github.io/aws-spark-introduction

### Imaging
- X-Ray Imaging Group at ETH Zurich - http://bit.ly/1gD8wKb
- Quantitative Big Imaging Course at ETH Zurich - http://bit.ly/1kj9mnq
- Presentation at Spark Summit 2014 - https://rawgit.com/4Quant/spark-summit-2014-presentation/master/ssPresentation.html
- Simple Hyperspectral Example - https://gist.github.com/kmader/e6fb564f4c180b87042f
- Flat-field correction and sinogram creation demo - https://gist.github.com/kmader/7cce1e04f74fdc990dfe

### Beyond Image Processing
- FEM Demo using GraphX - https://gist.github.com/kmader/6456262935af381c8dbe


