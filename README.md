## ✨ `React` Autohoster Dashboard

- `M-UI` based design
- Modern aesthetics UI design - Designed by *[CodedThemes](https://bit.ly/37fF9RT)*
- React, Redux, Redux-persist

<br />

> `Tests` (compatibility matrix using Ubuntu 18 LTS as reference)

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ✅ | ✅ |
| `v16.0.0` | ✅ | ✅ | 
| `v18.0.0` | ❌ | ❌ | 


<br />

## ✨ `Flask API` Features

- Stack: `Flask` / `Flask-RestX` / **SQLite** 
- **DB Layer**: `SqlAlchemyORM`, `SQLite` persistence
- **Auth**: JWT tokens managed via `Flask-jwt_extended`
- [API Definition](https://docs.twinstar.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server


<br /> 

## ✨ How to use it


- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `frontend`. 

```bash
$ cd frontend
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).

<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `backend`

```bash
$ cd backend
```

<br >

> **Step 2** - Install dependencies using a `virtual environment`

```bash
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ pip install -r requirements.txt
```

<br />

> **Step 3** - Setup the `Flask` environment 

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
// OR 
$ (Windows CMD) set FLASK_APP=run.py
$ (Windows CMD) set FLASK_ENV=development
// OR
$ (Powershell) $env:FLASK_APP = ".\run.py"
$ (Powershell) $env:FLASK_ENV = "development"
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ flask run
```

Use the API via `POSTMAN` or `Swagger Dashboard` at `localhost:5000`.

<br /> 

### 👉 Start API using `Docker` 

> **Step 1** - Change the directory to `backend`

```bash
$ cd backend
```

<br />

> **Step 2** - Start API using `docker-compose` command 

```bash
$ docker-compose up --build
```

<br />

## 👉 Codebase Structure

```bash
< ROOT  >
    |
   backend/
    ├── api
    │   ├── config.py
    │   ├── __init__.py
    │   ├── models.py
    │   └── routes.py
    ├── requirements.txt
    ├── run.py
    └── tests.py
```

<br />
