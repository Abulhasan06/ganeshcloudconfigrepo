# EShoppingZone Cloud Config Repository

Centralized configuration repository for all EShoppingZone microservices.

**GitHub Repository URL:**
https://github.com/Abulhasan06/ganeshcloudconfigrepo.git

## Configuration Files:
- `application.properties` (Shared common properties)
- `api-gateway.properties` (Route definitions)
- `auth-service.properties` (Port 8081, JWT, Database: ecommerceabuldb)
- `profile-service.properties` (Port 8082, Database: ecommerceabuldb)
- `product-service.properties` (Port 8083, Database: ecommerceabuldb)
- `cart-service.properties` (Port 8084, Database: ecommerceabuldb)
- `order-service.properties` (Port 8085, Database: ecommerceabuldb, RabbitMQ)
- `payment-service.properties` (Port 8086, Database: ecommerceabuldb)
- `delivery-service.properties` (Port 8087, Database: ecommerceabuldb)
- `notification-service.properties` (Port 8088, Live Gmail SMTP: abulhasanrathinamohamed@gmail.com, RabbitMQ)
- `wallet-service.properties` (Port 8089, Database: ecommerceabuldb)
- `website-controller.properties` (Port 8090, UI & Gateway client)

## Git Commands to Push to GitHub:
```bash
cd cloud-config-repo
git init
git add .
git commit -m "Update cloud configuration for ecommerceabuldb, live SMTP, and RabbitMQ"
git branch -M main
git remote add origin https://github.com/Abulhasan06/ganeshcloudconfigrepo.git
git push -u origin main --force
```
