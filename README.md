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
from app import db
db.create_all()
```

- Start server.

```sh
py app.py
```
- Access

<code><a href="http://127.0.0.1:5000">127.0.0.1:5000</a></code>
