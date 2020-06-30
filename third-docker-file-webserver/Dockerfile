FROM ubuntu
RUN apt-get update && apt-get install -y python3

COPY ./server.py /
EXPOSE 8888

CMD ["/server.py"]
