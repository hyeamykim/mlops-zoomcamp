# 1. Introduction

## Environment Setup

1. Create a GitHub repository. (e.g. mlops-zoomcamp)
2. Create GitHub codespace with the repository.
3. Open the codespace with VS code. 
4. Open terminal in VS code (ctrl+shft+` in  windows).
5. Download and install the Anaconda distribution of Python.

    ```
    wget https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh
    bash Anaconda3-2022.05-Linux-x86_64.sh
    ```
6. Docker is already included in GitHub codespace, which can be checked by running
    ```
    docker run hello-world
    ```

## NYC Taxi Duration Prediction

[Jupyter Notebook](duration-prediction.ipynb)

## ML Ops Maturity Model

MLOps Maturity model is necessary to 
- estimate the scope of the work 
- establish realistic success criteria
- identify deliverables 

It consists of five levels of maturity.

- level 0  
No MLOps. Manual training, builds, deployments, and testing of the model. No centralized tracking. 
- level l  
DevOps but no MLOps. Automated builds and tests.
- level 2  
Automated training. Training environment is managaed and traceable. Easy to reproduce model. Centralized tracking of model performance. 
- level 3  
Automated model deployment. Entire environment (train->test->production) is managed. Deployment traceable back to original data. Integrated A/B testing of model performance. 
- level 4  
Full MLOps automated operations. Full system automated and easily monitored. Production systems can provide information on how to improve, or automatically improve models. 

Reference: [MLOps Maturity Model](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/mlops-maturity-model)

