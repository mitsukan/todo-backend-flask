#todo-backend-flask
[![Circle CI](https://circleci.com/gh/Faerbit/todo-backend-flask.svg?style=shield)](https://circleci.com/gh/Faerbit/todo-backend-flask)
[![Requirements Status](https://requires.io/github/Faerbit/todo-backend-flask/requirements.svg?branch=master)](https://requires.io/github/Faerbit/todo-backend-flask/requirements/?branch=master)

A [todo backend](http://todobackend.com) written in Python with Flask.

##Tests
You can run the unit tests with `python -m unittest discover`.

##Server
You can start a debug server by executing `run_debug_server.py`

## License
Licensed under the MIT License.
See License.md for further details.


Note: For the Psycopg2 installation, I've changed the version to 2.7.1.
On top of this, to install, open ssl needs to be installed via `brew install openssl`
Then install psycopg2 linking to the installation path that brew installed it: `env LDFLAGS="-I/usr/local/opt/openssl/include -L/usr/local/opt/openssl/lib" pip install psycopg2`