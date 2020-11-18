FROM python:3.8-alpine

RUN mkdir /app
WORKDIR /app
COPY my_flask_app.py /app/

RUN pip install flask
RUN pip install flask_cors

EXPOSE 5000
CMD ["python", "/app/my_flask_app.py"]