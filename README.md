**Lesson:** Backend Course
**Description**
In this course, you will learn step-by-step how to design, develop and deploy a backend web service from scratch. I believe the best way to learn programming is to build a real application. Therefore, throughout the course, you will learn how to build a backend web service for a simple bank. It will provide APIs for the frontend to do the following things:

- Create and manage bank accounts.
- Record all balance changes to each of the accounts.
- Perform a money transfer between 2 accounts.

The programming language we will use to develop the service is Golang, but the course is not just about coding in Go. You will learn a lot of different topics regarding backend web development. They are presented in 6 sections:

1. In the 1st section, you will learn deeply about how to design the database, generate codes to talk to the DB in a consistent and reliable way using transactions, understand the DB isolation levels, and how to use it correctly in production. Besides the database, you will also learn how to use docker for local development, how to use Git to manage your codes, and how to use GitHub Action to run unit tests automatically.

2. In the 2nd section, you will learn how to build a set of RESTful HTTP APIs using Gin - one of the most popular Golang frameworks for building web services. This includes everything from loading app configs, mocking DB for more robust unit tests, handling errors, authenticating users, and securing the APIs with JWT and PASETO access tokens. 

3. In the 3rd section, you will learn how to build your app with Docker and deploy it to a production Kubernetes cluster on AWS. The lectures are very detailed with a step-by-step guide, from how to build a minimal docker image, set up a free-tier AWS account, create a production database, store and retrieve production secrets, create a Kubernetes cluster with EKS, use GitHub Action to automatically build and deploy the image to the EKS cluster, buy a domain name and route the traffics to the service, secure the connection with HTTPS and auto-renew TLS certificate from Let's Encrypt.

4. In the 4th section, we will discuss several advanced backend topics such as managing user sessions, building gRPC APIs, using gRPC gateway to serve both gRPC and HTTP requests at the same time, embedding Swagger documentation as part of the backend service, partially updating a record using optional parameters, and writing structured logger HTTP middlewares and gRPC interceptors.

5. Then the 5th section will introduce you to asynchronous processing in Golang using background workers and Redis as its message queue. We'll also learn how to create and send emails to users via Gmail SMTP server. Along the way, we'll learn more about writing unit tests for our gRPC services that might involve mocking multiple dependencies at once.

6. The final section 6th concludes the course with lectures about how to improve the stability and security of the server. We'll keep updating dependency packages to the latest version, use Cookies to make the refresh token more secure, and learn how to gracefully shut down the server to protect the processing resources. As this part is still a work in progress, we will keep making and uploading new videos about new topics in the future. So please come back here to check them out from time to time.

This course is designed with a lot of details, so that everyone, even those with very little programming experience can understand and do it by themselves. I firmly believe that after the course, you will be able to work much more confidently and effectively on your projects.

*Instructor*
**TECH SCHOOL**

*Conclusion:*
**What I'll learn**
- Design database schema using DBML and automatically generate SQL code from it
- Deeply understand the DB isolation levels, transactions and how to avoid deadlock
- Automatically generate Golang code to interact with the database
- Develop a RESTful backend web service using the Gin framework
- Secure the APIs with user authentication, JWT and PASETO
- Write stronger test set with high coverage using interfaces and mocking
- Build a minimal Docker image for deployment and use Docker-compose for development
- Set up Github Action to automatically build and deploy the app to AWS Kubernetes cluster
- Register a domain and config Kubernetes ingress to route traffic to the web service
- Enable automatic issue & renew TLS certificate for the domain with Let's Encrypt
- Take your web service to the next level with gRPC and gRPC gateway
- Run background workers to process tasks asynchronously with Redis and Asynq

"COMPARATION BETWEEN SQLs"
![Alt text](/document/comparation_sql.png)
