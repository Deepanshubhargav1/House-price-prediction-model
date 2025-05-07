📂 Project Structure
├── app.html               # Frontend HTML page
├── app.css                # Styling for the frontend
├── app.js                 # JavaScript to handle UI logic and API calls
├── server.py              # Flask backend server
├── util.py                # Utility functions used in backend
├── bhp.ipynb              # Data preprocessing & model training notebook
├── banglore_home_price_model.pickle  # Trained model
├── columns.json           # Metadata about model input features
🚀 Features
Predict housing price in lakhs for Bangalore city

Choose from multiple locations

Input area, number of BHKs, and bathrooms

Interactive web interface

🧰 Technologies Used
Frontend: HTML, CSS, JavaScript, jQuery

Backend: Python (Flask)

ML Model: Scikit-learn (trained separately in Jupyter Notebook)

Data: Real estate data scraped and preprocessed in bhp.ipynb

⚙️ Setup Instructions
Clone the Repository
git clone https://github.com/yourusername/bangalore-home-price-predictor.git
cd bangalore-home-price-predictor

Install Dependencies
pip install flask numpy pandas scikit-learn

Run the Flask Server
python server.py
Open the Frontend

Open app.html in your browser.

🔌 API Endpoints
GET /get_location_names
Returns list of location names

POST /predict_home_price
Inputs: total_sqft, location, bhk, bath
Returns: Predicted price

📄 License
This project is open-source and available under the MIT License.
