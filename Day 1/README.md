# Day 1

This repository contains Jupyter notebooks covering the complete machine learning workflow, from **data preparation** and **data analysis with Pandas** to **classical machine learning** and **deep learning** using PyTorch Lightning.

## Repository Structure

```text
Day 1
├── Pandas/
│   ├── 1_Pandas.ipynb
│   ├── 2_Pandas_(Dataset_Trending_YouTube_Video_Statistics).ipynb
│   └── 3_Advanced_Pandas_(Dataset_Trending_YouTube_Video_Statistics).ipynb
│
├── Data Preparation/
│   ├── 1_LoansDataSet.ipynb
│   ├── 2_ImputeMissingValue.ipynb
│   ├── 2_ImputeMissingValue_Pipeline.ipynb
│   ├── 3_SplitTrainTest.ipynb
│   ├── 4_Outliers_Titanic.ipynb
│   ├── 5_Outliers_Titanic_Pipeline.ipynb
│   ├── 6_Outliers_Boston_(optional).ipynb
│   └── 7_Outliers_Diabetes_(optional).ipynb
│
├── Machine Learning/
│   ├── 1_Decision_Trees_Random_Forests_v3.ipynb
│   ├── 2_Linear_Regression_v2.ipynb
│   ├── 3_Logistic_Regression_v2.ipynb
│   ├── 4_Neural_Network_v3.ipynb
│   ├── 5_K_Nearest_Neighbors_v2_update_09012025.ipynb
│   ├── 6_Support_Vector_Machine_v2.ipynb
│   ├── 7_Save_Load_Model_v2.ipynb
│   ├── 8_K_Means_Clustering_v2.ipynb
│   ├── 9_Market_Basket_Intro_v2.ipynb
│   └── 10_Scikit_learn_Pipeline.ipynb
│
├── Deep Learning/
│   ├── 1_Image_classification_CIFAR10_CNN(lightning).ipynb
│   ├── 2_Image_classification_Animal_EfficientNetV2(lightning).ipynb
│   ├── 2_2_Image_classification_Animal_EfficientNetV2(lightning)_TensorBoard.ipynb
│   ├── 2_3_Image_classification_Animal_EfficientNetV2(lightning)_wandb.ipynb
│   ├── 2_4_Image_classification_Animal_EfficientNet(lightning)_wandb_HuggingFace.ipynb
│   ├── 3_2_Object_detection_VOCDetection_yolov8_basic.ipynb
│   ├── 3_3_Object_detection_VOCDetection_yolov8_advanced.ipynb
│   ├── 4_Semantic_segmentation_Camseq_deeplabv3_DataInGD(lightning).ipynb
│   ├── 5_Time_series_forecasting_DataInGD.ipynb
│   └── 5_Time_series_forecasting_DataInGD_update.ipynb
│
├── Prompt Engineering/
│   ├── 1_LLM_Basic_API_Call_LangChain.ipynb
│   ├── 2_LLM_Prompt_Engineering_Basic_LangChain.ipynb
│   ├── 3_LLM_Prompt_Engineering_Advanced_LangChain.ipynb
│   ├── 4_LLM_LangChain_Playground_Tracking_with_LangSmith_Groq.ipynb
│   ├── 5_LLM_Basic_LangGraph.ipynb
│   └── 6_LLM_RAG_LangChain_LangGraph.ipynb
│
└── README.md
```

---

# Folder Description

## Pandas

This folder covers data manipulation and analysis using Pandas.

| Notebook                                                              | Description                                                                                             |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| `1_Pandas.ipynb`                                                      | Introduction to the Pandas library, including Series, DataFrames, indexing, filtering, and aggregation. |
| `2_Pandas_(Dataset_Trending_YouTube_Video_Statistics).ipynb`          | Data exploration using a real-world YouTube Trending dataset.                                           |
| `3_Advanced_Pandas_(Dataset_Trending_YouTube_Video_Statistics).ipynb` | Advanced Pandas techniques including grouping, merging, pivot tables, and complex data analysis.        |

---

## Data Preparation

This folder introduces essential data preprocessing techniques required before training machine learning models.

| Notebook                               | Description                                                                  |
| -------------------------------------- | ---------------------------------------------------------------------------- |
| `1_LoansDataSet.ipynb`                 | Introduction to the loan dataset used throughout the preprocessing examples. |
| `2_ImputeMissingValue.ipynb`           | Handling missing values using common imputation techniques.                  |
| `2_ImputeMissingValue_Pipeline.ipynb`  | Applying missing value imputation with Scikit-learn Pipelines.               |
| `3_SplitTrainTest.ipynb`               | Splitting datasets into training and testing sets.                           |
| `4_Outliers_Titanic.ipynb`             | Detecting and handling outliers using the Titanic dataset.                   |
| `5_Outliers_Titanic_Pipeline.ipynb`    | Outlier processing integrated into a preprocessing pipeline.                 |
| `6_Outliers_Boston_(optional).ipynb`   | Optional notebook demonstrating outlier handling with the Boston dataset.    |
| `7_Outliers_Diabetes_(optional).ipynb` | Optional notebook demonstrating outlier handling using the Diabetes dataset. |

---

## Machine Learning

This folder contains implementations of classical machine learning algorithms using Scikit-learn.

| Notebook                                         | Description                                                     |
| ------------------------------------------------ | --------------------------------------------------------------- |
| `1_Decision_Trees_Random_Forests_v3.ipynb`       | Decision Tree and Random Forest algorithms.                     |
| `2_Linear_Regression_v2.ipynb`                   | Linear Regression for regression problems.                      |
| `3_Logistic_Regression_v2.ipynb`                 | Logistic Regression for binary classification.                  |
| `4_Neural_Network_v3.ipynb`                      | Feedforward Neural Networks using Scikit-learn.                 |
| `5_K_Nearest_Neighbors_v2_update_09012025.ipynb` | K-Nearest Neighbors (KNN) classification.                       |
| `6_Support_Vector_Machine_v2.ipynb`              | Support Vector Machine (SVM) for classification.                |
| `7_Save_Load_Model_v2.ipynb`                     | Saving and loading trained machine learning models.             |
| `8_K_Means_Clustering_v2.ipynb`                  | K-Means clustering for unsupervised learning.                   |
| `9_Market_Basket_Intro_v2.ipynb`                 | Introduction to Market Basket Analysis and Association Rules.   |
| `10_Scikit_learn_Pipeline.ipynb`                 | Building complete machine learning pipelines with Scikit-learn. |

---

## Deep Learning

This folder demonstrates modern deep learning applications using PyTorch Lightning.

| Notebook                                                                          | Description                                                                              |
| --------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `1_Image_classification_CIFAR10_CNN(lightning).ipynb`                             | Image classification on the CIFAR-10 dataset using Convolutional Neural Networks (CNNs). |
| `2_Image_classification_Animal_EfficientNetV2(lightning).ipynb`                   | Transfer learning with EfficientNetV2 for animal image classification.                   |
| `2_2_Image_classification_Animal_EfficientNetV2(lightning)_TensorBoard.ipynb`     | Training with TensorBoard visualization.                                                 |
| `2_3_Image_classification_Animal_EfficientNetV2(lightning)_wandb.ipynb`           | Training with Weights & Biases experiment tracking.                                      |
| `2_4_Image_classification_Animal_EfficientNet(lightning)_wandb_HuggingFace.ipynb` | Model training with Weights & Biases and Hugging Face integration.                       |
| `3_2_Object_detection_VOCDetection_yolov8_basic.ipynb`                            | Basic object detection using YOLOv8 on the VOC dataset.                                  |
| `3_3_Object_detection_VOCDetection_yolov8_advanced.ipynb`                         | Advanced YOLOv8 object detection techniques.                                             |
| `4_Semantic_segmentation_Camseq_deeplabv3_DataInGD(lightning).ipynb`              | Semantic segmentation using DeepLabV3.                                                   |
| `5_Time_series_forecasting_DataInGD.ipynb`                                        | Deep learning for time series forecasting.                                               |
| `5_Time_series_forecasting_DataInGD_update.ipynb`                                 | Updated implementation of the time series forecasting example.                           |

---

## Prompt Engineering

This folder introduces modern Large Language Model (LLM) application development using LangChain and LangGraph.

| Notebook                                                        | Description                                                             |
| --------------------------------------------------------------- | ----------------------------------------------------------------------- |
| `1_LLM_Basic_API_Call_LangChain.ipynb`                          | Introduction to calling LLM APIs using LangChain.                       |
| `2_LLM_Prompt_Engineering_Basic_LangChain.ipynb`                | Fundamentals of prompt engineering with LangChain.                      |
| `3_LLM_Prompt_Engineering_Advanced_LangChain.ipynb`             | Advanced prompt engineering techniques, prompt templates, and chaining. |
| `4_LLM_LangChain_Playground_Tracking_with_LangSmith_Groq.ipynb` | Experiment tracking and debugging using LangSmith with Groq models.     |
| `5_LLM_Basic_LangGraph.ipynb`                                   | Building stateful LLM workflows using LangGraph.                        |
| `6_LLM_RAG_LangChain_LangGraph.ipynb`                           | Retrieval-Augmented Generation (RAG) using LangChain and LangGraph.     |

---

# Recommended Learning Order

For beginners, it is recommended to follow the notebooks in this order:

1. **Pandas**
    * Master data manipulation and exploratory data analysis.

2. **Data Preparation**
    * Learn data cleaning, preprocessing, train/test splitting, and handling outliers.

3. **Machine Learning**
    * Learn supervised and unsupervised learning algorithms.
    * Understand model evaluation and deployment.

4. **Deep Learning**
    * Start with CNN image classification.
    * Continue with transfer learning.
    * Explore object detection.
    * Learn semantic segmentation.
    * Finish with time series forecasting.

5. **Prompt Engineering**
    * Learn how to interact with LLMs using LangChain.
    * Study prompt engineering best practices.
    * Build AI workflows with LangGraph.
    * Learn experiment tracking with LangSmith.
    * Implement Retrieval-Augmented Generation (RAG) applications.