# 3.2 Sentiment Analysis Project: TripAdvisor Hotel Reviews

## Objective
The objective of this sentiment analysis project is to understand customer sentiments regarding TripAdvisor hotel reviews (positive, negative, or neutral). By analyzing the sentiment of reviews, insights into customer satisfaction and dissatisfaction are gained, allowing for the identification of pain points and features contributing to customer experiences.

## 1. Data Preprocessing
- **Text Cleaning:** Removed special characters, punctuation, and stopwords from review text to reduce noise.
- **Text Normalization:** Performed lemmatization to reduce words to their base forms, aiding in text standardization.

## 2. Data Visualization
- Utilized Matplotlib and wordcloud library for visualization.
  
### Insights:
- Positive Sentiment Dominance
- Room Quality Enhancement
- Customized Dining Experience
- Efficient Operations

## 3. MLFlow: Unified Platform for Experiment Tracking and Model Registry
- **Experiment Tracking:**
  - Create Experiments
  - Define Naming Conventions
  - Log Parameters, Metrics, and Artifacts
  - Compare Results
  - Iterate and Optimize
- **Metrics and Hyperparameter Visual Analysis**

| Model              | Accuracy | Efficiency | Scalability | Interpretability | Characteristics |
|--------------------|----------|------------|-------------|------------------|-----------------|
| Naive Bayes        | 83.7%    | Shortest training time | Relatively small model size | Simple and interpretable | Relies on feature independence |
| Decision Tree      | 77.34%   | Easy to understand and visualize | Can overfit | Model size grows with larger datasets | Tuning can mitigate overfitting |
| Logistic Regression| 87.0%    | Provides insights into feature importance | May not scale well to very large datasets | Longest training time | Regularization techniques prevent overfitting |
| Random Forest      | 86.4%    | Ensemble learning, combines multiple trees | Longer training time compared to some models | Largest model size, higher memory requirements | Significant impact of hyperparameters |

### Best Model: Logistic Regression
- Prediction Time
- Fit Time
- Model Size
- Test Score and Train Score

## 4. Deploying a Flask Web Application on AWS Cloud

### Step 1: Set up AWS Account and Resources
- Create an AWS Account
- Launch EC2 Instance

### Step 2: Prepare Your Flask Application
- Import necessary modules
- Initialize a Flask application instance
- Define routes for home page and prediction
- Run Flask application in debug mode

### Step 3: HTML Code Structure
- Define document type and language
- Include metadata in the head section
- Style body with center alignment, background color, and font family
- Create container div for main content
- Display title, form, and prediction result

### Step 3: Configure Your EC2 Instance
- SSH into Your EC2 Instance
- Install Required Packages
- Copy Flask Application

### Step 4: Access Your Flask Application
- Open Web Browser
- Enter EC2 Instance's Public IP Address or Domain Name
