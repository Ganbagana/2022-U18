FROM python:3.7-alpine
WORKDIR app
COPY app.py app.py
COPY requirements.txt requirements.txt 
RUN pip install -r requirements.txt
CMD ["python","app.py"]