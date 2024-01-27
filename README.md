# covid19-tracker-webapp

## Description
This is the COVID19 Tracker website, where we are supposed to display the statistics by fetching it from the standard API. The details will be fetched and displayed over the website in a user friendly way.

## API to be USed
- Novel COVID19 API
  - [Docs](https://disease.sh/docs)
  - [API](https://disease.sh/v2/all)

#### Frontend
- Good UI to attract people
- Mobile Friendly Website
- Header, Navigation and Footer
- Search Option to search for the specific regions

#### Backend
- Database to store all the important statistical information
- Display Statistics on the Website
- Add news feed related to the COVID-19
- Display Charts on the website

#### API
- Using API to fetch the details of regions.

## Set-up Guide

#### Clone the Project
```sh
git clone git@github.com:bellatrixdatacommunity/covid19-tracker-webapp.git
cd covid19-tracker-webapp
```

#### Make a new branch using following command
```sh
git checkout -b "<your-branch>"
```

#### Create a Virtual Environment and activate it
```sh
python -m venv venv
source venv/bin/activate
```

#### Installing Dependencies
```sh
python -m pip install -r requirements.txt
```

#### Makemigrations to the db
```sh
python manage.py makemigrations
python manage.py migrate
```

#### Starting the Server
```sh
python manage.py runserver
```

```txt
Code .... .... ....
.... Code .... ....
.... .... Code ....
.... .... .... Code
```

#### Stage your changes, commit, and push using the following commands
```sh
git add .
git commit -m "<commit message>"
git push origin "<your-branch>"
```

#### Deactivate your Virtual Environment
```sh
source deactivate
```








