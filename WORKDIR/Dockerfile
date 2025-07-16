FROM almalinux:9
RUN mkdir /tmp/workdir-demo
#RUN cd /tmp/workdir-demo  ##cd command won't work so we use workdir command
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello I am in the work dir" > hello.txt
CMD [ "slepp", "1000" ]