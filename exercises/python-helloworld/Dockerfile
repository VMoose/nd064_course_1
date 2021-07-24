FROM python:3.8
LABEL maintainer="Varun Malik"

COPY . /app
WORKDIR /app
RUN ls
RUN pip install -r requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]