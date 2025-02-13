# Scraper
Job lists scraper cuz I'm lazy to find them myself.

This project is a simple web scraper built with Python and Flask that retrieves job listings for "Software Developer Intern" positions from LinkedIn and displays them in a web interface.

Features

Scrapes LinkedIn job postings for "Software Developer Intern" roles in Mexico.

Displays job listings in a simple HTML webpage.

Uses Flask to serve the scraped data dynamically.

Filters jobs based on keywords to improve relevance.

Installation

Prerequisites

Make sure you have Python installed on your system. You can download it from python.org.

Install Required Libraries

Clone the repository and install dependencies:

pip install flask requests beautifulsoup4

Usage

Run the Flask application:

python app.py

Open a web browser and go to:

http://127.0.0.1:5000/

Click on job links to view detailed listings on LinkedIn.

Project Structure

|-- app.py                # Main Flask application
|-- README.md             # Project documentation
|-- requirements.txt      # Dependencies

Deployment

You can deploy this project on platforms like Render or PythonAnywhere for online access.

License

This project is open-source under the MIT License.

Feel free to contribute by submitting issues or pull requests!

