# AboutThis is a simple Flask application created during BootCamp course in 2021.

This application uses following libraries:

- SQLAlchemyforSQLstuff- Flaskforwebgoodness- Someterminalcandies(ex.tqdm)- UsespipenvformanagingdependenciesApplication can be easily deployed to Heroku or DigitalOcean. Have been tested only on Python 3.

# ConfigfileMake sure to create .env file in your project root (see .env_example) which contains correct DATABASE URI connection string. This will allow you to run application locally and connect to correct database. Locally you can use SQLite.

In order to create needed tables do following:
`# Run pipenv commands if you didn't yet# pipenv install# pipenv shellpython create_db.py`# Runnigapplication`shell# optional if you don't have pipenv installedpip install pipenv pipenv install pipenv shell python app.py `# InsertingdatafromCSVfiletodatabase- DownloadCSVdatahere:https://www.avoindata.fi/data/fi/dataset/alkoholielinkeinorekisteri(Alkoholijuomienanniskelupaikat)asCSVfile.- PlaceCSVfileinprojectroot- RenameCSVfiletodata.csv- Run`pythoncsv2db.py`withinpythonvirtualenviroment# DeplymenttoDigitalOceanappplatform## SettingupAppplatforminDigitalOcean![](https://dl.dropboxusercontent.com/s/1bd57jbxb5j29cm/2021-02-17_11-36-05.gif)# DcoumentationDocumentation can be found in doc folder.

# AuthorArtem Daniliants / www.daniliants.com

# LicenseCopyright 2021 Artem Daniliants

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
