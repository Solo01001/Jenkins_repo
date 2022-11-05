FROM alpine
RUN yum install --no-cache curl wget busybox-extras netcat-openbsd python2 py-pip
RUN pip install awscli
RUN yum remove -v del py-pip
CMD tail -f /dev/null
