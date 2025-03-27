
# Web Car Recommender App

This project is a web-based car recommendation system that allows users to explore and filter car options based on preferences. It combines a machine learning recommender model with a front-end built using Flask and standard web technologies.

🌐 **Live Demo**: [https://carrecommender.pythonanywhere.com/](https://carrecommender.pythonanywhere.com/)

## Features

- Interactive web interface for car selection and filtering
- Data-driven recommendation engine based on user input
- Visual feedback and car details display
- Real-time filtering by price, mileage, brand, and other attributes

## Technologies

- Python
- Flask
- HTML, CSS, JavaScript
- Pandas
- Scikit-learn
- Bootstrap (via templates)

## File Structure

- `app.py` – Main Flask app and routing logic
- `Recommender_Cars_DF_Ready.csv` – Car dataset used for filtering and recommendations
- `templates/` – HTML templates (Jinja2)
- `static/`, `css/`, `js/` – Static files for styling and interactivity

## How to Run

1. Install dependencies:
   ```bash
   pip install flask pandas scikit-learn
   ```

2. Run the app:
   ```bash
   python app.py
   ```

3. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Author

Mariusz Sołtycz

---

This project was developed as part of my BSc Final Project and MSc Artificial Intelligence coursework and showcases full-stack integration of machine learning and web technologies.
