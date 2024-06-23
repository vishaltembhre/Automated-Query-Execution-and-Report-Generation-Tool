## Automated Data Pipeline with Progress Tracking and Reporting

This Python script streamlines data processing and reporting, saving you manual work and keeping you informed!

## Key Features:

Scheduled Execution: Set the script to run at specific times using the schedule function (perfect for recurring tasks!). ⏰

User-Defined Inputs: Easily customize file paths, database connections, and output filenames for a flexible workflow.

Error Handling: The script gracefully handles exceptions and logs errors in a dedicated file, ensuring a smooth execution.

Progress Tracking: A handy progress bar keeps you updated on the script's progress, so you can relax and grab a coffee. ☕️

Data Cleaning: The script cleans data by removing unwanted characters, ensuring data integrity.

Result Formatting: Data is formatted into an Excel spreadsheet with pivot tables and charts for easy analysis.

Email Notification: Upon completion, the script sends an email with results and logs attached, keeping you informed.

## Getting Started:

Clone the Repository: Use git clone https://github.com/vishaltembhre/Automated-Query-Execution-and-Report-Generation-Tool.git

Install Dependencies: Navigate to the project directory and run pip install -r requirements.txt to install required libraries.

Configure Settings: Update connection details (host, database, username, password) in the Connect_PROD and Connect_SIT functions for your environment.

Customize Inputs: Modify file paths, output filenames, and SQL queries within the main function to match your specific needs.

Schedule Execution (Optional): Uncomment the desired schedule lines in the main function to run the script automatically.

## Libraries:

Python

pandas (data manipulation)

psycopg2 (PostgreSQL connection)

win32com (Outlook automation)

matplotlib & seaborn (data visualization)

shutil (file management)

## Let's Automate!

This script provides a solid foundation for automating data processing tasks. Feel free to customize it further to fit your specific requirements!