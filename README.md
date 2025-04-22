# Motif-based Clustering for Retail Time Seires

**Abstract**

One of the biggest obstacles for retailers is to identify and act on the changing sales of the products. The fact that several retail channels use time series data with high dimensionality and heterogeneity makes traditional clustering techniques prone to failure. The work at hand proposes a new method for the clustering of retail sales time series through the motif discovery technique. Given the fact that subsequence clustering has been around for sometime, the contribution of the current work is a framework, which applies the Matrix Profile method to discover motifs in retail time series, capturing similarities between sales patterns. The low memory and low computational costs are what makes the Matrix Profile method fast, exact, robust, and scalable. For the current work, we analyzed the sub-categories of products. We called our approach MoClust to refer to Motif-based Time Series Clustering via Matrix Profile for Retail. The application of the motifs found to reduce dimensionality of the whole time series is the first step of our algorithm. After that, the clustering method is applied to these motifs to detect the different temporal sales patterns of the product sub-categories. Our experiments carried out on the retail dataset showed that the MoClust outperforms traditional raw time series clustering when combined with Matrix Profile distance (MPDist) compared to distance measures such as Euclidean and Dynamic Time Warping (DTW). The primary business goal of the work of this thesis is retail customer segmentation.

## Project setup

Attached is the jupyternote book `motif_clustering.ipynb` for the project walkthrough. To run it:
 
- install the packages: `pip -m requirements.txt`

## References:

- <a href="https://www.cs.ucr.edu/~eamonn/MatrixProfile.html" target="_blank">Matrix Profile Official Page</a>
- <a href="https://www.cs.ucr.edu/~eamonn/PID4481997_extend_Matrix%20Profile_I.pdf" target="_blank">Matrix Profile I: All Pairs Similarity Joins for Time Series</a> 
- <a href="https://www.cs.ucr.edu/~eamonn/consensus_Motif_ICDM_Long_version.pdf" target="_blank">Matrix Profile VII: Time Series Chains</a>
- <a href="https://www.cs.ucr.edu/~eamonn/MPdist_Expanded.pdf" target="_blank">Matrix Profile XV: Exploiting Time Series Consensus Motifs to Find Structure in Time Series Sets</a>
- <a href="https://www.cs.ucr.edu/%7Eeamonn/chains_ICDM.pdf" target="_blank">An Ultra-Fast Time Series Distance Measure to allow Data Mining in more Complex Real-World Deployments</a>
