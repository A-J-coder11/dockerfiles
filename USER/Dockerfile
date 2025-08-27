FROM amazonlinux:9
# CMD ["ping", "google.com"]
RUN dnf install git -y
RUN useradd anand

USER anand
CMD ["google.com"]
ENTRYPOINT [ "ping" ]