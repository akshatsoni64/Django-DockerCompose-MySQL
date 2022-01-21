FROM python:3.9

RUN mkdir project
WORKDIR /project
ADD . .

RUN apt update && apt install netcat -y

RUN pip install -r ./requirements.txt
EXPOSE 8080
