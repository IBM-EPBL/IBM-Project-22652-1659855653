FROM python:3.8
 
ADD app.py .

 
RUN pip install click colorama flask itsdangerous jinja2 markupsafe werkzeug ibm-db flask bcrypt
 
EXPOSE 5050

CMD ["python","./app.py","127.0.0.1:5050"]