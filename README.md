# Smart Recipe - Your Meal Planning Assistant

A modern web application for managing recipes and meal planning, built with Flask and featuring a beautiful, animated interface.

## Features

- User Authentication (Register/Login)
- Recipe Management (Create, Read, Update, Delete)
- Beautiful Modern UI with Animations
- Responsive Design
- Secure Form Handling
- Database Integration
- Image Upload Support
- Interactive Recipe Cards
- Meal Planning System

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd smart-recipe
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix or MacOS:
```bash
source venv/bin/activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Initialize the database:
```bash
python init_db.py
```

## Configuration

1. Create a `.env` file in the root directory with the following content:
```
SECRET_KEY=your-secret-key
SQLALCHEMY_DATABASE_URI=sqlite:///recipes.db
```

2. Ensure the `instance` directory exists for the SQLite database.

## Running the Application

1. Make sure your virtual environment is activated
2. Run the Flask application:
```bash
python app.py
```
3. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
smart-recipe/
├── app.py              # Main application file
├── config.py           # Configuration settings
├── init_db.py         # Database initialization script
├── requirements.txt    # Project dependencies
├── instance/          # Database directory
├── static/            # Static files (CSS, JS, images)
│   ├── css/
│   ├── js/
│   └── images/
├── templates/         # HTML templates
└── venv/             # Virtual environment
```

## UI Features

- Modern gradient effects
- Smooth animations
- Interactive hover effects
- Responsive design
- Custom scrollbar
- Loading animations
- Card effects
- Beautiful typography

## Security Features

- CSRF Protection
- Secure Password Handling
- Form Validation
- Secure Session Management
- Protected Routes
- Input Sanitization

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Flask Framework
- Bootstrap
- SQLAlchemy
- WTForms
- Flask-Login 
