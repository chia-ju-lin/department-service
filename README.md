# department-service

This repo is used to learn microservice together with other modules
* service-registry 
* department-service (in the UserService use DEPARTMENT-SERVICE in the URL)
* user-service
* api-gateway
* circuit breaker
* cloud-config-server
* zipkin/sleuth dependency
* zipkin server: tracing log betweeen microservices https://zipkin.io/pages/quickstart.html

### Video: https://www.youtube.com/watch?v=BnknNTN8icw

## Two methods:
*  POST http://localhost:9001/departments/
> {"departmentName":"IT",
>  "departmentAddress":"3rd Cross, First Street",
>  "departmentCode":"IT-003"
> }

*  Get http://localhost:9001/departments/1
