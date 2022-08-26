# Project Todo App

## Overview

This project aligns with CRUD functionalities, also shows how to model any possible relationship that we can have between models in a relational database and I learned all of the foundational bread and butter tools that is needed to use anytime I want to build out an application that does CRUD no matter what kind of relationships exist between their models. So essentially this is a full-stack web development project.

# The set of concepts I covered in this project include:

* Implementing update functionality: update a todo item's completed state.
* Implementing delete functionality: remove a todo item.
* Model relationships between objects in SQL and SQLAlchemy.
  * Setting up Foreign Key constraints.
* Building CRUD on Lists of To-Do items.
* One-to-one, one-to-many, and many-to-many relationships.

## Development Setup
1. **Download the project starter code locally**
```
git clone https://github.com/muhammedctgr/project-todo-app.git
cd project-todo-app 
```

2. **Create an empty repository in your Github account online.

3. **Initialize and activate a virtualenv using:**
```
python -m virtualenv env
source env/bin/activate
```
>**Note** - In Windows, the `env` does not have a `bin` directory. Therefore, you'd use the analogous command shown below:
```
source env/Scripts/activate
```

4. **Install the dependencies:**
```
pip install -r requirements.txt
```

5. **Run the development server:**
```
export FLASK_APP=myapp
export FLASK_ENV=development # enables debug mode
python3 app.py
```

6. **Verify on the Browser**<br>
Navigate to project homepage [http://127.0.0.1:5000/](http://127.0.0.1:5000/) or [http://localhost:5000](http://localhost:5000) 

