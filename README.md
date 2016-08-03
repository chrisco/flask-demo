# Flask Tutorial

1. Setup virtualev as per this guide: http://flask.pocoo.org/docs/0.11/installation
2. Follow this Flask tutorial: http://flask.pocoo.org/docs/0.11/tutorial/

After these commands:
```
$ sudo easy_install virtualenv
$ mkdir flask-demo
$ cd flask-demo/
$ virtualenv venv
$ . venv/bin/activate
$ pip install Flask
$ cd flaskr/
$ mkdir static
$ mkdir templates
$ touch README.md
```
This is what we have:
```
Foo~/G25/w16/flask-demo
$ tree -L 2
.
├── flaskr
│   ├── README.md
│   ├── static
│   └── templates
└── venv
    ├── bin
    ├── include
    ├── lib
    └── pip-selfcheck.json

7 directories, 2 files
(venv)
```
To deactivate virtualenv:
```
$ deactivate
```
