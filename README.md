# Blog Website

This is a blog website built using Python and Django. Follow the steps below to download, set up, and run the project on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Python (version 3.x)
- pip (Python package installer)
- Git (to clone the repository)
- A virtual environment tool (optional)

## Installation

### 1. Clone the repository

First, clone this repository to your local machine using Git.

```bash
git clone https://github.com/PaschosEleftherios/django_blog.git
cd django_blog
```

### 2. Install dependencies

Once inside your virtual environment, install the necessary packages using `pip`:

```bash
pip install -r requirements.txt
```

### 3. Set up the database.

Run the following commands to set up the database:

```bash
python3 manage.py makemigrations
python3 manage.py migrate
```
### 4. Run the Server.

Finally, start the Django development server:

```bash
python3 manage.py runserver
```

Open your web browser and navigate to localhost:8000/ to view the website.

