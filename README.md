# papi
papi project build with flask

Run the code (navigate to your api folder in the command line and enter python api.py). Once the server is running, visit our route URL to view the data in the catalog:

http://127.0.0.1:5000/api/v1/resources/books/all

## api.py
This will display JSAN data 
http://127.0.0.1:5000/api/v1/resources/books/all

## papi api.py
This file has updated options to filter the search records
Once you’ve updated your API with the api_id function, run your code as before (python api.py from your api directory) and visit the below URLs to test the new filtering capability:
[127.0.0.1:5000/api/v1/resources/books?id=0 127.0.0.1:5000/api/v1/resources/books?id=1]
[127.0.0.1:5000/api/v1/resources/books?id=2 127.0.0.1:5000/api/v1/resources/books?id=3]
