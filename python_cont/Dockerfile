# version of python
FROM python:3-alpine3.15 

# working directory
WORKDIR /app

# copy all files to that working directory
COPY . /app 

# installaing packages
RUN pip install -r requirements.txt

# Exposing port
EXPOSE 3000

# Firing up command
CMD python ./index.py

# To create image run - docker build -t  msagr/hey-python-flask:0.0.1.RELEASE .
# To create container - docker container run -d -p 4000:3000 msagr/hey-python-flask:0.0.1.RELEASE
# To push to docker repo.(registry of an image) - docker push msagr/hey-python-flask:0.0.1.RELEASE