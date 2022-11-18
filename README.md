# loadbalancing-demo

#### Build:
`mvn clean install`

#### Running:
`java -jar -Dserver.port=8060 target/loadbalancing-demo-0.0.1-SNAPSHOT.jar`

#### Package and run:
This will build also  
`mvn package && java -jar -Dserver.port=8090 target/loadbalancing-demo-0.0.1-SNAPSHOT.jar`



##Core Load Balanching theory = https://youtu.be/37sdnojPHOs?list=PL564gOx0bCLqLVWPkSqC2eIkprh0EC7AF
##Live demo link = https://youtu.be/oJe2x49YeBY




#INFO We can also use the HAproxy service as a api gateway to routing diffrent service by call one service.
HAProxy routing demo URL = https://www.baeldung.com/devops/haproxy-api-gateway

