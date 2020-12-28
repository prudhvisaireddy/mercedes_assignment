# mercedes_assignment

description: it consists of 2 micfroservices and a eureka servermicroservices which are communicating with each other .When sending service is up loaded URL on webpage will wait for service to respond (i.e., true/false) . If we get true as response then sending service will send request(with city name) to  the other service . Then the second microservice is sending back the petrol price . Then again the first Microservice will perform business logic and provide the required output that is the bill amount and time required to fill the tank as per the city.

HOW to RUN
--------------------
run the following in the given order
1)eureka server
2)PetrolPriceAPIService
3)SendingService




