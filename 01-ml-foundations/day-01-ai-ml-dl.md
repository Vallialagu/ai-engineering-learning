# Day 1  AI, Machine Learning and Deep Learning

**Learning Track:** AI Engineering\
**Module:** ML Foundations\
**Objective:** Understand the relationship between AI, ML and DL,
different machine learning approaches, and common prediction tasks.

## 1. AI vs ML vs Deep Learning

  -----------------------------------------------------------------------
  Concept                 Meaning                 Examples
  ----------------------- ----------------------- -----------------------
  Artificial Intelligence Broad field of building Chatbots, voice
  (AI)                    intelligent systems     assistants, fraud
                                                  detection

  Machine Learning (ML)   Systems learn patterns  Recommendation systems,
                          from data               churn prediction

  Deep Learning (DL)      ML using multi-layer    Image recognition,
                          neural networks         speech recognition

  Generative AI           Models that generate    GPT, image generation
                          new content, often      models
                          using DL                
  -----------------------------------------------------------------------

**Remember:** ML is a subset of AI. DL is a subset of ML. Generative AI
is an application area that commonly uses deep learning architectures
such as Transformers.

## 2. Types of Machine Learning

### Supervised Learning

-   Learns from labelled data.
-   Common tasks: classification and regression.
-   Example: Detecting employees wearing uniforms using labelled images.

### Unsupervised Learning

-   Learns patterns from unlabelled data.
-   Common tasks: clustering and dimensionality reduction.
-   Example: Grouping customers based on purchasing behaviour.

### Semi-supervised Learning

-   Uses a small amount of labelled data along with a larger amount of
    unlabelled data.
-   Example: Image classification when only some images are labelled.

### Self-supervised Learning

-   Creates its own learning signals from the data.
-   Example: Language models learning to predict missing or next tokens.

## 3. Common ML Tasks

  Task             What it predicts                Example
  ---------------- ------------------------------- ----------------------------
  Classification   A category or class             Spam / Not Spam
  Regression       A numerical value               Monthly revenue prediction
  Clustering       Groups of similar data points   Customer segmentation

### Common algorithms

-   Classification: Logistic Regression, Decision Trees, Random Forest,
    SVM.
-   Regression: Linear Regression, Decision Tree Regression.
-   Clustering: K-Means, DBSCAN.

## 4. ML Training Lifecycle

1.  **Data Collection:** Gather relevant historical or real-world data.
2.  **Data Preparation:** Clean data, handle missing values and format
    inputs.
3.  **Feature Selection:** Identify relevant inputs for the model.
4.  **Training:** Allow the model to learn patterns from data.
5.  **Evaluation:** Test model performance using appropriate metrics and
    unseen data.
6.  **Inference:** Use the trained model to make predictions on new
    inputs.

## 5. Important Concepts

-   Training = learning patterns from data.
-   Inference = using a trained model to make predictions.
-   Classification and regression are prediction tasks.
-   Clustering discovers groups in data.
-   Generative AI often uses deep learning architectures such as
    Transformers.
-   The right approach depends on the problem, available data and
    business objective.

## 6. Real-world Scenarios

  -----------------------------------------------------------------------
  Business problem                    Approach
  ----------------------------------- -----------------------------------
  Customer churn prediction           Classification

  Monthly revenue prediction          Regression

  Customer segmentation               Clustering

  Temperature threshold alert         Rule-based system

  Employee uniform detection using    Supervised learning +
  labelled images                     classification
  -----------------------------------------------------------------------

**Next:** Day 2 -- Introduction to Machine Learning Algorithms.
