# REST

## Abstract
The REST stands for Representational State Transfer. It gives us six Architectural Constraints. First, Client-Server says to make a separation between the client and server to avoid complexity and provide ease of work to both of them. Second, stateless says does not store the session data in the server because it makes the response bulky, and required high bandwidth. Third, cache constraint says during passing the response the cache file is also passed. It will save in the client site or user system that will help the server to work in a fast way because some helping files are already present in the client site. Fourth, Uniform Interface has four-part pass the request in URL formate, pass the response in JSON to some other systematic formate, the request should be self-descriptive it help server to understand the data and HATEOS pass the additional link to the client to explore more. The fifth, layered system says to make things separated in server site to reduce complexity. The sixth, Code on Demand says you can also execute the code on the client site. But this is not recommended.

## The Main Body
### REST
REST stands for Representational State Transfer. Roy Fielding gives this term in 2000. First, let us understand what is REST what does it do? It is an architecture style for designing loosely coupled applications over HTTP. Nowadays, It is used in the development of web servers. REST provides you the high-level guidelines. It gives certain tricks to how things are done and it is up to you how you implement this.
REST defines six architectural constraints that make any web service "a truly RESTful API". If we use this we will be able to make an efficient website.

### Let's Discuss All Six Architectural Constraints:

### Client-Server
The client is something that does request to the server for resources and the server holds the resource that will give in the form of response to the client. This constraint says you should put client and server separately to make loosely coupled. It will give the ease of handling, both evolve independently and will move fast to new versions. If you put both things separated, the server doesn't need to see the UI thing, and as well as the frontend doesn't need to take care of the server.

### Stateless
This states that the server does not store any session data. In the request of resources, there is no data related to the session but on the other hand, the client can store the session data. When the client does request it pass all the data which is needed to the server. Now, the server analyzes the data and passes the resource according to that request. It will increase scalability and visibility. If you will get a single request at a time. It is easy to handle for the server and gives a perfect response.
The drawback of a single request is it reduces network optimization. It required a high bandwidth to hand the big and bulky file.

### Cacheable
It states that when the client sends the request after that server has to send the response. In response, the server has to tell whether the response can be cached or not and for how much duration the response will be cached at the client site. Here the question is what is cache? It is common data that is required to fulfill the basic need of the client and help the website to work properly. So if the client saves cache data. Next time, the response will not carry the same data. so, it will increase your network optimization. It also improves the performance of the application. 
The drawback if the client saves the data in form of a cache. so, anyone can steal the data.

### Uniform Interface
This constraint makes a key difference between the REST API and Non-REST API. It states that pass a single API to send the resource for every platform like mobile, desktop, and other devices.

**The four-element of uniform constraint.**

#### 1. Identification of Resources

Pass the resource in the form of a URL to the server. so, it becomes easy to call the particular function that presents on the server site.

#### 2. Manipulation of The Resource Through Representation

Response representation should be a systematic format like in a JSON format.

#### 3. Self-Descriptive Message for each Response

It means when the server gets the request it should be descriptive so that server can understand and give the perfect response to the client.

#### 4. HATEOS (Hypermedia As The Engine of Application State)

It means you have to send the additional link or a helping hand for the client to explore more.

### Layered System
It states that make things in a hierarchy. So, there will be no rush on the server site. Take an example of the layers system in the MVC model. It has different layers for different purposes. MVC (model view controller) Model handles database, View has which data will pass to the client and Controller handle the request from the client site. In this layered system, each layer does not know about the other layers other than their adjacent layers. The layered system is less complex and more secure.
The drawback is latency means the request has to travel a lot and that makes the website slow.

### Code on Demand
First of all, it is an optional constraint.
It states that the server provides the executable code to the client. The client can handle the code and execute it on the client site. If it happens it causes security issues and it also reduces visibility.


## References
- https://restfulapi.net/
- https://restfulapi.net/rest-architectural-constraints/
- https://www.youtube.com/watch?v=k2AR9hINWLs
- https://www.youtube.com/watch?v=LHJk_ISxHHc
- https://www.youtube.com/watch?v=JYNYv8jJQTE