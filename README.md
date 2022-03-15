# Rock-Type-Prediction
A machine learning approach to using well log data in describing electrofacies, reducing the need for mineralogy quantification (which is an expensive process) 

**Description of the problem**
Well Logs data can be used in describing electrofacies. These well logs are used as feed input in determining clusters.
With the availability of actual mineralogy data, in some wells, I attempt to use the well log data for supervised learning.
Actual mineralogy quantification is quite expensive, hence machine learning
 With the rock type clusters, saturation and resistivity data can be compared to identify sweet spots in the reservoir

**Dataset**: Volve field 

**Workflow Description**

Acquire mineralogy data & well log data:
  - Mineralogy and Well Log Data should match depth
  - Cleaned Log Data removing outliers in GR and NPHI log 

Perform unsupervised learning on mineralogy data:
  - Mineralogy data: Composition of Quartz, Shale, Carbonates
  - K-means and Ward Hierarchical Clustering

Perform supervised learning on well log data:
  - Features: Gamma Ray Log, Neutron Porosity Log, Density Log
  - Labels:  Rock Type
  - Algorithms:  K Nearest Neighbors (KNN), Support Vector Machines  (SVM), Random Forest  (RF)

Add noise to dataset and evaluate impact of noise on the various machine learning algorithms.






