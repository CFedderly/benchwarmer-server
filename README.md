# benchwarmer-server
Server side for sub finding app. Tentatively, Python, Django, PostgreSQL.

## Setup
Install python 3:  
Windows - https://www.python.org/downloads/windows/  
Linux - `$sudo apt-get install python3.4`  
  
Create virtual environment:  
`$ pip install virtualenv`  
`$ virtualenv <virtualenv-directory>/benchwarmer`  

Activate virtual environment:  
`$ source <virtualenv-directory>/benchwarmer/Scripts/activate`

Install project python dependencies:  
`(benchwarmer)$ pip install -r requirements.txt`  

Run the server:  
`(benchwarmer)$ python benchwarmer/manage.py runserver`