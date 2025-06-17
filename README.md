# ProManager

ProManager is a Flask-based web application designed to manage user authentication and provide a simple interface for users. This README provides an overview of the project, setup instructions, and usage guidelines.

## Project Structure

```
ProManager
├── app.py               # Main entry point of the Flask application
├── requirements.txt     # Lists dependencies required for the project
├── templates            # Contains HTML files for the application
│   ├── index.html      # Main page of the application
│   └── login.html      # Login page for user authentication
├── static              # Contains static files like CSS and JS
│   └── style.css       # CSS styles for the application
├── database            # Optional: Store SQLite file here
│   └── promanager.db   # SQLite database file
└── README.md           # Documentation for the project
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd ProManager
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```
   python app.py
   ```

5. **Access the application:**
   Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

- Navigate to the main page to view the application.
- Use the login page to authenticate users.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
