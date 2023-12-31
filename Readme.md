<h1>Spatial Clustering Approach for Vessel Path Identification</h1>

This research work addresses the challenge of identifying the paths for vessels with operating routes of repetitive paths, semi-repetitive paths, and new paths. We propose a spatial clustering approach for labeling the vessel paths by using position information only. 
We develop a path clustering framework with either a distance-based or likelihood-based path modeling, combined with unsupervised machine learning (ML) techniques to improve the accuracy and efficiency of the clustering algorithm.
The result findings highlight the superior performance and efficiency of the developed approach.
The approach aims to offer valuable insights for planning of vessel paths, ultimately contributing to improving the safety and operation practices in the maritime transportation.

<h2>Framework of Vessel Path Identification</h2>
<p align="center">
  <img src="/icons/Framework_of_Vessel_Path_Identification.jpg" width="500" height="625">
</p>

<h2>Data Preprocessing and Analysis</h2>
<h3>Data Preprocessing</h3>
<p align="center">
  <img src="/icons/Fig_Cinderella_II_Ship.png" width="500" height="300">
</p>

<p align="center">
  <div style="display: flex; justify-content: space-between;">
    <img src="/icons/Fig_Cinderella_II_route.png" width="400" height="300">
    <img src="/icons/Fig_Cind_route_Dist_5paths.png" width="400" height="300">
  </div>
</p>

<h3>Data Analysis</h3>

<p align="center">
  <img src="/icons/Fig_Cind_5Paths_Stats_Hists.png" width="500" height="300">
</p>

<p align="center">
  <img src="/icons/Fig2_Cind_Fuel_Time_Hists.png" width="500" height="150">
</p>

<p align="center">
  <img src="/icons/Fig2_Cind_Distance_SOG_Hists.png" width="500" height="150">
</p>


<p align="center">
  <img src="/icons/Fig_Cind_route_Indv_5paths.png" width="700" height="400">
</p>


<h2>Distance-Based Method</h2>
<h3>Result of k-means or GMM clustering to five path classes</h3>

<p align="center">
  <img src="/icons/Fig2_Cind_5paths_by_Kmeans_GMM.png" width="700" height="400">
</p>

<p align="center">
  <img src="/icons/Fig_Cind_5paths_PDF_Misclustered.png" width="700" height="350">
</p>
<h3>Result of hierarchical clustering to five path classes</h3>

<p align="center">
  <img src="/icons/Fig_Cind_5paths_Hierarch2.png" width="1100" height="400">
</p>

<h2>Segmented Gaussian Likelihood Method</h2>

<p align="center">
  <img src="/icons/Fig_Cind_route_Dist_8Segs.png" width="500" height="300">
</p>

<p align="center">
  <img src="/icons/Fig_Cind_8paths_Gaussians_Lat_Lon.png" width="500" height="200">
</p>
<p align="center">
  <img src="/icons/Fig_Cind_7Segs_Gaussians.png" width="700" height="500">
</p>
