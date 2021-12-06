FROM ubuntu:bionic
 
RUN apt-get update && apt-get install -y python3.6 --no-install-recommends
RUN apt-get install -y python-pip;pip install Flask;export FLASK_APP=hello
COPY . /app
WORKDIR /app
#COPY hello.py .
CMD ["/usr/bin/python", "hello.py"]
#CMD ["flask run hello.py"]
