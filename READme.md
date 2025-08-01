Shopper Spectrum: Customer Segmentation \& Product Recommendation

🚀 Project Overview

This project analyzes a transactional e-commerce dataset to derive actionable business insights. It involves two core machine learning tasks:



Customer Segmentation: Using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, customers are segmented into four distinct groups: "High-Value," "Regular," "Occasional," and "At-Risk."



Product Recommendation: An item-based collaborative filtering model recommends the top 5 most similar products based on customer co-purchase history.



The final output is an interactive web application built with Streamlit that allows users to perform real-time predictions for both customer segmentation and product recommendations.



✨ Features

The project is delivered as an interactive Streamlit web application with three main pages:



🏠 Home: A welcome page that provides an overview of the application's capabilities.



👤 Customer Segmentation: Allows users to input a customer's Recency, Frequency, and Monetary values to predict which of the four segments they belong to.



🛍️ Product Recommendation: Allows users to enter a product name and receive the top 5 most similar product recommendations.



🛠️ Tech Stack

Language: Python



Libraries:



Data Manipulation: Pandas, NumPy



Data Visualization: Matplotlib, Seaborn, Plotly



Machine Learning: Scikit-learn



Web Framework: Streamlit



UI Components: streamlit-option-menu



📂 Project Structure

To run this application, your project folder must contain the following files:



Shopper\_Spectrum/

│

├── 📄 app.py                     # The main Streamlit application script

├── 📄 requirements.txt           # List of required Python libraries

│-- 📄 online\_retail.csv          # download the dataset from the link provided below

├── 📦 kmeans\_model.pkl           # Saved K-Means clustering model

├── 📦 scaler.pkl                  # Saved StandardScaler for data preprocessing

├── 📦 rfm\_df.pkl                 # Saved RFM data for dynamic labeling

├── 📦 product\_list.pkl            # List of all product names for the recommender

└── 📦 product\_similarity\_df.pkl   # Saved product similarity matrix

Dataset (link to download):[Click here to download dataset](https://drive.google.com/file/d/1rzRwxm_CJxcRzfoo9Ix37A2JTlMummY-/view)

**Its necessary to download dataset from the above link,otherwise the code doesn't work.**

⚙️ Setup and Installation

Follow these steps to set up and run the application on your local machine.



1\. Clone the Repository (or Create the Project Folder)

First, get the project files onto your computer. If this were a GitHub repository, you would clone it. For now, ensure all the files listed in the "Project Structure" section are in a single folder named Shopper\_Spectrum.



2\. Set Up a Virtual Environment (Recommended)

It's good practice to create a virtual environment to keep your project dependencies isolated.



\# Create a new virtual environment

python -m venv venv



\# Activate the virtual environment

\# On Windows:

venv\\Scripts\\activate

\# On macOS/Linux:

source venv/bin/activate



3\. Install Required Libraries

Navigate to your project folder in your terminal or command prompt and install all the necessary libraries using the requirements.txt file.



\# Ensure you are in the Shopper\_Spectrum folder

pip install -r requirements.txt



4\. Run the Streamlit Application

Once the installation is complete, you can launch the web application with a single command.



\# Run the app

streamlit run app.py



Your web browser should automatically open with the "Shopper Spectrum" application running live. If not, the terminal will provide a local URL (usually http://localhost:8501) that you can open in your browser.



This README provides all the necessary information for a user to understand, set up, and run the Shopper Spectrum application.

