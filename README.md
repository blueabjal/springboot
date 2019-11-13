<!DOCTYPE HTML>
<body> 
   <p>#springboot</p>
<p> cd springboot/app1</p>
<p> mvn clean install</p>
<p> sudo docker build -t app1:1.0 .</p>
<p> sudo docker run -it -d -p 8081:8080 app1:1.0</p>
<p> cd springboot/app2</p>
<p> mvn clean install</p>
<p> sudo docker build -t app2:1.0 .</p>
<p> sudo docker run -it -d -p 8082:8080 app2:1.0</p>
</body>

