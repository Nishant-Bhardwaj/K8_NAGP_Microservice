### It Make use of Images pushed to Docker Hub Registry.

### Commands to apply (create Deployment and Service): 

* kubectl apply -f k8_eureka_server_nishant_nagp.yml

* kubectl apply -f k8_api_gateway_nishant_nagp.yml

* kubectl apply -f k8_consumer-service-nishant-nagp.yml

* kubectl apply -f k8_flight-supplier-service-nishant-nagp.yml

* kubectl apply -f k8_hotel_supplier_service_nishant_nagp.yml

### In K8s, the correct option for calling another service is usually not through the 'CONTAINER NAME' or 'localhost'.

### Instead, applications with-in a Kubernetes cluster typically communicate with each other using 'Kubernetes Service Name'.


### Delete Deployment and Services created appove:

* kubectl delete -f k8_eureka_server_nishant_nagp.yml
* kubectl delete -f k8_api_gateway_nishant_nagp.yml
* kubectl delete -f k8_consumer-service-nishant-nagp.yml
* kubectl delete -f k8_flight-supplier-service-nishant-nagp.yml
* kubectl delete -f k8_hotel_supplier_service_nishant_nagp.yml