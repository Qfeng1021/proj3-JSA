FROM python:3
MAINTAINER Qianyi Feng "noemail@website.domain"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
COPY . /flask_vocab.py
WORKDIR /flask_vocab.py
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
