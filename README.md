#  Medical Office Information System

## Project Overview

Managing a medical office involves sensitive data, complex workflows and constant interactions between patients, doctors and administrators. Manual or fragmented systems increase the risk of errors and reduce efficiency.

This project provides a complete Information System that digitalizes and optimizes all medical office activities, from appointment scheduling to medical record management and administrative operations.



## Project Objectives

The goal of this system is to offer a centralized, secure and reliable platform that improves the quality of medical services and administrative efficiency.

It allows:
- Better organization of patient data
- Easier appointment management
- Digital medical records and prescriptions
- Improved coordination between doctors and administration

The system was developed following a structured approach based on business analysis, data modeling and full-stack implementation.



## System Analysis and Design

### Data Flow Diagram (DFD)
Describes how data moves between patients, doctors, management and the system.

![DFD](docs/DFD.drawio.png)

### Global Dependency Diagram (GDD)
Represents the relationships and dependencies between the main business processes.

![GDD](docs/GDD.png)

### Logical Data Model (MLD)
Defines the structure of the database including tables, attributes and relationships used in MySQL.

![MLD](docs/MLD.drawio.png)



## Technology Stack

- Frontend: React  
- Backend: FastAPI (REST API with Swagger documentation)  
- Database: MySQL  


## Project Structure

```bash
├── docs/               # Diagrams (DFD, MLD, GDD) and documentation
├── backend/            # FastAPI application
├── frontend/           # React application
├── mock_data/          # Database seeding scripts
└── README.md
```



##  How to Run

### 1. Clone the repository
```bash
git clone https://github.com/SalmaTAMMARI12/Information_System.git
cd Information_System
```

### 2. Configure the MySQL database
Create a MySQL database and update the connection settings in the backend configuration file.

### 3. Install backend dependencies
```bash
pip install -r requirements.txt
```

### 4. Start the backend
```bash
uvicorn backend.main:app --reload
```

The API will be available at:
```
http://127.0.0.1:8000
```

Swagger documentation:
```
http://127.0.0.1:8000/docs
```

### 5. Start the frontend
```bash
cd frontend
npm install
npm start
```

The web application will run at:
```
http://localhost:3000
```


## Application Features

Patient: online appointment booking, modification and cancellation  
Doctor: digital prescriptions and medical records  
Administration: staff and leave management  



## Team

This project was developed by:

- Salma Tammari  
- Assmaa El Hidani  
- Lina Raoui 

Data Engineering students at ENSIAS  
Academic year 2025–2026

