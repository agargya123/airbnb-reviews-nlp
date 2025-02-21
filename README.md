# **Airbnb Reviews Analytics & Recommendation System**

## **Project Overview**

This project focuses on analyzing Airbnb reviews and implementing a recommendation system based on sentiment analysis and user ratings. The goal is to develop a robust recommendation system that can suggest relevant listings to users based on reviews, sentiment, and ratings.


## **Key Features**

- **Sentiment Analysis**: Analyze the sentiment of Airbnb reviews to understand user satisfaction and potential improvements.
- **Recommendation System**: Build a content-based filtering recommendation system to suggest listings to users based on their preferences.
- **Data Exploration & Visualization**: Explore various data points such as review sentiment, location, and other features through visualizations.
  

## **Dataset**

The primary dataset for this project is the Airbnb reviews data, which contains the following fields:

- `review_text`: The actual review text written by a guest.
- `rating`: The rating provided by the guest for their stay.
- `listing_id`: The unique identifier for each listing.
- `date`: The date the review was posted.
- Other relevant attributes of the Airbnb listings.

The dataset is located in the `data/` folder and includes the **reviews.csv** file, which has been tracked using **Git LFS**.

## **Technologies Used**

- **Python**: The core programming language used for analysis and building the recommendation system.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib/Seaborn**: Data visualization.
- **Scikit-learn**: Building machine learning models for recommendation.
- **Git LFS**: Used to manage and store large dataset files (e.g., `reviews.csv`).

## **Setup Instructions**

To get this project up and running on your local machine, follow these steps:

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/your-repository.git
````

### **2. Setting up and activating your virtual environment**
For Windows:  
Set up your virtual environment - 
```bash
py -3.9 -m venv venv
```
then activate it: 
```bash
.\venv\Scripts\activate
```
For macOS/Linux: 
```bash
python3 -m venv venv
````
then activate it: 
```bash
source venv/bin/activate
```

### **3. Install Dependencies**
Make sure you have Python installed. Then, install the required dependencies using pip:
```bash
pip install -r requirements.txt
```
If you do not already have Git LFS on your system, install Git LFS (Large File Storage) this is crucial to be able to access and download some of the data files
```bash
git lfs install
```

Once this is installed on your local machine, Git will automatically pull the required files from LFS. No extra steps needed.


Now you can run the Airbnb-reviews-analytics notebook found under the "notebooks/" folder and perform your analysis!

