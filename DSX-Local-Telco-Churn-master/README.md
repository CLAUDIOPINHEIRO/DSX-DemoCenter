# DSX Local Telco Churn demo

**Objective**

The objective of this demo asset is to demonstrate building a predictive model with Spark machine learning API (SparkML) to predict customer churn, and deploy it for scoring in Machine Learning (ML).

**This repository contains the following assets for the Telco Churn demo in DSX Local**
1. ![Presentation](Presentation)
2. ![Notebook](Notebooks)
3. ![Data](data)
4. ![Instructions for creating a UI](WebApp) (requires a Bluemix account with access to Flask service)

**Demo setup**
1. Create a DSX project and name it "*DSX Local Lab - Telco Churn*"
2. Import ![Data](data) <br/>
Tip: First download the csv files before importing them into your project.  When downloading the csv files, make sure to click the **Raw** button to display the data in its raw format, right-click and select "Save Page As".
![Download CSV files](static/img/download_csv.png?raw=true)

3. Import notebook <br/>
Within the "DSX Local Lab - Telco Churn" project, add a Notebook and choose to import it from this URL: https://github.com/elenalowery/DSX-Local-Telco-Churn/blob/master/Notebooks/Telco%20Churn%20ML_Local.ipynb

4. Follow instructions in the notebook to add project token, and work through the notebook
5. Optional: deploy Telco Churn UI application: instructions in the ![WebApp](WebApp) folder. Or you can use this deployed UI: https://predictcustomerchurn.mybluemix.net/
6. If you would like to show Model Management - create several deployments from this or different notebooks
7. Optionally, watch a [video](https://ibm.box.com/s/9u40d8ug8paajh35ars0vtvhj48964wb) of the presentation and demo

**Demo**
1. Follow the agenda in the presentation 
2. During the demo show capabilities of DSX in the context of Telco Churn use case
   * Start with the overview of the use case and optionally the Telco Churn UI
   * Log in to DSX Local and create a new project
   * Show collaboration features for the project
   * Load data and explain what type of data sources are supported
   * Create a notebook from File
   * Walk through the notebook
   * Explain the deployment process - via UI and API
   * Test the model via UI or API and explian how the demo UI makes the same call
3. Wrap up with architecture discussion 

**Converting the notebook to use HDFS data sources**
1. Load .csv files into HDFS
2. Make a copy of the notebook or use the [sample notebook](https://github.com/elenalowery/DSX-Local-Telco-Churn/blob/master/Notebooks/TelcoChurn_HDP.ipynb) in the Notebooks folder
3. Replace Object Storage access code with HDFS access code <br>
![LoadData_HDFS](static/img/LoadData_HDFS1.JPG?raw=true) <br>


