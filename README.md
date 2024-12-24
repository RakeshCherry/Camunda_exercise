# Camunda_exercise
Camunda Assignment

below are the details of a brief camunda exercise to be completed

1. Create a Spring Boot and camunda based microservice
2 Use any compatible SQL DB
3. Create a rest api/order/process which will validate the request and start a bpmn process
4. create a custom validator to valid incoming request
5. Request fields: item id, customer details obj (pincode, mobilenumber, name, customerType), noOfItems
6. Create DB tables to save/update order details, save/update inventory (itemId, itemName, itemType, pricePerUnit, inventoryBalance)
7. DMN to deduce shipment type. Rules are:
   a) VIP Customer ? - Express
   b) Order price > 50000 - Express
   c) If item is electronics - Express
   d) Rest all cases - normal

![Camunda Exercise](https://github.com/user-attachments/assets/2806a9a9-e728-497f-914a-d36cbbd59b0b)
