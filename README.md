# Cryptocurrencies
## Objective
Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system. 

> Resources:<br>
> Data: crypto_data.csv<br>
> Software: Python, Jupyter Notebook, VS Code, Pandas, Plotly, SKLearn, KMeans

## Results

* Data cleaning in preparation for training.
* Reduce dimensions using principal component analysis.
* Use Kmeans for clustering.
* Plot

The images below give a snapshot of the processes that took place in the steps above in order to create a classification system using unsupervised machine learning.

> Initial data file read in using Pandas
![crypto_df](https://user-images.githubusercontent.com/108758105/211185331-6062b325-5698-430a-bba2-3fab28621a8f.png)

> Dataframe after cleaning
![post_clean](https://user-images.githubusercontent.com/108758105/211185600-e08ebe05-23ee-4186-a41d-ddb49e6ec192.png)

> Chart showing result of three principal components from Principal Component Analysis
![3pc](https://user-images.githubusercontent.com/108758105/211185387-f0b73478-c490-4bd2-8549-3a61599e6327.png)

> Elbow curve finding the best value for K
![elbow_curve](https://user-images.githubusercontent.com/108758105/211185352-dc196f97-1d35-49ea-989f-c7be3948b054.png)

> Post-run of the K-means algorithm to make predictions of the K clusters for the cryptocurrencies’ data
![prediction](https://user-images.githubusercontent.com/108758105/211185785-cbd36da6-2074-4021-bb74-4216bbc27e29.png)

> Clustered dataframe snapshot 
![clustered_df](https://user-images.githubusercontent.com/108758105/211185720-cf838600-9081-4509-a513-1df4c5394c7c.png)

> 3D scatter plot using the Plotly Express to plot the three clusters from the clustered dataframe
![scatter_plot](https://user-images.githubusercontent.com/108758105/211185900-97f30dcd-ad44-4956-ac95-941f1abc5c12.png)


