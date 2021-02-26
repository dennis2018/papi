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
### [127.0.0.1:5000/api/v1/resources/books?id=0] [127.0.0.1:5000/api/v1/resources/books?id=1]
http://127.0.0.1:5000/api/v1/resources/books?id=0

### [127.0.0.1:5000/api/v1/resources/books?id=2] [127.0.0.1:5000/api/v1/resources/books?id=3]
http://127.0.0.1:5000/api/v1/resources/books?id=2

## papi api.py
Before we modify our code, first download the example database from this location and copy the file to your api folder using your graphical user interface. 
The final version of our API will query this database when returning results to users.

Copy the below code into your text editor. As before, we’ll examine the code more closely once you have it running.

http://127.0.0.1:5000/api/v1/resources/books/all
http://127.0.0.1:5000/api/v1/resources/books?
author=Connie+Willis http://127.0.0.1:5000/api/v1/resources/books?
author=Connie+Willis&published=1999 http://127.0.0.1:5000/api/v1/resources/books?published=2010
