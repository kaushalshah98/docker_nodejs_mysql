# getting started with docker-mysql-nodejs

Running a nodejs application with mysql database using docker and microservice architecture

1. mysql image build :- `docker build -t docker-mysql .`
2. nodejs image build :- `docker build -t docker-nodejs .`
3. run mysql :- `docker run -d -p 3306:3306 docker-mysql`
4. run nodejs:- `docker run -t -p 4000:4000 docker-nodejs`