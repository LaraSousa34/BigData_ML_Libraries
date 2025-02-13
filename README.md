# BigData_ML_Libraries
Study and Analysis of the 2009 Taxi Rides Dataset
This repository contains a series of notebooks that explore, analyze, and compare different data processing and machine learning modeling libraries using the 2009 taxi rides dataset. The goal is to evaluate the efficiency of several libraries for data processing operations on different samples of the dataset and create machine learning pipelines to predict the fare value (fare_amt). A detailed description of the included notebooks and their respective functions is presented below.

## Notebooks
**1. dask_koalas**
Objective: Introduction and comparative study using the Dask and Koalas libraries.
Description: This notebook provides an introduction to the dataset and performs a detailed study using Dask and Koalas. Benchmarks are calculated for data processing operations using three different samples of the 2009 dataset. A more in-depth evaluation is performed with cprofile.
Platform: Runs on a Virtual Machine (VM), created on Google Cloud Platform.
**2. modin_joblib**
Objective: Study of the dataset using the Modin + Dask and Joblib libraries.
Description: This notebook calculates benchmarks for data processing operations using three different samples (from the first three months, the first two months and the first month of 2009). A more in-depth evaluation is performed with cprofile to analyze the efficiency of the operations.
Platform: Executed on a Virtual Machine (VM), created on the Google Cloud Platform.
**3. rapids**
Objective: Study of the dataset using the Dask + RAPIDS library.
Description: Similar to the modin_joblib notebook, this notebook calculates benchmarks for data processing operations using three different samples of the 2009 dataset. The performance evaluation is further evaluated with cprofile.
Platform: Executed through Google Colab.
**4. comparisons**
Objective: Compare the libraries used in previous studies.
Description: This notebook compares the efficiency and performance of the Dask, Koalas, Modin, Joblib, and RAPIDS libraries for data processing operations. The analysis includes benchmarks and results from evaluations made with cprofile.
Platform: Executed on a Virtual Machine (VM), created on Google Cloud Platform.
**5. ML**
Objective: Create machine learning pipelines to predict fare_amt.
Description: This notebook focuses on building preprocessing and modeling pipelines to predict the fare value (fare_amt) using two machine learning models. The process includes data splitting, preprocessing, training, and evaluation of the models.
Platform: Executed on a Virtual Machine (VM), created on Google Cloud Platform.
Execution Environment
Virtual Machine (VM): Used for the dask_koalas, modin_joblib, comparacoes, and ML notebooks.
Google Colab: Used for the rapids notebook.

**How to Run**
Download the files:

Download the 5 notebooks: dask_koalas.ipynb, modin_joblib.ipynb, rapids.ipynb, comparacoes.ipynb and ML.ipynb
Install Dependencies:

**For notebooks in VM:**

For notebooks in Colab: Follow the instructions in the rapids notebook itself to install the necessary dependencies.

**Run the Notebooks:**

Open the desired notebooks and run the cells sequentially.

**How to read**
It is suggested that the notebooks be read in the order indicated above. Therefore, start with the dask_koalas notebook, since it contains the introduction to the work, followed by modin_joblib, rapids and comparacoes. Finally, explore the Machine Learning task in the ML notebook.

**Benchmark results**
The benchmark results were saved in a results zip file.
