## public projects roadmap

### restaurant management system (backend microservices + restaurant and order management webapp) + kiosk desktop app

#### architecture[the diagram is just for testing]

```mermaid
graph TB
    
    APIGateway[API Gateway]
    RestaurantService[Restaurant Service]
    RestaurantDB[DB]
    PaymentService[Payment Service]
    PaymentDB[DB]
    MessageQueue[Message Queue]

    APIGateway --> RestaurantService
    APIGateway --> PaymentService

    RestaurantService --> RestaurantDB
    PaymentService --> PaymentDB

    RestaurantService --> MessageQueue
    PaymentService --> MessageQueue

```
    
<!-- ### money manager pwa
## digital badge signing and verification platform
## api test automation platform (like postman but nice test visualization and smaller feature set)


🟥 🟧 🟨 🟩 🟦 🟪 🟫 ⬛ ⬜ 

-->
