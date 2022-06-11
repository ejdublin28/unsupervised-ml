# unsupervised-ml

Adding the dummy variables for Algorithm and ProofType drastically increased the size of the dataframe increasing it from 6 columns to 96 columns. The number of features was reduced after using PCA, the number of columns in the PCA dataframe was 74.

After running t-SNE and plotting the results, it appears that there is at least one distinct cluster in the middle of the graph. This cluster could potentially be broken into smaller clusters as well, providing further distinction from the main cluster and the outer ring around the periphery of the main grouping. 

Based on the elbow 'curve', it seems like the cryptocurrencies that are currently trading could be clustered into three groups. However, with the data cleaning steps at the beginning and the filters that were applied - maybe additional data (going back and finding values to fill Na or nulls) could improve the ability to cluster the cryptocurrencies.