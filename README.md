# Background on enhancer gene link prediction

All the cells in the human body have the same DNA, but they look different and perform different functions. Why is this? It turns out that different genes are active in different cell types. Special regions in the genome called enhancers help the cell decide which genes to turn on at a given time. Enhancers are stretches of DNA around 10-1000bp long. When active, they recruit RNA polymerase to transcribe their targeted genes. Different enhancers are active in different cell types, leading to different genes being activated. To understand how different cell functions are encoded in our DNA, it is crucial to map out which enhancers regulate which genes in a given cell type. 

Although there are many methods capable of predicting enhancer-gene links, some were created for another application and need to be adapted to predict enhancer gene links. They were run on different, small datasets, and their predictions were evaluted by different metrics against different gold standards. This project seeks to unify these methods. The best performing pipelines will be implemented on one common platform. They will be run on pooled datasets from ENCODE and NIH Roadmap Epigenomics Consortiums, and their predictions compared a set of prevailing gold standards. 
