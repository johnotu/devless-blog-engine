FROM ubuntu:latest
MAINTAINER John Otu "johnne01@gmail.com"
RUN apt-get -y update
RUN apt-get install -y python-pip python-dev build-essential
COPY . /blog
WORKDIR /blog
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["blog.py"]
