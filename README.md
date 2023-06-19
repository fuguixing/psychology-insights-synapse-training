<p align="center">
  <a href="https://azure.microsoft.com/services/synapse-analytics/"><img src="https://img.shields.io/badge/Azure%20Synapse-Analytics-blue.svg" alt="Azure Synapse Analytics"></a>
  <a href="https://www.python.org/downloads/release/python-380/"><img src="https://img.shields.io/badge/Python-3.8-blue.svg" alt="Python 3.8"></a>
</p>

# Psychology Insights Machine Learning Training (Synapse)


This repository contains the code and resources for training machine learning models using Synapse in the Psychology Insights project.

## Getting Started

To train the models using Synapse, follow these steps:

1. Upload the Dataset
Before starting with Azure Synapse Analytics, upload the mypersonality_final.csv file to Azure Blob Storage. This file contains the dataset that will be used for model training.

2. Create Azure Synapse Workspace
Create an Azure Synapse Workspace in your Azure portal. This workspace will serve as the central hub for managing and executing your analytics tasks.

3. Create Spark Pool
Within your Azure Synapse Workspace, create a Spark pool. This pool will provide the necessary resources for distributed data processing and model training.

4. Train Models
Open the Train_Models.ipynb notebook available in your Spark pool. This notebook contains the code and instructions for training machine learning models using the dataset uploaded in Step 1. Follow the guidelines provided in the notebook to train and evaluate the models.

By following these steps, you can leverage Azure Synapse Analytics to efficiently train machine learning models and gain valuable insights from your dataset.

## Contributing

Welcome contributions to improve the machine learning training process in the Psychology Insights project. If you'd like to contribute, please follow these guidelines:

- Fork the repository and create a new branch for your feature or improvement.
- Commit your changes and push your branch to your forked repository.
- Submit a pull request, describing your changes in detail.

## License

This project is licensed under the [MIT License](LICENSE).
