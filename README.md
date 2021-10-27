# Python_Ass3

- Assignment 3


- Installation
    pip install jupyter
    pip install pandas

- Usage
    from datetime import datetime, timedelta
    from flask import Flask
    from flask.helpers import make_response
    from flask import request
    from flask.json import jsonify
    import jwt
    
- Examples
     * Serving Flask app 'web_server' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 277-743-101
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
127.0.0.1 - - [27/Oct/2021 22:31:59] "GET / HTTP/1.1" 404 -
127.0.0.1 - - [27/Oct/2021 22:31:59] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [27/Oct/2021 22:32:04] "GET /login HTTP/1.1" 401 -
127.0.0.1 - - [27/Oct/2021 22:32:31] "GET /login HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2021 22:32:47] "GET /protected HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2021 22:33:01] "GET /protected?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyIjoicXdlcnR5IiwiZXhwIjoxNjM1MzU0MTUxfQ.YybJHKrwy_7WRTPfGzHDP9aTM2tLEatsVawptP2KkNU HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2021 22:33:28] "GET /protected?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyIjoicXdlcnRfaragandonDP9aTM2tLEatsVawptP2KkNU HTTP/1.1" 200 -
 * Detected change in 'd:\\Downloads(папка D)\\web_server.py', reloading
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 277-743-101
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
