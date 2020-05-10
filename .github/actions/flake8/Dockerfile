FROM python:alpine

RUN pip install --upgrade pip
RUN pip install flake8

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
