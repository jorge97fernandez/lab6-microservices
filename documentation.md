## 1. The two microservices are running and registered

![AccountRegistration](imgs/accountregistration_1.png)
![WebRegistration](imgs/webservice_registration.png)

## 2. The service registration service has the two microservices registered

![RegistrationDashboard](imgs/registered_services_1.png)

## 3. A second account microservice is running in the port 4444 and it is registered

![NewAccountRegistration](imgs/accountregistration_2.png)

## 4. Killing the microservice with port 2222

After kill the account microservice with port 2222, the account microservice on port
4444 is still alive, so because of replication, data is still accesible
![AccountInfo](imgs/accountstillalive.png)
