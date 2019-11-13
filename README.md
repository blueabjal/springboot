# springboot
cd springboot/app1
mvn clean install
sudo docker build -t app1:1.0 .
sudo docker run -it -d -p 8081:8080 app1:1.0
cd springboot/app2
mvn clean install
sudo docker build -t app2:1.0 .
sudo docker run -it -d -p 8082:8080 app2:1.0
