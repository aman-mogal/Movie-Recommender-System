# Movie-Recommender-System

This repository contains a machine learning-based movie recommender system. It includes a Jupyter Notebook for data analysis and model training, as well as a Streamlit web application to showcase the model.

## Features
- **Data Analysis and Model Training:** Explore and train a movie recommendation model using collaborative filtering techniques.
- **Interactive Web Application:** A user-friendly interface built with Streamlit that allows users to input a movie name and get personalized recommendations.

## Files in the Repository
- `movie-recommender-system.ipynb`: Jupyter Notebook for data loading, preprocessing, exploratory data analysis, and model training.
- `app.py`: Streamlit web application that uses the trained model to recommend movies.
- `movies_dict.pkl`: Pickled file containing movie metadata.
- `similarity.pkl`: Pickled file containing the similarity matrix.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- Jupyter Notebook
- Streamlit

Install the required dependencies using:
```bash
pip install -r requirements.txt
```

### Running the Project

#### Step 1: Model Training
1. Open `movie-recommender-system.ipynb` in Jupyter Notebook.
2. Execute the notebook to process the data, train the model, and generate the necessary files (`movies_dict.pkl` and `similarity.pkl`).

#### Step 2: Run the Web Application
1. Place the generated `movies_dict.pkl` and `similarity.pkl` files in the same directory as `app.py`.
2. Launch the Streamlit application by running:
   ```bash
   streamlit run app.py
   ```
3. Open the application in your web browser at `http://localhost:8501`.

## Usage
1. Select a movie from the dropdown menu in the app.
2. Click the "Recommend" button to see the top 5 recommended movies.

## Project Structure
```
├── movie-recommender-system.ipynb   # Jupyter notebook for training the model
├── app.py                           # Streamlit app code
├── movies_dict.pkl                  # Pickled movie data
├── similarity.pkl                   # Pickled similarity matrix
├── requirements.txt                 # List of Python dependencies
```

## Dependencies
- `streamlit`
- `pandas`
- `pickle`

## Outcome
![Screenshot (414)](https://github.com/user-attachments/assets/a3b5fac9-8c2e-41f0-a1c5-419b1dd991ff)
![Screenshot (415)](https://github.com/user-attachments/assets/056e8f53-9fdc-41c3-bd83-c01eb687c21e)
![Screenshot (416)](https://github.com/user-attachments/assets/29d56ae6-94a6-4f00-9d57-dccf209924ae)




## Contribution
Contributions are welcome! Please feel free to submit pull requests or raise issues for enhancements and bug fixes.


