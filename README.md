# CS340-Grazioso-Salvare-Dashboard
Data driven search and rescue dashboard integrating MongoDB, reusable CRUD logic, and dynamic Dash visualizations.

Ronnie Corpuz

Project Overview

This project implements a full stack MongoDB dashboard for Grazioso Salvare, a search and rescue animal training organization. The application allows users to filter shelter dogs by rescue category and visualize results through an interactive data table, a breed distribution chart, and a geolocation map.

The system follows the MVC design pattern:

Model: MongoDB database

Controller: Python CRUD module and Dash callbacks

View: Dash dashboard interface

The dashboard dynamically connects user interactions to database queries through a reusable CRUD module.

How do you write programs that are maintainable, readable, and adaptable?

Maintainability begins with separation of concerns. In this project, database operations were isolated inside a reusable CRUD Python module rather than embedded directly in dashboard logic. This improved readability and reduced duplication.

The advantages of this structure include:

Centralized database access

Easier debugging and testing

Reduced code repetition

Improved scalability

If database credentials, schema, or query logic change, updates only need to be made inside the CRUD module. In the future, this module could be reused for APIs, analytics pipelines, or other web applications that require structured MongoDB access.

How do you approach a problem as a computer scientist?

I approach problems by breaking them into structured layers:

Understand the data model

Translate requirements into database queries

Validate results at the database layer

Connect backend logic to frontend components

Test each component incrementally

This project required thinking across database design, backend logic, and user interface behavior. Unlike smaller assignments focused only on algorithms, this required integration across multiple technologies and careful validation of dynamic behavior.

In future database projects, I would continue using schema inspection, modular design, and incremental testing to ensure reliability and scalability.

What do computer scientists do, and why does it matter?

Computer scientists design systems that transform raw data into meaningful information. In this project, the dashboard enables Grazioso Salvare to identify rescue dog candidates efficiently using dynamic filtering and visualization tools.

Instead of manually reviewing records, users can:

Filter dogs by rescue category

Analyze breed distribution

Locate animals geographically

This improves operational efficiency, supports data-driven decision making, and reduces human error. Structured software solutions like this directly support real-world organizational goals.

Technologies Used

MongoDB

PyMongo

Python

Dash

Plotly Express

Dash Leaflet

Jupyter Dash

Repository Contents

ProjectTwoDashboard.ipynb

CRUD_Python_Module.py

Project Two README (Word Document with screenshots)
