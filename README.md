# Book_recomadation
Book_recomadation

**##Overview**
This is a Book Recommendation System built using Python, Flask, and machine learning techniques. It provides book recommendations based on two approaches:
 **(1)Popularity-Based Recommendation**
 **(2)Collaborative Filtering-Based Recommendation**

**##Features**
(1) Suggests popular books based on average ratings and number of reviews.
(2) Uses collaborative filtering to recommend books similar to user preferences.
(3) Provides an easy-to-use web interface using Flask.

**##Models Used**

**1. Popularity-Based Recommendation**
  Selects books with the highest average ratings.
  Filters books that have at least 200 ratings.

**2. Collaborative Filtering-Based Recommendation**
   Filters books with at least 200 ratings and at least 50 users who have rated them.
   Uses Euclidean distance to compute book similarity and suggest relevant books.

**##Technologies Used**
  Python (pandas, NumPy, scikit-learn, Flask)
  Flask (for web deployment)
  Pickle (for model persistence)
  Render (for hosting the web application)

**##Installation & Usage**

**1. Clone the repository**
  git clone <your-repo-url>
  cd book-recommendation

**2. Install dependencies**
  pip install -r requirements.txt

**3. Run the Flask app**
  python app.py
  Then, open http://127.0.0.1:5000/ in your browser.

**##Deployment on Render**
  Push your project to GitHub.
  Connect the repository to Render.
  Deploy the Flask application.
  **url :-https://book-recomadation.onrender.com**
This project is open-source and free to use.


