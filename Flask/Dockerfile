FROM python:alpine

COPY requirements.txt .

EXPOSE 5000

RUN pip install -r requirements.txt

COPY . .

ENTRYPOINT ["python3" , "main.py"]

# CMD ['python3','flask.py']