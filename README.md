# Portfolio-project-1
Launch a python 3 tier web application using flask

**Presentation tier:** 
  Nginx web server acts as the presentation tier, which serves as a reverse proxy for the Flask application.
  
**Application tier:** 
  The Flask application running on uWSGI server acts as the application tier, which processes the user requests and generates responses.
  
**Data tier:** 
  SQLite database acts as the data tier, which stores the data used by the application.
