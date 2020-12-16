# Flask-Demo

This basic Flask app was created during the Monday workshop, _Intro to Web Programming_.
This is a simple web page to make a meme about my friend Bryan Yakimisky.

## Usage

Ensure that `python3` is installed.

Clone the repository and set up a new virutal environment.
```
cd flask-demo/
python3 -m venv venv
```

Activate the virtual environment. For macOS/Linux:
```
. venv/bin/activate
```

For Windows:
```
. venv\Scripts\activate
```

Install Flask and its dependencies.
```
pip install -r requirements.txt
```

Run the server.
```
export FLASK_ENV=dev
flask run
```

## License

Licensed under the [MIT License](LICENSE).
