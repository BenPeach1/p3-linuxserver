# Project 3: Linux Server Configuration & Web Application Deployment

For this project, an Ubuntu Linux server has been established using Amazon Web
Services - Lightsail. The server has been configured with a 'grader' login which
has been given sudo access. Furthermore, the server has been locked down
(see details below).


### _Public IP Address:_
```34.237.143.85```

### _Web Application URL:_
```http://34.237.143.85.xip.io```

### _Installed Software:_
- _Apache2_
- _mod_wsgi_
- _PostgreSQL_

### _Third-Party Resources:_
- __Flask__ (Flask, render_template, request, redirect, jsonify, url_for, flash,
  make_response, session)
- __SQLAlchemy__ (create_engine, asc, func, sessionmaker)
- __Flask_WTF__ (Form, StringField, TextField, TextAreaField, InputRequired)
- __Functools__ (wraps)
- __DateTime__

### _Server Configuration Summary_
- 'grader' login created & given sudo access
- root login disabled
- Firewall configured to only allow for SSH, HTTP, and NTP
- RSA keys required for login
- All applications are up-to-date
- SSH hosted on non-default port
- Apache web server is configured to serve the catalog application (Woodworking
  Project Forum)
- Database server configured with necessary users and security to serve data
