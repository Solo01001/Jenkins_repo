FROM alpine
RUN yum add --no-cache curl wget busybox-extras netcat-openbsd python2 py-pip
RUN pip install awscli
RUN yum --purge -v del py-pip
CMD tail -f /dev/null
