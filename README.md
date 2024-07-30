# FashionEase
Fashion Resource Management
FashionEase - Fashion Supply and Resource Management
FashionEase is an application designed to streamline supply and resource management in the fashion industry. This application allows suppliers, manufacturers, and designers to manage their materials, designs, and bulk orders efficiently.

Features
Supplier Page
 View Materials: Display all available materials.
 Add Material: Add new materials to the database.
 Update Material: Update the price of existing materials.
 Delete Material: Remove materials from the database.
Manufacturer Page
 View Designs: Display all available designs.
 View Materials: Display all available materials.
 View Bulk Orders: Display bulk orders for designs.
Designer Page
Upload Designs: Upload new designs for manufacturers to view.
Tech Stack
 Frontend
   Streamlit: Used for building the web interface and user interaction.
Backend
   Python: Primary programming language for the backend logic.
   MySQL: Database management system used to store and manage data.
Libraries and Packages
pandas: Used for data manipulation and analysis.
mysql-connector-python: MySQL driver for Python to connect and interact with the MySQL database.
Infrastructure
Localhost: The application is configured to run on a local server.
Authentication and Security
Basic Authentication: The MySQL database connection is secured with a username and password.

Setup and Installation
Python: Ensure Python is installed on your system.
Streamlit: Install Streamlit using:
pip install streamlit
pandas: Install pandas using:
pip install pandas
mysql-connector-python: Install the MySQL connector using:
pip install mysql-connector-python
MySQL Database: Set up and configure your MySQL database with the necessary tables and data.
Running the Application
Ensure your MySQL database is running and accessible.
Run the Streamlit app with the command:
streamlit run app.py
Access the application through the URL provided by Streamlit (usually http://localhost:8501).
