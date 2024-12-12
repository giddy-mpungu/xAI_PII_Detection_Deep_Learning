# PII Detection in Low-Resource Language of Luganda Using Deep Learning with Attention Mechanisms

## Authors
- **Gideon Mpungu**: [gmbugampungu@gmail.com](mailto:gmbugampungu@gmail.com)
- **Africano Byamugisha**: [africanobyamugisha@gmail.com](mailto:africanobyamugisha@gmail.com)

## Background
In our globally interconnected environment, managing Personally Identifiable Information (PII) poses significant challenges, especially in regions with low-resource languages like Luganda in Uganda. These languages lack sufficient computational resources and tools for Natural Language Processing (NLP), loooking at the difficulty of PII detection and anonymization. This project attempts to address these challenges by leveraging deep learning with attention mechanisms to enhance PII detection in Luganda while ensuring transparency through Explainable AI (XAI).

## Problem Statement
The primary challenge is detecting PII in text data, particularly focusing on low-resource languages like Luganda. Two main issues compound this challenge: the scarcity of annotated datasets and the limited effectiveness of existing NLP tools. Additionally, developing adaptable and transparent models that ensure ethical use presents a complex hurdle. This project aims to overcome these challenges by employing deep learning with attention mechanisms for improved PII detection in Luganda.

## Research Contributions
1. **Enhancement of PII Detection and Anonymization**: By utilizing attention mechanisms, the project directs deep learning models to focus on crucial linguistic features for PII detection, thus enhancing model performance even with limited data.
2. **Incorporation of Explainable AI (XAI)**: Through XAI techniques, the project aims to enhance model transparency, enabling better understanding and adaptation based on specific PII classifications.

The significance of this research lies in its potential to improve privacy protection in multilingual digital environments, aligning with global standards for data protection and privacy. Additionally, addressing the challenges of low-resource languages contributes valuable insights to the broader fields of NLP and privacy technology.

## Computational Problem Description
Data Scarcity in Low-Resource Languages:
Explainability and Adaptability:

## Dataset Description
The project utilizes the "Conrad747/lg-ner" dataset from Hugging Face for both training and evaluating the model.

## Notebooks Overview
1. **Initial Model and EDA**: This notebook contains exploratory data analysis (EDA) and the exploration of the initial models.
2. **Explanation of Initial Model and XAI**: Here, the initial model's implementation and the application of Explainable AI (XAI) techniques are explained and demonstrated.
3. **Final Model Integration**: The final notebook integrates additional models and XAI techniques for improved PII detection and transparency.

## Models Implemented
1. **xlm-roberta-base**
2. **microsoft/deberta-v3-base**
3. **masakhane/afroxlmr-large-ner-masakhaner-1.0_2.0**

## XAI Results and Visualizations
- **LIME**
- **SHAP**
- **eli5**