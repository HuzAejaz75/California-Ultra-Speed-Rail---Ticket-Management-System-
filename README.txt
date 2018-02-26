#README.TXT


Shiva Kumar Padma - 011545313 - shivakumar.padma@sjsu.edu
Huzaifa Aejaz - 011490453 - huzaifa.aejaz@sjsu.edu
Sai Ravi Tejabhishek Sreepada - 011169002 Sairavitejabhishek.sreepada@sjsu.edu

URL - 
http://ec2-18-144-67-72.us-west-1.compute.amazonaws.com:3030/main

(Backend URL - 
http://ec2-54-193-54-75.us-west-1.compute.amazonaws.com:9090/train?depStation=A&arrStation=G&type=Regular&depTime=09:00&exactTimeFalg=False&NumofConnections=Any&tripDate=2017-12-21)


Build & Run Instructions - 

Frondend:
1.npm install -g create-react-app
2.cd trainbooking
3.npm install
4.npm start

Backend: 
1.cd Backend/
2.mvn clean install
3.java -jar target/CaliforniaRailTransportSystem-0.0.1-SNAPSHOT.jar




