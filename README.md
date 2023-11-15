# Operating instructions

1. Clone this git repository
2. Make clean environment running python 3.10.5. Activate the environment, navigate to the location of the requirements.txt file and ```run pip install -r requirements.txt``` 
3. Follow the instruction on [Google sheets quickstart for Python](https://developers.google.com/sheets/api/quickstart/python) to create google sheets service account. Save the create json file as ```google_key.json``` in the same directory as the ```analyze.ipynb``` notebook.
4. Populate ```SHEET_ID``` with the google sheet id.
5. Execute ```analyze.ipynb```, using the above created environment
