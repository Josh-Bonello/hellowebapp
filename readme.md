# Hello Web App

This is a proof of concept for utilizing Django to manage and maintain a website. It has been created by following the tutorial provided by [HelloWebApp](https://hellowebapp.com/).

### Prerequisites

What things you need to install the software and how to install them

* A native *NIX environment or [Git Bash](https://git-scm.com/downloads)
* [Python 2.7 or greater](https://www.python.org/download/releases/2.7/)
* [Pip](https://pip.pypa.io/en/stable/installing/)
* [VirtualEnv](https://virtualenv.pypa.io/en/stable/)

### Installing

Create a virtual environment

```
virtualenv ~/myhellowebapp
```

Enter the virtual environment

```
source ~/myhellowebapp/bin/activate
```

Install the requirements.txt file

```
pip install -r ~/myhellowebapp/requirements.txt
```

## Running the tests

To ensure that the app is compiling and logically stable, run the Django test suite.

```
python ~/myhellowebapp/manage.py test
```

## Deployment

To deploy to your localhost, execute the following command

```
python ~/myhellowebapp/manage.py runserver
```

## Built With

* [Django] (https://www.djangoproject.com/)
* [Python](https://maven.apache.org/)


## Authors

* **Josh Bonello** - *Initial work* - [Josh-Bonello](https://github.com/Josh-Bonello)

## Acknowledgments

* A special thanks to Tracy Osborn for writing Hello Web App and for her free online resource.

