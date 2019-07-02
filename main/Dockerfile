ARG TAG=stretch
FROM balenalib/raspberrypi3-debian:$TAG

RUN echo "hi there testing cache"

RUN echo "tag is $TAG"

COPY . /usr/src/app/

RUN ls -l /usr/src/app/

CMD while true; do echo hi; sleep 3600; done
