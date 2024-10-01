# **IT3212 - Data Driven Software (Group 25)**

## **Project Description**
In this competition, you will predict sales for the thousands of product families sold at Favorita stores located in Ecuador. The training data includes dates, store and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models.

## **Code Structure**
* [Assignment 1 - Data Pre-processing](./assignment_1) 
<br>
The objective is to understand and apply data preprocessing techniques on a dataset. Learning how to clean, transform, and prepare data for modeling, focusing on various steps involved in data preprocessing such as handling missing values, encoding categorical data, feature scaling, and data splitting.
* [assignment_2](./assignment_2): 
* [assignment_3](./assignment_3): 
* [assignment_4](./assignment_4): 


## **Installation and Requirements**
We propose using Conda for managing Python virtual environment and project dependencies.

1. Download project folder to destination:<br> 
`/<your-preferred-path>/IT3212`

2. Navigate into the project root path: <br>
`cd /<your-preferred-path>/IT3212`

3. Create a Python virtual environment: <br>
`conda create -n it3212 python=<python version>`

4. Activate new virtual environment: <br>
`conda activate it3212`

5. Install all required Python packages: <br>
`conda install -f requirements.yaml`


## **Running the code**
Source code is separated as much as possible from domain/project specifics and is parametrized using YAML configuration files to select hyperparameters and path definitions. Use Jupyter Notebooks to reproduce output or inspect pre-embedded final results.

6. Launch Jupyter Notebooks: <br>
`jupyter notebook`

7. Run [assignment_1/notebook_Anders.ipynb](./assignment_1/notebook_Anders.ipynb) to execute data pre-processing.


## **Datasets**
Data is provided from a Kaggle competition: [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data).

## **Compute**
Assumed running on IDUN - High Performance Computing (Linux environment)
* Runtime: Python vXYZ is recommended, dependencies documented in [requirements.yaml](./requirements.yaml)
* GPU: NVIDIA XYZ
* Model complexity: XYZ parameters (XYZ MB)
* Dataset storage: 125 MB 
* GPU VRAM utilization: XYZ MB (XYZ%)

## **Developer Information**

Developers: [Thomas Haugan](https://github.com/haugan7), [David Spilde](https://github.com/Davidspilde), [Anders Stubberud](https://github.com/Anders-Stubberud) and [Erlend Løken Sæveraas](https://github.com/ErlendSae) (group 25).