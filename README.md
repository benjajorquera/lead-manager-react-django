# Lead Manager

Full stack Django/React/Redux app that uses token based authentication with Knox.

## Quick Start

````
# Install dependencies
npm install
pip install django
pip install pipenv
pipenv shell
pipenv install

# Config database (optional)
python leadmanager/manage.py migrate
python leadmanager/manage.py flush

# Run webpack (from root)
npm run dev

# Serve API on localhost:8000
python leadmanager/manage.py runserver

# Build for production
npm run build
````

## Reference

[Traversy Media](https://www.youtube.com/watch?v=Uyei2iDA4Hs&list=PLillGF-RfqbbRA-CIUxlxkUpbq0IFkX60)
