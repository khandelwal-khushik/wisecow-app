FROM ubuntu:latest
RUN apt-get update -y
RUN apt-get install fortune-mod cowsay netcat -y
ENV PATH="/usr/games:${PATH}"
WORKDIR /app
COPY wisecow.sh /app
RUN chmod +x wisecow.sh
CMD ["./wisecow.sh"]
EXPOSE 4499
