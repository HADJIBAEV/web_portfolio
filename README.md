# web_portfolio

## Author

Aziz Mavlyanov

## Stack

HTML, CSS, JavaScript, Python, Flask, Travis CI

## Installation and usage of the project locally

**Please make sure that you have python, pip installed on your PC (Notebook)**

1\) Clone the project

```dotenv
git clone git@github.com:azizMavlyanov/web_portfolio.git
```


2\) Create virtual env
```dotenv
python3 -m venv myenv
```

3\) Activate virtual environment

```dotenv
source venv/bin/activate
```

4\) Install all dependencies:

```dotenv
pip install -r requirements.txt
```

5\) Set flask environment variables


```dotenv
export FLASK_APP=app.py
export FLASK_ENV=development
```

6\) Run the project


```dotenv
flask run
```

7\) Visit http://localhost:5000/ and start using the app
