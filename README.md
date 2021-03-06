

### Online harvesting of correspondence between brands and consumers' visual associations

#### FILES

- `Compare_LDA_from_sklearn_And_gensim.ipynb` - short compersament of `gensim` and `sklearn` LDA
- `Download_datasets.ipynb` and `Download_files.py` - scripts for downloading Amazon datasets
- `LDA_PCA_PERPLEXITY_MAIN.ipynb` - Preprocessing of Amazon dataset, [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation), [PCA](https://en.wikipedia.org/wiki/Principal_component_analysis), plots, wordclouds, embeddings
- `NMF_final.ipynb` - Implementation of [Non-negative matrix factorization](https://en.wikipedia.org/wiki/Non-negative_matrix_factorization)
- `results` - mostly `*.pickle` files which are used by `*.ipynb` notebooks, and some `*.xlsx` files for NMF results. 
- `nmf_tailoring` - `*.pickle` files and datasets for NMF

Project type:
Application/Original


A brief synopsis:

There is a significant problem in marketing that firms sometimes do not know which visuals trigger consumers' associations with their brand name and how they can alter these associations. As a result, the majority end up trying to influence consumers' by erotic content, producing advertisments that many consumers find boring. Most importantly, since visual assotiations these ad's are trying to establish are not product-related, this badly affects revenues.
Our team will try to measure potential consumers' associations with brands. We will use a dataset consisting of the results of online survey asking people to create a collage out of several photos expressing their associations with a brand name, and to answer some questions regarding their perception of the brand characteristics. After potential consumers create collages the survey uses Clarifai API to make via CNNs a list of tags corresponding to a particular visual the person used.
 

Project's scope:

Natural Language Processing

 

Project's outline:

Our team's goals are:
1) The main priority is to divide the large set of tags into a smaller number of topics using Latent Dirichlet Allocation (LDA), Non-negative Matrix Factorization (NMF)
2) By using word embeddings, word clouds, and, finally, human ability to interpret, we want to achieve the best topic extraction quality that gives interpretable results convertible into a setup of business decisions
3) After we get interpretable topics we would like to predict which characteristics do people assign to a brand depending on their visual associations

 

Team name: Great Marketologists

Team members:

- Ilya Feshchenko
- Anna Vlasova
- Daria Ryabukhina
- Mohammad Ali Sadri
- Dejan Dzunja

 

