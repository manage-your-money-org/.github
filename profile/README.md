# ManageYourMoney

#### This org containes all the repositories related to ManageYourMoney Application.

## Repositories
#### Backend
  - Backend is developed using spring framework using soring boot.
  - Backend is based on microservice architecure.
  - Backend contains below microservices.
    - [mym-config-server](https://github.com/manage-your-money-org/mym-config-server)
    - [mym-discovery-server](https://github.com/manage-your-money-org/mym-discovery-server)
    - [mym-api-gateway](https://github.com/manage-your-money-org/mym-api-gateway)
    - [mym-user-authentication-service](https://github.com/manage-your-money-org/mym-user-authentication-service)
    - [mym-email-and-notification-service](https://github.com/manage-your-money-org/mym-email-and-notification-service)
    - [mym-expense-category-service](https://github.com/manage-your-money-org/mym-expense-category-service)
    - [mym-expense-service](https://github.com/manage-your-money-org/mym-expense-service)
   
#### Frontend
- Frontend is developed using Angular
  - [manage-your-money-frontend](https://github.com/manage-your-money-org/manage-your-money-frontend)

---

## Containerization
**Docker** is used for containerization.
- [mym-docker-and-kubernetes-configs](https://github.com/manage-your-money-org/mym-docker-and-kubernetes-configs)
- *docker-compose* contains the definition for managing the docker applications.

## Message-Broker
**RabbitMQ** is used as a message broker for the asynchronous communication between the microservices.
