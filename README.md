## TITLE
Django-Gallery

## AUTHOR
Amwata Albert

## DESCRIPTION
A django personal gallery application that displays my photos for others to see.

## BEHAVIOUR DRIVEN DEVELOPMENT(BDD)

| Behaviour | Input                     | Output                    |
| --------- | ------------------------- | ------------------------- |
|Navigate to website| Click on an image | Image is expanded and further details of the image displayed |
|Navigate to locations in navbar| Click on a location|Photos from that location are displayed|
|Navigate to search input| Type in a photo category e.g cars|Photos of that particular category are displayed|


## SETUP
### Requirements
* Django 1.11
* Python 3.5 and above 
### Installation
* Fork the data onto your own personal repository.
* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* Access the live site using the local host provided

#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/Amwata-Albert/Gallery
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3.6 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste the following filling where appropriate:
```
SECRET_KEY='your_Secret_key'
DEBUG=True
DB_USER='your_database_username'
DB_PASSWORD='your_database_password'
DB_HOST='127.0.0.1'
MODE='dev' 
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependencies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.6 manage.py makemigrations && python3.6 manage.py migrate
```

#### Run the app
```bash
python3.8 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)

## KNOWN BUGS
None

## TECHNOLOGIES
* Python3.8
* Django
* Javascript
* Css
* Scss

## LICENSE
[MIT](https://github.com/Amwata-Albert/Gallery)