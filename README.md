# REST-Architecture
## What is called an API?
- **API** stands for **A**pplication **P**rogramming **I**nterface. 
- In general, an **API** is a set of programming code that enables data transmission between one software product and another.

![API](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQDzT7su1ZcjFDC24OQ3aEDv2Noh6_SZhsJug&usqp=CAU)

Click [here](https://en.wikipedia.org/wiki/API) for more about an **API**.


## What is REST?
- Let us assume that zomato food delivery app, the client searched if the particular food is available or not.
- The client's request, send to the zomato's database via an API.
- If the particular food is present or not the output resource sent to the REST API in the form of web page.
- The REST sent the information in the form of JSON,XML,HTML, etc,.
- Following diagram explains better to you.

![REST](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGWU2E5TqHwcSnaL1SKk4eYSz4SqU8ZUfTtg&usqp=CAU)

## REST Definition ?
- **REST** stands for **R**epresentational **S**tate **T**ransfer.
- **REST** is a software architectural style as well as an approach for communication purpose that is often used in various web services development.
- The goal of **REST** is to increase performance, scalability, simplicity, modifiability, visibility, portability, and reliability.
- These goals are achieved through following **REST** principles.
### REST Principles :
- **Client–server architecture**
  + Separating the user interface concerns from the data storage concerns improves the portability of the user interfaces across multiple platforms.
- **Statelessness**
  + It makes them ideal in high volume applications, increasing performance by removing server load caused by retention of session information.
- **Cacheability**
  + Well-managed caching partially or completely eliminates some client–server interactions, further improving scalability and performance.
- **Layered system**
  + Adding security as a separate layer enforces security policies.
- **Code on demand**
  + Servers can temporarily extend or customize the functionality of a client by transferring executable code.
- **Uniform interface**
  + It simplifies and decouples the architecture, which enables each part to evolve independently.
  + The four constraints for this uniform interface are :
    * Resource identification in requests
    * Resource manipulation through representations
    * Self-descriptive messages
    * Hypermedia as the engine of application state (HATEOAS)
