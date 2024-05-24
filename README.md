# Flask-Inputs
![Project Status](https://img.shields.io/badge/status-active-green)
![Project Status](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11-blue)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE.md)


## Introduction
WTForms is awesome for validating POST data. What about other request data?

The __Flask-Inputs__ extension adds support for WTForms to validate request data from args to headers to json.


## Installation
To install Flask-Inputs, simply:

```bash
$ pip install Flask-Inputs
```

- JSON validation requires the optional [jsonschema](https://pypi.python.org/pypi/jsonschema) package
- e-mail validation requires [email_validator](https://pypi.python.org/pypi/email_validator) package

```bash
$ pip install Flask-Inputs jsonschema email_validator
```


## Contributing
```bash
make clean install test build
```


## Documentation
Documentation is available at [http://pythonhosted.org/Flask-Inputs](http://pythonhosted.org/Flask-Inputs)


## License
[MIT](./LICENSE.md)
