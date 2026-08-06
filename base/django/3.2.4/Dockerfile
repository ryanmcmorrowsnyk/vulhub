FROM python:3.15.0rc1

ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh /usr/local/bin/wait-for-it.sh

RUN set -ex \
    && pip install -U pip \
    && pip install "django==3.2.4" "mysqlclient==2.0.2" \
    && chmod +x /usr/local/bin/wait-for-it.sh
