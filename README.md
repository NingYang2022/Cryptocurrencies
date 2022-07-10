# <font color=#6495ED>Cryptocurrencies</font>

## <font color=#6495ED>Project Overview</font>

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. We were asked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

### <font color=#6495D>Purposes</font>

- Preprocess the data for PCA
- Cluster data using K-means
- Reduce data dimensions using PCA
- Visualize cryptocurrencies results

## <font color=#6495ED>Resources</font>

### <font color=#6495D>Data Source: </font>
crypto_data.csv from  [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

### <font color=#6495D>Software:</font> 
- Anaconda with python 3.9
- Jupyter Notebook
- Libraries: Pandas, hvPlot, Plotly and Scikit-learn

## <font color=#6495ED>Results</font> 
### Preprocess the data for PCA

![df_crypto](https://github.com/NingYang2022/Cryptocurrencies/blob/main/Images/df_crypto.png?raw=true)

### Cluster data using K-means

![K-means_Elbow_Curve](https://github.com/NingYang2022/Cryptocurrencies/blob/main/Images/K-means_Elbow_Curve.png?raw=true)

### Reduce data dimensions using PCA

![pcs_df](https://github.com/NingYang2022/Cryptocurrencies/blob/main/Images/pcs_df.png?raw=true)

### Visualize tradable cryptocurrencies results

- 3D Scatterplot with PCA data and the Clusters

![3D_Scatter_PCA_data_and_clusters](https://github.com/NingYang2022/Cryptocurrencies/blob/main/Images/3D_Scatter_PCA_data_and_clusters.png?raw=true)

- 2D hvplot of scatters with MinMax scaled data and cluster index

![hvplot_scatter_plot](
https://github.com/NingYang2022/Cryptocurrencies/blob/main/Images/hvplot_scatter_plot.png?raw=true)


