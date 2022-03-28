FROM ubuntu:20.04
RUN apt update && apt install -y pip 
WORKDIR /var/www/html
COPY ["index.html","."]
RUN echo "Hello, <strong>Docker</strong>" > index2.html
CMD ["python3","-u","-m","http.server"]