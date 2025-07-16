FROM almalinux:9
#CMD ["ping", "google.com"]  #cmd can be overridden
RUN dnf install git -y
RUN useradd Sahith

USER Sahith
CMD [ "google.com" ]
ENTRYPOINT [ "ping" ]