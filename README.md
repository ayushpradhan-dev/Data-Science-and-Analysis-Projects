# Ayush Pradhan - Data Science & Analytics Projects

This repository contains a collection of data science, machine learning, and analytics projects that demonstrate skills in data analysis, predictive modeling, and visualization using Python, R, and SQL. Each project includes code, documentation, and datasets (where applicable) to provide a detailed understanding of the scope, methodology, and results.

## Projects Overview

### 1. Retail Sales Inferential Analysis
**Project Scope:**  
Analyzed sales data to measure the impact of a new store layout and signage on revenue.  

**Dataset:** `sales.csv` (Located in the `data/` folder of this repository).  

**Implementation:**  
- Conducted exploratory data analysis (EDA) using histograms, scatter plots, and boxplots to visualize sales trends.  
- Built a multiple linear regression model in R to measure the statistical significance of layout changes.  
- Controlled for store type and staff turnover to ensure accurate insights.  
- Validated assumptions using residual analysis, variance inflation factors, and the Durbin-Watson test.  

---

### 2. COVID-19 Data Analysis & Visualization
**Project Scope:**  
Analyzed the impact of COVID-19 over time using real-time public API data.  

**Dataset:** Queried directly from a public COVID-19 API (no static dataset required).  

**Implementation:**  
- Extracted real-time COVID-19 case, death, and vaccination data from a public API.  
- Cleaned and structured the data into Pandas DataFrames for analysis.  
- Conducted time-series analysis, computing rolling averages and tracking infection trends.  
- Created dynamic visualizations to display regional trends and patterns over time.  

---

### 3. Natural Language Processing (NLP) on Wikipedia Data
**Project Scope:**  
Applied NLP techniques to extract meaningful insights from Wikipedia articles on ACM Turing Award winners.  

**Dataset:** Scraped using WikiData and Wikipedia APIs.  

**Implementation:**  
- Retrieved text from Wikipedia using API queries.  
- Preprocessed text using tokenization, stemming, lemmatization, and stopword removal.  
- Extracted bigrams and trigrams to identify frequent keyword associations.  
- Visualized word distributions with Matplotlib to compare linguistic patterns across award winners.  

---

### 4. Handwritten Digit Classification Using Convolutional Neural Networks (CNNs)
**Project Scope:**  
Developed a deep learning model to classify handwritten digits with high accuracy.  

**Dataset:** MNIST dataset (70,000 images of handwritten digits).  

**Implementation:**  
- Built a Convolutional Neural Network (CNN) using TensorFlow/Keras.  
- Implemented convolutional, pooling, dropout, and fully connected layers to improve model performance.  
- Optimized performance through hyperparameter tuning and batch normalization.  
- Achieved high accuracy on unseen test data through fine-tuning of the network.  

---

## Getting Started
To explore the projects, clone this repository and navigate to the relevant project folder:

```sh
git clone https://github.com/ayushpradhan-dev/Data-Science-and-Analysis-Projects.git
cd Data-Science-and-Analysis-Projects
