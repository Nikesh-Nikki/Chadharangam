# To run the server:

## First time setup:
1. First, create a virtual environment for python using ```virtualenv .venv``` in your current directory.
2. Now, activate this virtual environment using ```source .venv/bin/activate``` for Bash on Linux. Alternatively, if on Windows, type ```.venv\Scripts\activate```.
3. Now, install the required libraries by running ```pip install -r requirements.txt``` while inside the virtual environment.
4. Deactivate this virtual environment by typing ```deactivate```.

## Every other time:
1. Activate this virtual environment using ```source .venv/bin/activate``` for Bash on Linux. Alternatively, if on Windows, type ```.venv\Scripts\activate```.
2. Now, run "python app.py" to start the server up.
3. Navigate to the URL as printed in the terminal (usually http://127.0.0.1:5000).
4. After you're done, shut down the server by simply pressing ```Ctrl + C``` to terminate the Flask server.
5. Deactivate this virtual environment by typing ```deactivate```.

---
