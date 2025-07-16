FROM almalinux:9
#CMD ["ping", "google.com"]  #cmd can be overridden
RUN dnf install git -y
RUN useradd sahith

USER sahith
CMD [ "google.com" ]
ENTRYPOINT [ "ping" ]