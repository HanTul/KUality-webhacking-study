FROM python:3.12.0
COPY . /app
WORKDIR /app
RUN pip3 install flask flask-wtf flask-migrate email_validator
RUN python -m pip install --upgrade pip

ENV FLASK_APP=pybo
ENV FLASK_ENV=__init__.py

CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]