# maven commands

#Clean previous builds
mvn clean

#Compile the project
mvn compile

#Package the project into a JAR with dependencies
mvn package

#Run the project
java -jar target/BlogWebsite-1.0-SNAPSHOT-jar-with-dependencies.jar


# git commands
git init

git add .

git commit -m "Initial commit"

git branch -M main

git remote add origin https://github.com/ShreyaJadhav9700/maven.git

git pull origin main --allow-unrelated-histories

git push -u origin main


# Docker 

Dockerfile

FROM nginx:latest
COPY . /usr/share/nginx/html



cmd copy

docker build -t travel-website:latest .


optional

git clone https://github.com/<your-username>/travel-website.git
cd travel-website
docker build -t travel-website:latest .


cmd

docker run -d -p 8080:80 --name travel-container travel-website:latest


localhot8080 
go to this website

