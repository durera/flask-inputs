# flask-inputs2
![Project Status](https://img.shields.io/badge/status-active-green)
![Project Status](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11-blue)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE.md)


## Introduction
WTForms is awesome for validating POST data. What about other request data?

The __flask-inputs2__ extension adds support for WTForms to validate request data from args to headers to json.

The [Flask-Inputs](https://github.com/nathancahill/flask-inputs) project is no longer maintained, and has not been for many years.  This project exists to provide a drop-in replacement for Flask-Inputs ensuring support for modern Python releases.


## Installation
To install flask-inputs2, simply:

```bash
$ pip install flask-inputs2
```

- JSON validation requires the optional [jsonschema](https://pypi.python.org/pypi/jsonschema) package
- e-mail validation requires [email_validator](https://pypi.python.org/pypi/email_validator) package

```bash
$ pip install flask-inputs2 jsonschema email_validator
```


## Contributing
```bash
make clean install test build
```


## Documentation
Original documentation for [Flask-Inputs](https://pypi.python.org/pypi/Flask-Inputs) is available at [http://pythonhosted.org/Flask-Inputs](http://pythonhosted.org/Flask-Inputs), there is no functional change in flask-inputs2.


## License
[MIT](./LICENSE.md)
