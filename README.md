<h1 align='center'>Django Web Scraper</h1>

<p align="center">
    <b>A simple Django project for web scraping and displaying results</b>
</p>

<details>
<summary>Table of Contents</summary>
<br>

- [What and why](#what-and-why)
- [Setup](#setup)
- [Usage](#usage)

</details>

# What and why

This project is a Django-based web scraper. It allows you to scrape data from the web and display the results in your browser. The project is intended as a learning tool for Django and web scraping.

# Setup

**Requirements:**  
- Python 3.10+  
- [pip](https://pip.pypa.io/en/stable/)  

**1. Clone the repository:**
```sh
git clone <your-repo-url>
cd web_scraper
```

**2. Create and activate a virtual environment:**
```sh
python3 -m venv .venv
source .venv/bin/activate
```

**3. Install dependencies:**
```sh
pip install django
pip install bs4 # Beautiful Soup library
pip install requests # requests library
```

**4. Apply migrations:**
```sh
cd mysite
python manage.py migrate
```

**5. Run the development server:**
```sh
python manage.py runserver
```

# Usage

Once the server is running, open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/).  
You can use the web interface to start a web scraping job and view the results.

Happy scraping!