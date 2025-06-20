# Key Elements of AI

AI refers to mimicking human behavior and capabilities.

## Components of AI

| Component               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Machine Learning (ML)  | Learn and predict like a human                                              |
| Natural Language Processing (NLP) | Understand natural language and convert it to machine-readable format |
| Computer Vision         | Identify objects or see like a human                                       |
| Anomaly Detection       | Detect outliers                                                            |
| Conversational AI       | Hold conversations with humans                                             |

---

# Datasets & Labeling

- **Dataset**: Group of common data used to train ML models  
- **Data Labeling**: Assigning meaningful labels to raw data  
- **Ground Truth**: Standard used during labeling to ensure consistency  

## Types of Machine Learning

| Type                 | Driven By      | Labeling             | Examples                                      |
|----------------------|----------------|-----------------------|-----------------------------------------------|
| Supervised ML        | Task Driven    | Done by humans        | Classification, Regression                    |
| Unsupervised ML      | Data Driven    | Done by the machine   | Clustering, Dimensionality Reduction, Association |
| Reinforcement Learning | Decision Driven | No initial data, uses environment | Game AI, Learning tasks         |

## Use Cases for ML Types

| Supervised ML                | Unsupervised ML             | Reinforcement Learning                                |
|-----------------------------|-----------------------------|-------------------------------------------------------|
| When precise outcome needed | To understand sense of data | No data provided; interacts with environment          |
| Specific value returned     | Outcome does not need to be precise | Learns via multiple attempts                    |

---
## Evaluation Metrics for Regression Models 

| Metric                  | Description                                                                                     |
|-------------------------|-------------------------------------------------------------------------------------------------|
| **Mean Absolute Error (MAE)**      | The average amount the predictions are off from the true values, ignoring direction.          |
| **Mean Squared Error (MSE)**       | The average of the squared differences between predictions and true values (penalizes big errors more). |
| **Root Mean Squared Error (RMSE)** | The square root of MSE, showing error in the same units as the data.                         |
| **Mean Absolute Percentage Error (MAPE)** | The average error shown as a percentage of the true values.                                 |
| **R-squared (Coefficient of Determination)** | How well the model explains the variation in the data (higher is better).                   |
| **Adjusted R-squared**              | Like R-squared but adjusts for extra variables to avoid overestimating performance.          |


# Hardware & Acceleration

- **GPU (Graphics Processing Unit)**: Helps in parallel operations  
  - ~1000 cores  
  - Renders high-quality video  
  - Used in: ML, DL, Bitcoin mining  
- **CUDA (Compute Unified Device Architecture)**: Developed by NVIDIA  
  - Platform/API to work with GPUs

---

# Forecasting vs Prediction

| Forecasting                       | Prediction                          |
|----------------------------------|-------------------------------------|
| Uses relevant data               | May not use relevant data           |
| Analyzes trends                  | Uses statistics and decision theory |
| Not guessing                     | Mostly guessing                     |

---


# Computer Vision

## Algorithms:

- **CNN (Convolutional Neural Networks)**: Image & video recognition  
- **RNN (Recurrent Neural Networks)**: Handwritten text & speech recognition  

## Types of Computer Vision Tasks:

- Image Classification  
- Object Detection  
- Semantic Segmentation  
- Image Analysis  
- Optical Character Recognition (OCR)  
- Facial Detection  

## Azure Services for CV:

- **Computer Vision**  
- **Custom Vision**  
- **Form Recognizer**: Extracts key-value pairs from documents  
- **Face**: Detects people and emotions in images  

---

# Natural Language Processing (NLP)

## Azure Services:

- Text Analytics  
- Translator  
- Speech  
- LUIS (Language Understanding)  

---

# Conversational AI

## Azure Services:

- QnA Maker  
- Azure Bot Service  

---

# Responsible AI (FRPITA)

- **Fairness**  
- **Reliability and Safety**  
- **Privacy and Security**  
- **Inclusiveness**  
- **Transparency**  
- **Accountability**  

---

# Azure Cognitive Services

Grouped set of APIs to add AI capabilities easily.

## Categories & Services:

| Category | Services                                                                 |
|----------|--------------------------------------------------------------------------|
| Decision | Anomaly Detector, Content Moderator, Personalizer                        |
| Language | LUIS, QnA Maker, Text Analytics, Translator                              |
| Speech   | Speech to Text, Text to Speech, Speech Translation, Speech Recognition   |
| Vision   | Computer Vision, Custom Vision, Face, Form Recognizer                    |

---

# Knowledge Mining

Extract and analyze large volumes of data from documents.

## Three Steps:

1. Ingest  
2. Enrich  
3. Explore  

## Use Cases:

- Content research  
- Auditing, risk & compliance  
- Business process management  
- Customer support & feedback analysis  
- Digital asset management  
- Contract management  

---

# Azure Face Service & OCR

- **OCR API**: Legacy, fast, image-only, synchronous  
- **Read API**: Newer, supports images + PDFs, asynchronous  
- OCR uses Computer Vision SDK  

---

# Form Recognizer

- Preserves structure and relationships in forms (e.g., date fields)  

---

# LUIS (Language Understanding Intelligent Service)

- ML-based service to understand natural language (NLP/NLU)  
- Hosted at [luis.ai](https://luis.ai)  

## Components:

- **None Intent**: Default intent  
- **Intents**: Classify user utterances  
- **Entities**: Extract data from utterances  

**Example**:  
"Book me 2 tickets to Europe"  
- **Intent**: Book flight  
- **Entities**: 2 tickets, Europe  

---

# Azure Machine Learning Studio

## Compute Types:

| Type              | Purpose                                     |
|-------------------|---------------------------------------------|
| Compute Instance  | Development workstation                     |
| Compute Clusters  | Scalable VMs for experiments                |
| Inference Clusters| Deployment targets for trained models       |
| Attached Compute  | External VMs / Azure Databricks             |

## Data Storage:

- Blob Storage  
- File Share  
- Data Lake Storage  
- SQL Database  
- PostgreSQL  
- MySQL  

---

# Azure ML Concepts

| Component        | Description                                         |
|------------------|-----------------------------------------------------|
| Experiments      | Logical grouping of Azure runs                      |
| Pipelines        | Workflow or sequence of steps                       |
| ML Designer      | Visual tool to build ML pipelines                   |
| Model Registry   | Create, track, manage versions of models            |
| Endpoints        | Deploy ML models as web services via AKS or ACI     |
| Notebooks        | Jupyter-like notebook editor                        |

> **AKS** - Real-Time Inference End Points

---

# Automated Machine Learning (AutoML)

- Automatically builds and trains ML models  
- **DataGuard Rails**: Ensures high-quality input data (auto-featurization)  
- **Model Selection**: Uses many models and recommends the best  
- **Explanation**: **MLX** - Explaining ML and Deep learning models  
- **Primary Metrics**: Chosen based on problem type

## Important Points
- speech service is used for speech to text, text to speech, speech translation and speaker recognition
- Speech Synthesis : Text to Speech conversion
- Which assumption of the multiple linear regression model should be satisfied to avoid misleading predictions? - Features are independent of each other
- **System messages** can used to identify constraints and styles for the responses of a generative AI model.
- **Image description** is not supported by DALL E model
- GPT model is good at creating and Understanding Natural Language
- **Embeddings** can search, classify, and compare sources of text for similarity.
- **Facial Detection** computer vision solution provides the ability to identify a person's age based on a photograph?
- Which additional piece of information is included with each phrase returned by an image description task of the Azure AI Vision? **Confidence Score**
- Face Identification - one to many mapping and Face verification one to one matching
- Which natural language processing (NLP) technique normalizes words before counting them? **Stemming**
- Which feature of the Azure AI Language service includes functionality that returns links to external websites to disambiguate terms identified in a text? **EntityLinking**
- Semantic segmentation provides the ability to classify individual pixels in an image depending on the object that they represent. The other answer choices also process images, but their outcomes are different.
- Stemming normalizes words before counting them. Frequency analysis counts how often a word appears in a text. N-grams extend frequency analysis to include multi-term phrases. Vectorization captures semantic relationships between words by assigning them to locations in n-dimensional space.
- Entity Linking identifies and disambiguates the identity of entities found in a text. Key phrase extraction is not used to extract entities and is used instead to extract key phrases to identify the main concepts in a text. Named entity recognition cannot provide a link for each entity to view further information. Text translation is part of the Azure AI Translator service.
- K-means clustering is an unsupervised machine learning algorithm component used for training clustering models. You can use unlabeled data with this algorithm. Linear regression and classification are supervised machine learning algorithm components. You need labeled data to use these algorithms. Normalize Data is not a machine learning algorithm module.

- Text Analytucs API : takes input text document and return sentiment and also helps with language detection and named entity recognition
- Direct Line channel to support speach ouput
- **Accuracy** is a calculated probability of correct Image classification.
- Best possible R2 score : Set primary metric to R2 score
- In the context of ROC curves, AUC values range from 0 to 1.
- More Focus should be on Generative AI Models 
