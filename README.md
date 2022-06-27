# React Horizon Ui `full-stack`

Full-Stack Seed project generated by **[React App Generator](https://appseed.us/generator/react/)** top of *Horizon Ui* design. The backend logic is provided by a simple, `easy-to-extend` API Server that manages the Authentication flow (login, registration, logout) using `JSON Web Tokens` (JWT).

<br />

> 🚀 Build Timestamp `2022-06-27 12:35`

- **React Frontend**: `Horizon UI` (open-source)
  - Design crafted by *[Simmmple](https://simmmple.com/)*
  - Styled with `Chakra UI`
  - `Dark-Mode`, `RTL` Support
  - `UI Kit`: 70+ components, `8 Sample Pages`, `3 Customized Plugins`   

- **API Backend Server**: `Flask` / `Flask-RestX` / **SQLite** 
  - `Up-to-date dependencies`
  - **DB Layer**: `SqlAlchemyORM`, `SQLite` persistence
  - **Auth**: JWT tokens managed via `Flask-jwt_extended`
  - [API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server


<br />

> Links

- 👉 [React Horizon UI](https://react-horizon-ui-chakra.appseed-srv1.com/#/auth/sign-in/default) - LIVE Demo (from a similar product)

- 👉 **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`
- ✅ [PRO Version Available](#pro-version) - `enhanced UI` and more `features`

<br />

![React Horizon UI - Full-Stack starter provided by AppSeed and Simmmple.](https://user-images.githubusercontent.com/51070104/174428337-181e6dea-0ad9-4fe1-a35f-25e5fa656a9d.png)

<br >

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
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

> **Step 1** - Change the directory to `api-server-flask`

```bash
$ cd api-server-flask
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
$
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

## 👉 Codebase Structure

```bash
< ROOT  >
    |
   api-server-flask/
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



<br />

## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Designed for those who like modern UI elements and beautiful websites, Horizon UI is ready to help you create stunning websites and webapps.
This premium design powered by `Chakra UI` comes with many examples for pages like NFTs Pages, Authentication Pages, Profile and so on. 

- 👉 [React Horizon UI PRO](https://appseed.us/product/horizon-ui-pro/full-stack/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![React Horizon UI PRO - Full-Stack starter provided by AppSeed and Simmmple.](https://user-images.githubusercontent.com/51070104/175255148-7475cb47-0f63-48ee-a39d-7620beca6783.png)

<br />

---
**React Horizon Ui** - Full-Stack Seed project generated by **[App Generator](https://appseed.us/generator/)**.
