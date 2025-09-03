# Customer360 – Unified Customer Profile Dashboard

## Overview
Customer360 is a web application that aggregates customer data from multiple sources—Sales, Support, and Billing—into a **single unified dashboard**. The project demonstrates backend development, API integration, and database management skills.

## Tech Stack
- **Backend:** Python, Django, FastAPI  
- **Database:** MySQL  
- **APIs:** RESTful APIs for data aggregation  
- **Tools & Libraries:** Pandas, NumPy, SQLAlchemy  

## Features
- Aggregates data from multiple mock systems into a single dashboard  
- Implements microservices using FastAPI for API integration  
- User authentication and role-based access control  
- SQL-backed storage for tracking customer interactions  
- Demonstrates concepts of data aggregation, API integration, and microservice architecture  

## Project Structure
Customer360/
│
├── backend/ # Django and FastAPI services
├── database/ # SQL scripts and schema
├── api_clients/ # Modules to simulate external API calls
├── requirements.txt # Python dependencies
└── README.md # Project documentation
## How to Run
1. Clone the repository  =
 
   git clone https://github.com/prachibangre100/Customer360.git

2. Install dependencies - 
pip install -r requirements.txt
Set up the MySQL database and update connection settings

3. Run Django and FastAPI services -

python manage.py runserver   # Django
uvicorn api_service:app --reload   # FastAPI
