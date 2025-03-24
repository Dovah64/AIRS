# AI-powered Recommendation System
This is a simple AI-powered device recommendation web application built using Flask, Python, and Sentence Transformers. The app takes user input in the form of a search query and returns a list of the most relevant electronic devices based on similarity scores.

## Features
Natural Language Search: Search for devices in everyday language.

AI-Based Recommendations: Uses pre-computed embeddings and cosine similarity to suggest the most relevant products.

Interactive Web Interface: Built with Flask and HTML.

## Technologies Used
Python: Backend logic and AI model.

Flask: Web framework.

Pandas: Data manipulation.

Sentence Transformers: For generating and comparing text embeddings.

Scikit-learn: Cosine similarity calculation.

## Project Structure
Pyprjct/ |-- venv/ # Virtual environment (not included in repo) |-- templates/ # HTML templates | |-- index.html # Main web interface |-- main.py # Flask backend |-- embeddings.pkl # Precomputed device embeddings |-- requirements.txt # Python dependencies |-- .gitignore # Files to exclude from version control

## How to Run
Clone the Repository:

git clone cd Pyprjct

Create a Virtual Environment:

python -m venv venv

Activate the Virtual Environment:

On Windows:

venv\Scripts\activate

On Mac/Linux:

source venv/bin/activate

Install Dependencies:

pip install -r requirements.txt

Run the Flask App:

python main.py

Open in Browser: Go to http://127.0.0.1:5000/.

## How to Use
Enter a device type, brand, or description in the search bar.

Click the Search button.

View the top recommended devices with their titles, brands, categories, and images.

## Future Plans
Deploy the app online for easy sharing.

Enhance the AI model with more advanced techniques.

Add more features and improve UI.

Feel free to contribute or suggest improvements!
