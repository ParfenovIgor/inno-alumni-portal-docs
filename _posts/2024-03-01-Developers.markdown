---
layout: post
title:  "For Developers"
---

## Frameworks and Technology
* Python FastAPI
* Next.js
* Docker
* PostgreSQL

## Backend

# How to run using Python
1. Open a shell/command line in project's directory (it is preferable, that it was after activating a python virtual env).
2. Install the needed python packages:
```bash
    pip install -r requirements.txt
```
3. Run the python script:
```bash
    python3 main.py
```

# How to run using docker
1. Open a shell/command line in project's directory.
2. Run the following commands:
```bash
docker build -t alumni-backend
docker run -p 8000:8000 -d alumni-backend
```

Note:
* The image tag name is `alumni-backend` (you can name it as you like).
* The port used by docker is `8000` by default (you can locally map it to anything as you like).


## Frontend

# How to run
1. Open a shell/command line in project's directory.
2. Install all packages (local to the repo) using `npm`:
```bash
npm install
```
3. To build the project for production:
```bash
npm run build
```
4. To start the project on development:
```bash
npm start
```
