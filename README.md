# flask-React-emotion
A Flask+React based application that utilizes Haar Cascade model to detect faces and eyes in images received from the webcam

## Technologies Used
- React for the frontend
- Flask for the backend (on run, flask application renders the index.html file in the React Build Folder)
- Heroku for deployement

## Steps to run on a local server
- ```git clone https://github.com/appstimesete/flask-react-emotion.git```
- ```cd flask-react-emotion```
- ```gunicorn --bind localhost:3000 app:app```
