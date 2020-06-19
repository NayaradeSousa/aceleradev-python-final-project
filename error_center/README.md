### **ERROR CENTER**

Final practical project of Codenation's Python acceleration. 
Error Central: System to centralize application error records.

##### **About the Project**

In modern projects it is increasingly common to use architectures based in 
services or microservices. In these complex environments, errors can arise 
in different layers of the application (backend, frontend, mobile, desktop)
and even in different services. Thus, it is very important that developers
can centralized all errors logs in one place, from where they can monitor 
and make better decisions. In this project, we will implement a system to
centralized application error records.

the project architecture is formed by:

##### **Backend API**

- created endpoint to be used by the application frontend;
- created an endpoint that will be used to write error logs to a relational
database;
- the API must be security, allowing access only with a valid authentication
token.

 ##### **Frontend API (optional)**
 
 - must implement the features presented in the wireframes;
 - must be accessed properly by both desktop and mobile browsers;
 - must consume the product API;
 - developed as a Single Page Application.