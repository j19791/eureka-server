# Service Discovery com Eureka
- Os microsserviços não precisam conhecer o endereço IP das outras aplicações, mas apenas o nome que elas se registraram no Eureka.
- (Lista de servicçõs registrados no eureka)[http://localhost:8761/eureka/apps]
- Service registry é um servidor central, onde todos os microsserviços ficam cadastrados (nome e IP/porta)
- Service discovery é um mecanismo de descoberta do IP do microsserviço pelo nome
- Dessa forma, nenhum microsserviço fica acoplado ao outro pelo IP/porta


