FROM alpine
LABEL name: carolina

RUN apk add --update \
    python \
    python-dev \
    py-pip \
    build-base \
  && pip install flask

ADD sources /tmp

CMD ["/usr/bin/python","/tmp/greedy.py"]
