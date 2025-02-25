## REAL-TIME SOCIAL MEDIA ANALYTICS PIPELINE: BUILDING A ROBUST DATA PROCESSING FRAMEWORK

### Overview
This project aims to build a **real-time social media analytics pipeline** to extract meaningful insights from various platforms. It includes **sentiment analysis, hashtag clustering, and engagement prediction** using machine learning models.

The system processes high-velocity data, enabling businesses and researchers to monitor trends and user engagement efficiently.

### Tech Stack Used
- **Python** – for data processing and model training  
- **Google Colab** – for dataset analysis and model development  
- **Flask** – for web framework and deployment  
- **Scikit-Learn, TensorFlow** – for machine learning models  
- **Pandas, NumPy** – for data manipulation  
- **Matplotlib, Seaborn, Plotly** – for data visualization  
- **Joblib** – for model saving/loading  

### Dataset
The dataset includes various features such as:
- Social media text content  
- Hashtags and keywords  
- Likes, shares, and comments  
- User engagement metrics  
- Sentiment scores  

### Preprocessing Steps:
- Handling missing values  
- Encoding categorical variables  
- Normalizing numerical features  
- Removing stopwords and special characters from text  

### Model Training Process
#### Data Preprocessing:
- Tokenization and text cleaning  
- Feature scaling for numerical data  

#### Model Selection & Training:
- **Sentiment Analysis** using VADER  
- **Hashtag Clustering** using TF-IDF and K-Means  
- **Engagement Prediction** using Random Forest  
- Hyperparameter tuning with GridSearchCV  

#### Model Evaluation:
- **Silhouette Score** for clustering  
- **Mean Squared Error (MSE)** for regression models  
- **Mean Absolute Error (MAE)**  
- **F1 Score, Accuracy** for classification tasks  

#### Visualization Techniques:
- Word Clouds for trending topics  
- Correlation heatmaps  
- Cluster distribution plots  
- Model performance graphs  

### Model Deployment using Flask
1. User inputs text/hashtags via a web form  
2. Pre-trained models analyze data in real-time  
3. Results are displayed on the dashboard  

### Installation and Setup
```bash
# Clone the Repository
git clone https://github.com/ilajnae/RealTime-Analytics-Pipeline-IBM.git
cd RealTime-Analytics-Pipeline-IBM

# Install Dependencies
pip install -r requirements.txt

# Run Flask Server
python app.py
```

Open \`http://127.0.0.1:5000/` in your browser to access the web application.

### Usage
1. Enter text or hashtag data on the analytics page.  
2. Click "Analyze" to get insights.  
3. View sentiment scores, trending hashtags, and engagement predictions.  

