FROM python:3.8
LABEL maintainer="Clare Limo"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

# command to run the container
CMD ["python", "app.py"]