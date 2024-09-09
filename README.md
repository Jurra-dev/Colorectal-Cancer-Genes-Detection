# Colorectal-Cancer-Genes-Detection

*Summary*: In this work, we integrated different types of biological information associated with the genetic understanding of the origin and development of the disease, coupling it to the most detailed protein-protein interaction map that exists. Subsequently, we performed fundamental analyses on classical measures of the topology of the constructed network, which were useful to identify key elements of the network. We assigned weights to the nodes and edges of the network according to the biological information, which was a fundamental procedure to prioritize network elements (proteins) associated with cancer and specifically with colorectal cancer. Based on this information and the constructed network, we implemented modularity algorithms to identify specific communities that could be specifically associated with the development of colorectal cancer, and finally we implemented algorithms to characterize non-overlapping communities and specific machine learning strategies to find potential proteins associated with colorectal cancer.

- *Criterios.xslx*: This file contains the node weight information according to the importance of each main characteristic.
- *asyn_lpa_communities_excel*: This file contains the results of the Asynchronous LPA Communities algorithm.
- *greedy_modularity_excel*: This file contains the results of the Greedy Modularity Communities algorithm.
- *louvain_algorithm*: This file contains the results of the Louvain algorithm.
- *new_angel_algorithm*: This file contains the results of the New Angel algorithm.
- *v2_ipca_algorithm*: This file contains the results of the V2 IPCA Algorithm.
- *Deteccion_de_comunidades*: This is the Python file that processes the different community detection algorithms.
- *Louvain.gephi*: This is the GEPHI file that contains the Graphic results of the Louvaing algorithm.
- *Pu_Learning*: This file contains the PU Learning Machine Learning algorithm processing.
- *SMOTE_GSMOTE*: This file applies the SMOTE and GSMOTE strategy tho the dataset.
