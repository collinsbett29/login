# INTERINTEL TECHNOLOGIES LOGIN PAGE

### Built By;
Collins Kipkorir Bett

### Description
- This application was built by Django==3.1.5 a python framework.
- This is a login and a success login page web application.


## Setup/Installation Requirements

* Install python version 3.9.2
* Clone https://github.com/collinsbett29/login
* Atleast have a computer or a laptop
* Have a stable internet connection

* Create a virtual environment and activate it.

   `$ pip install virtualenv`

   ```$ virtualenv env```

   ```$ env\Scripts\activate```


![](images/screenshot(13).png)

* install Django

   ```$ pip install  Django==3.1.5```

## Running tests
   ```$ python3.6 manage.py test login```

## Running the Development server
  ```$ python3.6 manage.py runserver```

## Specifications

| Behavior        | Input           | Output |
| ------------- |:-------------:| -----:|
| Display a login page | N/A | **Click** login to be redirected to a login form |
| Display a login form | Fill the login form and `click login` | You will be redirected to InterIntel homepage |
| Display current user logged, homepage and LOGOUT button | **Click** LOGOUT button to logout | You will logged out and redirected to login page |

## Deployment
-Install uwsgi into the virtual environment.

   ```$pip install uwsgi```

-Run uwisgi

   ```uwsgi --http :8000 --wsgi-file test.py```

## Technologies Used

  * Python version 3.9.2
  * Django version 3.1.5
  * Bootstrap 4
  * HTML & CSS 
  * uwsgi/nginx


## License

This project is licenced under the MIT License.


                                © Collins K. Bett | 2021





