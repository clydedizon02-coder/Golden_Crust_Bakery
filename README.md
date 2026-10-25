# Golden Crust Bakery – Django Final Project

A multi-page bakery website built with **Django Templates** for the DMMMSU-NLUC College of Information Technology Final Project.

## Overview

**Golden Crust Bakery** is a neighborhood bakery site in Bacnotan, La Union with Home, About, Menu, Gallery, and Contact pages.

## Features

- 5 pages with template inheritance (`base.html`, `{% extends %}`, `{% block %}`)
- Navbar & footer via `{% include %}`
- Named URLs with `{% url %}`
- Static CSS with `{% load static %}` / `{% static %}`
- Responsive design

## Setup

```bash
git clone https://github.com/clydedizon02-coder/Golden_Crust_Bakery.git
cd Golden_Crust_Bakery
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/

## Group / Author

DMMMSU-NLUC · College of Information Technology
Final Project: Django Templates & GitHub
