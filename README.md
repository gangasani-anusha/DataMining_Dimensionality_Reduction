## **Dimensionality Reduction:**

The transformation of data from a high-dimensional space into a low-dimensional space so that the low-dimensional representation retains some meaningful properties of the original data, ideally close to its intrinsic dimension.

In this colab demonstration of various dimensionality reduction techniques we have used the following:

### **Definitions:**
**1. Principal Component Analysis:**

It's a linear mapping of the data to a lower-dimensional space in such a way that the variance of the data in the low-dimensional representation is maximized.

**2. Singular value decomposition:**

It can be used to reduce the dimensionality, i.e., the number of columns, of a data set.

**3. Locally Linear Embedding:**

It is an unsupervised learning algorithm that produces low-dimensional embeddings of high-dimensional inputs, relating each training instance to its closest neighbor.

**4. T-distributed Stochastic Neighbor Embedding:**

It is a statistical method for visualizing high-dimensional data by giving each datapoint a location in a two or three-dimensional map.

**5. Isometric Mapping:**

It is a simple method for estimating the intrinsic geometry of a data manifold based on a rough estimate of each data point’s neighbors on the manifold.

**6. Uniform Manifold Approximation and Projection:**

It assumes that the data is uniformly distributed on a locally connected Riemannian manifold and that the Riemannian metric is locally constant or approximately locally constant.


### **Implementation:**

**-** Applied **PCA analysis** on an image data by reducing its dimensionality to 5 and 200 components and for the text data reduced the components to 3, used scatter plot_3D for visualization

**-** After reducing the dimensionality displayed image data with various components and for the text data we have defined an array to apply the **SVD technique** 

**-** Displayed the swiss roll dataset and applied **Locallay Linear Embedding** method on it, for the text data applied this technique on the digits data and displayed using the scatter plot

**-** Imported a circles image data set to apply **t-SNE method** and for text used plotly express carshare data

**-** Implemented the **Isometric mapping** technique on the circles data set to 3 components and and for text digits data and displayed using the scatter plot

**-** Used the mnist dataset for **UMAP procedure** and displayed the carshare data from plotly express in the 3D scatter plot

## **References:**

https://towardsdatascience.com/dimensionality-reduction-for-data-visualization-pca-vs-tsne-vs-umap-be4aa7b1cb29

https://pair-code.github.io/understanding-umap/

https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.735.8417&rep=rep1&type=pdf
