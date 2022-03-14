# Rest-API-Architecture-Basics

### Representational state transfer

### It is an architectural style that has some constraints and allows us to interact with services. The features are as follows ->

    - Client-Server Architecture
    - Cacheabled
    - Layered
    - Stateless
    - Uniform Interface
    - Code on demand

- Client-Server-Architecture - This means there will  be a client (consumer) and a provider 
                               whenever we will be using Restful services.

- Cacheable - This mentions whether the response received from the server is cacheable or not, if 
              it is , the the client can reuse it without again making call to the service api.

- Layered -   This means the data which the client is asking maybe coming from different layers , 
              i.e each layer only knows about the immediate layer from where the data is coming. 

- Stateless - It means the client and server won't be saving any state of the data received from
              each other. All the necessary data needed to call the endpoint must be sent during the call only.      

- Code-On-Demand - It is a optional thing for Rest services. According to this, servers can also  
                 provide executable code to the client                                                                    