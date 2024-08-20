# Language Detection and Translation Application

This is a Flask-based web application that detects the language of a given text and translates it into a target language of your choice. It uses `langdetect` for language detection and `googletrans` for translation.

## Features

- **Language Detection**: Automatically detects the language of the input text.
- **Language Translation**: Translates the detected text into a user-selected target language.
- **User-Friendly Interface**: Simple web interface for easy text input and language selection.

## Live Demo

You can try the live demo of the application here: [Language Detection and Translation](https://languagedetection-translation.onrender.com)

## Installation

Follow these steps to set up and run the application locally:

### Prerequisites

- Python 3.7 or later
- Pip (Python package installer)

### Clone the Repository

```bash
git clone https://github.com/ashwarytripath/languagedetection-translation.git
cd languagedetection-translation
```

### Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Running the Application Locally

You can run the application locally using Flask’s built-in development server:

```bash
flask run
```

The application will be accessible at `http://127.0.0.1:5000`.

## Deployment

The application is deployed and accessible at [https://languagedetection-translation.onrender.com](https://languagedetection-translation.onrender.com).

To deploy the application in a production environment using `gunicorn`, run:

```bash
gunicorn app:app
```

This command starts the application using the Gunicorn WSGI server.

### Example for Deployment with Render

1. Ensure your `requirements.txt` is set up correctly.
2. Deploy using Render by connecting your GitHub repository and following their deployment guide.

## Usage

1. Navigate to the home page of the application.
2. Enter the text you want to detect and translate.
3. Select the target language from the dropdown menu.
4. Click "Translate" to see the detected language and its translation.

## Files and Directories

- **app.py**: The main Flask application file.
- **templates/index.html**: The HTML template for the web interface.
- **requirements.txt**: Lists the Python dependencies for the application.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue if you find a bug or have a suggestion.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [langdetect](https://pypi.org/project/langdetect/)
- [googletrans](https://pypi.org/project/googletrans/)

