# tech_experience

This project is mainly to introduce my technical experience, because the working code is not convenient to upload to the public network, so I used the screenshot and encrypted the API information.


## REST API & Asynchronous service


![main_service_arch](https://user-images.githubusercontent.com/41864925/109452967-d656fd00-7a8b-11eb-9962-d1b8c14f9c42.png)
The figure above shows the project architecture of the whole content moderation team. I am mainly responsible for the API service's development and performance optimization. 


![API_0](https://user-images.githubusercontent.com/41864925/109452874-ab6ca900-7a8b-11eb-9a8a-9d587d4856b0.png)
The entrance of the main audit service


![API_1](https://user-images.githubusercontent.com/41864925/109453099-28981e00-7a8c-11eb-9704-e393d35469e8.png)
The uri config


![API_2](https://user-images.githubusercontent.com/41864925/109453114-3483e000-7a8c-11eb-8ee7-7db6cbdb08b8.png)
The handler layer, for the HTTP request response and processing


![API_3](https://user-images.githubusercontent.com/41864925/109453155-4a91a080-7a8c-11eb-9b74-85415ac8a5bb.png)
The service layer, logic implementation part, interacte with database, message queue and third-party services.




## data-monitoring 
The main purpose of this service is to provide real-time monitoring of main APIs, so as to analyze peak hours and offer warnings, and then optimize the service

![data_monitoring_arch](https://user-images.githubusercontent.com/41864925/109453316-b1af5500-7a8c-11eb-9aaa-95c6ce91f2c1.png)
The architecture of API conditions monitoring.

![main_service_arch](https://user-images.githubusercontent.com/41864925/109453380-df949980-7a8c-11eb-8400-f73aafb66ba1.png)
The data visualization on the Kibana.


