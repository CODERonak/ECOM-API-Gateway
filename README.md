# ECOM API Gateway
The unified entry point and request router for all client traffic.

## Architecture
- **Tech Stack:** Spring Cloud Gateway.
- **Communication:** Routes traffic to microservices; utilizes **OpenFeign** internally for service-to-service orchestration requirements.
- **Deployment:** Google Cloud Run.

## Project Navigation
| Service Name | Primary Database | Data Characteristic | Repository Link |
| --- | --- | --- | --- |
| **User Service** | PostgreSQL (Cloud SQL) | Structured user data | [ECOM-User-Service](https://github.com/CODERonak/ECOM-User-Service) |
| **Product Service** | MongoDB (Cloud Atlas) | Flexible schema | [ECOM-Product-Service](https://github.com/CODERonak/ECOM-Product-Service) |
| **Order Service** | MySQL (Cloud SQL) | Transactional nature | [ECOM-Order-Service](https://github.com/CODERonak/ECOM-Order-Service) |
| **Notification Service** | MongoDB (Cloud Atlas) | Notification history/logs | [ECOM-Notification-Service](https://github.com/CODERonak/ECOM-Notification-Service) |
| **API Gateway** | N/A | Request Routing | [ECOM-API-Gateway](https://github.com/CODERonak/ECOM-API-Gateway) |
