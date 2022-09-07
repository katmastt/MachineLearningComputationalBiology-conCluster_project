# MachineLearningComputationalBiology-conCluster_project

This is the final project of Machine Learning in Computational Biology course - MSc in Data Science and Information Technologies, Departement of Informatics and Telecommunications, National & Kapodistrian Uneversity of Athens. In this project we implemented an alternative pipeline [of this paper](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-018-0433-z). 

# Datasets

In the repository there are 2 different folders, one for each dataset. Each dataset was created from a recent scRNA-seq study. 

- The first dataset can be found on NCBI Gene Expression Omnibus with Geo accession GSE72056. It contains a cell expression matrix of 4645 cells found on melanoma tumors. - **data1.txt**

- The second dataset can be found on NCBI Gene Expression Omnibus with Geo accession GSE73727. It contains 72 different samples of transcriptional dissection of human pancreatic islets collected from the same donor. There are 72 different files, each with a different sample. To construct the second dataset we combined the 72 samples in one text file and we added the classification for each cell from the GSE73727 series matrix.txt file. - **data2_clusters.txt**

# Run

To run our project you should download the textfile and the python notebook of each dataset and place them in two different folders. When you run the notebooks some intermediate text files would be created in your folder. These files contain the altered cell matrix through the different steps of the pipeline. 
