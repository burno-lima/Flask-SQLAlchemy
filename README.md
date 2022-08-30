# Flask-SQLAlchemy

![flask](https://user-images.githubusercontent.com/80166382/187505724-2bab9acb-697d-4f96-a2c1-39d9f43723b5.png)


Installation

- First clone the project.

```sh
git clone https://github.com/burno-lima/Flask-SQLAlchemy.git
```

- Create venv and activate.

```sh
python -m venv .venv
```
```sh
.venv\Scripts\activate
```
- Install dependency for project.

```sh
pip install -r requirements.txt
```

- Create data base, need to open python in terminal.

```sh
Python 3.8.3 (tags/v3.8.3:6f8c832, May 13 2020, 22:37:02) [MSC v.1924 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> from app import db
>>> db.create_all()
>>> exit()
```

- Start server.

```sh
py app.py
```
- Access

<code><a href="http://127.0.0.1:5000">127.0.0.1:5000</a></code>
