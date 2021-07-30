# Workshop for Machine Learning on Azure

![logo](images/workshop_logo.png)

###### Originally forked from: [hyssh/mtc-open-workshop](https://github.com/hyssh/mtc-open-workshop)

Welcome to Microsoft Technology Center workshop for an introduction to Machine Learning on Azure. You will learn the basics of how to get started with the different ways of doing machine learning tasks on Azure Machine Learning Service.
Following are some of the pre-requisites for you to have the best learning experience in this workshop.

## Pre-requisites

* Basic knowledge of Cloud Computing, Python, and Machine Learning Concepts
* You should have an Azure subscription with appropriate permissions to be able to perform the tasks in this workshop.

> You may also be able to use free credits available in the Visual Studio Subscription.
> You will typically need **Contributor** permission to be able to create an Azure Machine Learning resource.

* [Create Azure Machine Learning Workspace](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace?tabs=azure-portal) before the workshop

## Agenda

## Day 1

| Session #   | Time (PDT)          | Topics                                                                                                                                                                         |
| ----------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Session 1.1 | 10:00 am - 12:00 pm | - Welcome</br>- Session: Introduction to Azure Machine Learning Service</br>- Demo: Azure Machine Learning Workspace</br> --> Data Store</br> --> Dataset</br> --> Environment |
| Break       | 12:00 pm - 01:00 pm | Lunch Break;                                                                                                                                                                   |
| Office Hour | 01:00 pm - 01:45 pm | (Optional) One-on-one Technical Architect coaching (Join the same teams meeting invite)                                                                                        |
| Session 1.2 | 02:00 pm - 04:00 pm | - Session: Automated Machine Learning Concept</br> - Hands-on break out 1.2: [Create AutoML experiment](/labs/lab1.2.md)</br>- Downsize/Stop resources                         |

## Day 2

| Session #   | Time (PDT)          | Topics                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ----------- | ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Session 2.1 | 10:00 am - 12:00 pm | - Session: No-code ML using [AML Studio Designer](labs/session2.1.md)</br>- Hands-on break out 2.1: [Tutorial for AML Studio Designer](/labs/lab2.1.md)</br>                                                                                                                                                                                                                                                                                                                                                                                         |
| Break       | 12:00 pm - 01:00 pm | Lunch Break;                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Office Hour | 01:00 pm - 01:45 pm | (Optional) One-on-one Technical Architect coaching (Join the same teams meeting invite)                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Session 2.2 | 02:00 pm - 04:00 pm | - Session: [Azure Machine Learning using Python SDK](/labs/session2.2.md)</br> - Hands-on break out 2.2: [Create Compute Instance](labs/lab2.2.md) </br> - Demo: Inside CI (Compute Instance)</br> --> Python </br> --> Conda env </br> --> Docker</br>- Hands-on break out 2.3: [AML Python get started](https://github.com/hyssh/mtc-open-workshop/tree/master/Notebooks/tutorials/1.create-first-ml-experiment) </br>```Notebooks/tutorials/1.create-first-ml-experiment/tutorial-1st-experiment-sdk-train.ipynb```</br>- Downsize/Stop resources |

> **Extra labs for Day 2**
>
> Dataset hands-on lab notebook '**AML-Dataset.ipynb**' and '**train-with-datasets.ipynb**'
>
> ```Notebooks/tutorials/2.train-with-datasets/AML-Dataset.ipynb```
>
> ```Notebooks/tutorials/2.train-with-datasets/train-with-datasets.ipynb```
>
></br>
>
> Train on local hands-on lab notebook '**train-on-local.ipynb**'
>
> ```Notebooks/tutorials/3.train-on-local/train-on-local.ipynb```

## Day 3

| Session #   | Time (PDT)          | Topics                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------- | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Session 3.1 | 10:00 am - 12:00 pm | - Session: Deep Learning using GPU</br>[VM Types available in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/sizes-gpu)</br>[Azure Machine Learning Service Compute targets](labs/session3.1.1.md)</br>- Session: Large Scale ML with Azure Remote Compute [Tensorflow Horovod Sample](https://github.com/hyssh/mtc-open-workshop/blob/master/labs/tensorflow/distributed-tensorflow-with-horovod/distributed-tensorflow-with-horovod.ipynb)</br>- Session: [Large Scale ML with DASK](https://github.com/hyssh/azureml-and-dask/blob/master/interactive/StartDask.ipynb)</br> - Hands-on break out: 3.1: [Train on AML Compute](https://github.com/hyssh/mtc-open-workshop/tree/master/Notebooks/tutorials/4.train-on-amlcompute/)</br>```Notebooks/tutorials/4.train-on-amlcompute/train-on-amlcompute.ipynb```</br> - Hands-on Break out 3.2: [Deploy model](https://github.com/hyssh/mtc-open-workshop/tree/master/Notebooks/tutorials/5.deploy-to-local)</br>```Notebooks/tutorials/5.deploy-to-local/register-model-deploy-local.ipynb``` |
| Break       | 12:00 pm - 01:00 pm | Lunch Break;                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Office Hour | 01:00 pm - 01:45 pm | (Optional) One-on-one Technical Architect coaching                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Session 3.2 | 02:00 pm - 04:00 pm | - Session: [AML Pipeline](labs/session3.2.md) & [MLOps](https://github.com/microsoft/MLOpsPython)</br> - Hands-on break out: 3.2: [AML Pipeline](https://github.com/hyssh/mtc-open-workshop/tree/master/Notebooks/tutorials/6.intro-to-pipelines)</br>```Notebooks/tutorials/6.intro-to-pipelines/aml-pipelines-getting-started.ipynb```</br>- **Delete** resources </br>- Survey                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

## Breakout Session

To rejoin breakout room, please use 'Join room' button.

![Join room](images/MicrosoftTeams-image.png)
