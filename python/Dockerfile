FROM python:3.9
ENV PYTHONUNBUFFERED 1
RUN mkdir /docker_nginx_django_mysql
WORKDIR /docker_nginx_django_mysql
ADD requirements.txt /docker_nginx_django_mysql/
RUN pip install -r requirements.txt
ADD . /docker_nginx_django_mysql/
