# Image_Classification_and-Object_Detection
The Proceedings of the European Conference on Computer Vision has conducted a benchmark PASCAL Visual Object Challenge (VOC) evaluating performance on object class
recognition (from 2005-2012, now finished). For our task, we examine the VOC07 dataset which consists of several types of random images collected in January 2007 from Flickr.

## Data set
The PASCAL Visual Object Classes Challenge (VOC 2007) data set consists of about 9,000 256x256 RGB images of 20 classes. The twenty object classes that have been selected are:

-Person: person
-Animal: bird, cat, cow, dog, horse, sheep
-Vehicle: aeroplane, bicycle, boat, bus, car, motorbike, train
-Indoor: bottle, chair, dining table, potted plant, sofa, tv/monitor

## Feature Detection
We extracted the 3 mandatory features: 

1. MPEG-7 Color Layout Descriptor
2. Visual Bag-of-Words (BOV)
3. Speeded Up Robust Features.

## Feature Engineering

1. Class balancing by using Undersampling
2. Feature selection by using Analysis of Variance (ANOVA)
3. Feature selection by using Principal Component Analysis (PCA)

## Model Selection

1. Label Propagation
2. Label Spreading
3. GMM

## Model Evaluation

1. Class prediction error
2. ROC/AUC curves
3. Precision Recall Curves
4. Correlation Heatmap

## Baseline Comparision

We compare our work with a similar dataset on BOV features which was implemented using additive and exponential kernel-based supervised SVM classifiers. Their performances reported were in the range of 48.9%-52%. In comparison, our SSL techniques attain nearly 31% which are not superior to supervised counterparts.



