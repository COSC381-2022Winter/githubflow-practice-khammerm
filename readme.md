Steps for starting the website:
1. Create your virtual environment: `python3 -m venv venv`
2. Activate the virtual environment: `source venv/bin/activate`
3. Install the required dependencies: `python3 -m pip install -r requirements.txt`
4. Use the environment variables for the flask app: `source env-var.sh`
5. Initialize the flask database: `flask init-db`
6. Start the website: `flask run` (to make externally visible: `flask run --host 0.0.0.0`)
7. The default website address is http://127.0.0.1:5000/movies/ (IP will vary if making externally visible, or using EC2 for example.)

