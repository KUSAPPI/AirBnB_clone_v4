# AirBnB Clone: Flask Web Application

## Description

This is a directory that contains all the Web Application files for the Python Flask App.
The Flask App and nginx are connected with gunicorn Web Server Gateway
Interface (WSGI).

## Learning Objective
How cool it is to request your own API
How to modify an HTML element style
How to get and update an HTML element content
How to modify the DOM
How to make a GET request with JQuery Ajax
How to make a POST request with JQuery Ajax
How to listen/bind to DOM events
How to listen/bind to user events

## Environment

* __OS:__ Ubuntu 14.04 LTS
* __language:__ Python 3.4.3
* __application server:__ Flask 0.12.2, Jinja2 2.9.6
* __database:__ mysql Ver 14.14 Distrib 5.7.18
* __python style:__ PEP 8 (v. 1.7.0)
* __web static style:__ [W3C Validator](https://validator.w3.org/)

## Tests

* Test Flask App integration with Storage Engine:

```
$ cat 7-dump.sql | mysql -uroot -p
```

* Test complete integation with files AirBnB HTML: `10-hbnb.py` &
  `100-hbnb.html`. Execute from root directory (`AirBnB_clone`) with all the
  necessary environmental variables to establish the database storage model:

```
$ cat 100-dump.sql | mysql -uroot -p
$ python3 -m web_flask.100-hbnb
```

## License

MIT License
