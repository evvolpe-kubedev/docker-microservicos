FROM python:3.8-slim-buster
WORKDIR /app
COPY requirements.txt /app
RUN python -m pip install -r requirements.txt
COPY . .
EXPOSE 5000
CMD ["gunicorn", "--workers=3", "--bind", "0.0.0.0:5000", "app:app"]

#FROM python:3.8.12-buster
#EXPOSE 5000
#WORKDIR /app
#COPY requirements.txt .
#RUN pip install -r requirements.txt
#COPY . .
#ENTRYPOINT [ "python", "app.py" ]