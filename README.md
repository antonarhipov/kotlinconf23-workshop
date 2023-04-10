# KotlinConf 2023: Building Scalable Microservices With Ktor and Kafka

Writing a single RESTful service is easy, but creating a scalable design is hard. Developers building their first distributed apps in the cloud are often puzzled by the choice of available frameworks and the variety of design options for the system architecture.

This workshop will use Kotlin programming language, the Ktor services framework, and Kafka for event streaming to build a feature-complete backend application. We’ll start with the basics by exploring the Ktor framework and learning how to build a simple web application using obligatory functions. We’ll cover topics like handling HTTP requests, working with WebSockets, database access, authentication and authorization, logging, and more. We will also explore the plugin API and write a simple plugin for our web application.

Once you’re comfortable with Ktor, we will model a distributed system where the actors communicate asynchronously. What are the requirements for such a system? Messaging, long-term storage, and real-time stream processing immediately come to mind. This is where Apache Kafka comes in. Kafka will help make the system truly asynchronous, distributed, and resilient.
By the end of the workshop, you will know:

* How to create and deploy resilient RESTful services using Ktor.
* How to integrate Ktor with external libraries that require additional configuration.
* How to flexibly connect services using various tools, such as Kafka streams.

This will be a fast-paced workshop where attendees will spend most of their time coding.

## Workshop Requirements

To ensure that you can fully participate in the workshop and make the most of the hands-on coding experience, you should have the following software and tools installed on your computers:

1. **JDK** (Java Development Kit) 17 or later: You should have the latest version of the JDK installed. You can download it from the official Oracle website or use an OpenJDK distribution via https://sdkman.io/jdks.
2. **IntelliJ IDEA**: We recommend using IntelliJ IDEA Ultimate as your IDE for Kotlin development. However, the Community Edition is sufficient for this workshop and can be downloaded from the JetBrains website.
Kotlin plugin for IntelliJ IDEA: Kotlin plugin comes bundled with IntelliJ IDEA by default.  
3. **Git**: A version control system like Git will be helpful for cloning the workshop's starter project and following along with the instructors. You can download Git from the official website or use the Git plugin in IntelliJ IDEA.
4. **Ktor and Kafka libraries**: To save time during the workshop, you should download the Ktor and Kafka libraries in advance. You can find the specific versions you’ll need in the workshop's starter project, which can be cloned from the provided Git repository.
5. **Docker**: You will need Docker to run Apache Kafka, Zookeeper, and the Redpanda UI, as well as any other required services for the workshop. You can download and install Docker Desktop from the official website.

Make sure to download the following images before the workshop:
    docker pull confluentinc/cp-kafka:7.3.1
    docker pull confluentinc/cp-zookeeper:7.3.1
    docker pull docker.redpanda.com/vectorized/console:master-173596f
    docker pull confluentinc/cp-schema-registry:7.3.1
    
6. **Basic knowledge of Kotlin**: Since the workshop focuses on building microservices with Ktor and Kafka using Kotlin, you should have a basic understanding of Kotlin programming.
7. **Insomnia REST Client**: To test the RESTful services and WebSocket communication developed during the workshop, you should install Insomnia. Insomnia is a powerful HTTP and GraphQL client that allows you to interact with APIs easily. You can download and install it from the official website: https://insomnia.rest/download
