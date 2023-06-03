# django-to_do-react

## Open a terminal (in the folder directory) and run the comands: 

pipenv shell

pipenv install django

python backend/manage.py runserver

### Do not close the terminal

## Open another terminal (in the folder directory) and run the comands:

pipenv shell

npx create-react-app frontend

rm frontend/package.json; mv frontends/package.json frontend/package.json

rm frontend/src/index.js; rm frontend/src/App.js

mv frontends/src/index.js frontend/src/index.js;

mv frontends/src/App.js frontend/src/App.js

mv frontends/src/components frontend/src/components

npm install bootstrap@4.6.0 reactstrap@8.9.0 --legacy-peer-deps

cd frontend; npm start

### If you have an error installing bootstrap and reactstrap you must need to run again the following commands:

npm install bootstrap@4.6.0 reactstrap@8.9.0 --legacy-peer-deps

cd frontend; npm start

