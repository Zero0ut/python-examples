### Install Dependencies

```
pip3 install -r requirements.txt
```

### Initalise Database and Schema

```
python
>>>> from app import db
>>>> db.create_all()
>>>> exit()
```

### Start development server

```
python app.py
```

### Endpoint

```
The API is now running at http://127.0.0.1:5000/api/users
```

### Reference

```
https://towardsdatascience.com/develop-database-driven-rest-api-with-python-in-10-minutes-9b8cbb7ce5b2
```
