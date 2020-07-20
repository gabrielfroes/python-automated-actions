# Python Automated Actions

This project is a simple script that creates folder and download files from internet according to a JSON file.

The main goal is simplify the creation of projects for: video makers, developers, designers, photographers or any kind of professional that need automated some things.

The most simple project creation ever! :p

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them.

```
Python 3.x
```

### Installing

A step by step series of examples that tell you how to get a development env running

Install Python 3.x with pip

Install Path Validate, a Python Library for file validation.

```
pip install pathvalidate
```

Install PyInstaller, to generate .exe file (for Windows).

```
pip install pyinstaller
```

Run a Live Server or any http service or port 5500. This is optional, you can also customize the *actions-sample.json* and *config.ini* with your own URLs.

## Running the tests

### Linux, Mac OS X, BSD and most OSes except Windows
Turn script executable:

```
chmod +x actions.py
```

Call script inside a folder with photos:

```
./actions.py .
```

### Windows

To run a test, call the script inside a folder with photos.

```
python actions.py .
```

**For Windows in Context Menu:**

1. To generate *actions.exe* file to run on Windows.

```
pyinstaller -c -F ----icon=app.ico actions.py
```

2. Add the keys on Registry or run *actions.reg*.
3. Copy .exe file on *C:\Program Files\CDFTV Actions*
4. Add *C:\Program Files\CDFTV Actions* in the *Path* on Windows Environment Variable.

## Contributing

Feel free to submitting pull requests to us.

## Authors

* **Gabriel Froes** - *Initial work* - [Twitter](https://www.twitter.com/gabrielfroes)
* **Vanessa Weber** - *Initial work* - [Twitter](https://www.twitter.com/nessaweberfroes)

## License

This project is licensed under the [GNU General Public License](https://opensource.org/licenses/GPL-3.0).

## Acknowledgments

* First steps in Python language
* Create simple and useful things
* Produce a [video lesson](https://youtu.be/eosclmulqqo) coding this little project
* Build code for [Código Fonte TV](https://www.youtube.com/codigofontetv), our Youtube Channel.
