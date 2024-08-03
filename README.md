# transactional-outbox-pattern



## CREATE DOCKER-COMPOSE

# Excecute

``` docker-compose up -d ```

## cURL to access Order Service ##

```
curl -X 'POST' \
  'http://localhost:9191/api/orders' \
  -H 'accept: */*' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Mobile",
  "customerId": "Basant",
  "productType": "Electronics",
  "quantity": 1,
  "price": 89000
}'
```
