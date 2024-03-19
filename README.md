# data-analysis through ML approach using R
exploratory data analysis (EDA) of "Flavors of Cacao" Dataset and scRNA-seq Data

## Part 1: Flavors of Cacao Data Analysis

### Overview
This section presents an exploratory data analysis (EDA) of the "Flavors of Cacao" dataset. The analysis aims to uncover factors influencing chocolate bar ratings and identify characteristics associated with high-quality chocolate.

### Dataset
The dataset used for this analysis is "Flavors of Cacao":
![image](https://github.com/yeela8g/data-analysis/assets/118124478/ca9c2434-66af-4c05-907a-8868951ac2b7)
This dataset includes various attributes of chocolate bars such as cocoa percentage, origin country, company information, and ratings.

### Analysis Workflow
The analysis follows a structured workflow, including data loading, cleaning, correlation analysis, insights, and follow-up research questions.

#### Data Loading and Exploration
The dataset is loaded, and its structure is explored using R.

#### Data Cleaning
- Conversion of values to numerical values.
- Removal of columns with limited information.

#### Correlation Analysis
Investigation of the correlation between chocolate rating and cocoa percentage/Broad Bean Origin/company related information and more features in order to identify and understand key determinants of chocolate quality and consumer preferences.

#### Insights and Follow-up Questions
Summarization of key findings and identification of follow-up research questions for further exploration.

### Conclusion
The analysis provides insights into factors influencing chocolate ratings, including cocoa percentage, bean origin, company location, and bean type. These findings can guide further research and inform chocolate manufacturing practices.

## Part 2: scRNA-seq Analysis of Mouse Lung Cells using ML techniques

### Overview
This section presents a single-cell RNA sequencing (scRNA-seq) analysis of lung cells isolated from an adult mouse organism. The analysis aims to identify different cell types present in the lung tissue.

### Dataset
The dataset used for this analysis consists of RNA sequencing data obtained from lung cells isolated using the 10x Genomics platform and sequenced using Illumina NovaSeq 6000.

### Analysis Workflow
The analysis includes data loading, pre-processing, identification of variable features, principal component analysis (PCA), cluster identification, visualization, differential expression analysis, and cell type annotation.

#### Data Loading and Pre-processing
- Loading the raw data and creating a Seurat object.
- Filtering out low-quality cells based on mitochondrial gene expression and unique feature counts.
- Normalizing and scaling the data.

#### Identification of Variable Features
Identifying genes exhibiting high variation in expression across cells.

#### Principal Component Analysis (PCA)
Performing PCA to reduce the dimensionality of the dataset and visualize cell clusters.

#### Cluster Identification
Clustering the cells based on shared gene expression profiles using the KNN algorithm.

#### Visualization
Visualizing cell clusters using uniform manifold approximation and projection (UMAP).
![image](https://github.com/yeela8g/data-analysis/assets/118124478/6bb58e5c-2417-4c39-b2d4-4c590e7b5d84)


#### Differential Expression Analysis
Identifying marker genes for each cluster through differential expression analysis.

#### Cell Type Annotation
Assigning cell types to clusters based on gene expression profiles using the SingleR package.
![image](https://github.com/yeela8g/data-analysis/assets/118124478/41a7379a-ad2c-4e18-9cdd-d686ff8c987c)


### Follow-up Analysis
1. Further exploration of cell type-specific gene expression patterns and functional implications.
2. Integration of additional datasets to validate and refine cell type annotations.
3. Investigation into the role of identified cell types in lung physiology and pathology.

### Conclusion
The scRNA-seq analysis provides insights into the cellular composition of mouse lung tissue and lays the groundwork for understanding lung cell heterogeneity and function.
