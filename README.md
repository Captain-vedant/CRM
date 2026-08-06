# Customer Relationship Management (CRM) System

## Overview

The **Customer Relationship Management (CRM) System** is a web-based application developed using the **Django Framework** to streamline customer management and business operations. It provides a centralized platform for managing companies, contacts, leads, requests, deals, products, departments, and users through an intuitive interface.

The project demonstrates the implementation of a complete CRM workflow while focusing on usability, modularity, and efficient data management.

---

## Key Features

- Company Management
- Contact Management
- Lead Management
- Request Management
- Deal Management
- Product Management
- Department Management
- User Authentication & Authorization
- Role-Based Administrative Panel
- Industry Classification
- Search and Filtering
- Centralized Customer Database
- Responsive User Interface

---

## Project Modules

### Welcome Page
A custom landing page designed to provide a professional entry point to the application with separate access to the CRM Dashboard and the Administrative Panel.

### Authentication
Secure login system that authenticates users before granting access to application resources.

### CRM Dashboard
The central workspace providing quick access to all CRM modules including Companies, Contacts, Leads, Requests, Deals, Products, and Reports.

### Company Management
Maintain company records including business details, contact information, location, industry classification, and associated contacts.

### Contact Management
Manage customer contact information and maintain relationships with associated companies.

### Lead Management
Create, monitor, and manage potential customers throughout the sales process.

### Request Management
Handle customer requests efficiently by assigning and processing them through the appropriate workflow.

### Deal Management
Track business opportunities and monitor deal progress from initiation to completion.

### Product Management
Maintain product information that can be associated with customer requests and business deals.

### Administration
Manage users, groups, departments, permissions, industries, client types, and other master data through Django's administrative interface.

---

## System Workflow

```
Welcome Page
        │
        ▼
 User Authentication
        │
        ▼
   CRM Dashboard
        │
 ┌──────┼────────────────────────────────────┐
 │      │      │      │      │      │
 ▼      ▼      ▼      ▼      ▼      ▼
Companies Contacts Leads Requests Deals Products
        │
        ▼
   SQLite Database
```

---

## Technology Stack

| Component | Technology |
|-----------|------------|
| Programming Language | Python |
| Framework | Django |
| Frontend | HTML5, CSS3, JavaScript |
| Database | SQLite |
| Backend | Django ORM |
| Template Engine | Django Templates |
| Development Environment | Visual Studio Code |
| Version Control | Git |

---

## Project Structure

```
django-crm/
│
├── common/
├── crm/
├── webcrm/
├── templates/
├── static/
├── media/
├── manage.py
├── requirements.txt
└── README.md
```

---

## Core Functionalities

- Create and manage company records
- Maintain customer contact information
- Track and manage sales leads
- Convert leads into active customer records
- Handle customer requests
- Monitor business deals
- Organize products
- Manage departments and users
- Maintain industries and client types
- Perform administrative operations through a centralized dashboard

---

## Customizations Implemented

During the development of this project, the following enhancements were implemented:

- Designed a dedicated Welcome Page
- Added separate access for CRM Dashboard and Admin Panel
- Enhanced the administrative interface
- Improved project navigation
- Configured complete CRM workflow
- Tested and validated lead conversion process
- Improved overall user experience and presentation

---

## Benefits

- Centralized customer information
- Improved organization of business data
- Reduced manual record management
- Efficient lead tracking
- Better customer relationship management
- Structured workflow for business operations
- Scalable and modular application architecture

---

## Future Enhancements

- Email Integration
- Notification System
- Advanced Analytics Dashboard
- REST API Support
- Mobile Application
- Cloud Deployment
- Interactive Reports
- Real-Time Notifications
- AI-assisted Lead Analysis
- Enhanced Data Visualization

---

## Author

**Vedant Pandey**

B.Tech Student

Full Stack Web Development Intern

---

## Acknowledgement

This project represents the implementation, configuration, customization, testing, and enhancement of a Django-based Customer Relationship Management system as part of an academic internship. The work focuses on understanding enterprise CRM workflows, improving the user interface, and demonstrating practical web application development using Django.
