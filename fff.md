David, Ruzzel S.
Montoya, Elijah James

To execute this project, ensure that Python is installed on your computer. After downloading the project, follow these steps:

Step 1: Extract or unzip the downloaded file.

Step 2: Navigate to the project folder and open the command prompt (cmd).

Step 3: Activate the virtual environment and install the required dependencies on Windows using the commands below:

bash
Copy code
python -m venv venv
.\venv\scripts\activate
python -m pip install -r requirements.txt
Step 4: Run the Flask app with the following commands:

bash
Copy code
set FLASK_APP=app.py
set FLASK_ENV=development
flask run
These steps involve creating a virtual environment, activating it, installing necessary packages from the requirements.txt file, and then running the Flask app. Adjustments might be needed based on your operating system or specific project requirements.