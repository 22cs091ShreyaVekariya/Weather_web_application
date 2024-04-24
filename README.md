### Weather Condition Web App
This is a simple web application built with Flask that provides weather condition information for a given location.

### Features
1. Displays current weather conditions such as temperature, humidity, wind speed, etc.
2. Allows users to search for weather conditions by location.
3. Provides a clean and intuitive user interface.
4. Installation
5. Clone the repository:
6. bash
### Copy code
'''
git clone https://github.com/22cs091ShreyaVekariya/Weather_web_application.git
'''
7. Navigate to the project directory:
8. bash
Copy code
'''
cd Weather_web_application
'''
Install dependencies:
bash
Copy code
'''
pip install -r requirements.txt
'''
### Usage
Run the Flask application:
bash
Copy code
'''
python app.py
'''
Open your web browser and go to http://localhost:5000.
Enter the location for which you want to check the weather conditions in the provided input field and click on the "Search" button.
The weather conditions for the specified location will be displayed on the screen.
### Configuration
You can configure the application to use a different weather API provider or adjust other settings in the config.py file.

### Dependencies
Flask: A lightweight WSGI web application framework.
requests: A simple HTTP library for Python, used for making API requests.
