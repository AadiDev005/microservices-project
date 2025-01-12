# Microservices-Based Project Journey 🚀  

Welcome to the repository showcasing my journey of building a scalable and robust microservices-based application. This project is a testament to my passion for **Advanced Java**, **Microservices**, and **DevOps**, and encapsulates my learnings, challenges, and achievements.  

---

## 📖 **Project Overview**  

This project aimed to develop a scalable system using:  
- **Spring Boot** for microservices.  
- **PostgreSQL** as the database.  
- **RabbitMQ** for asynchronous messaging.  
- **Zipkin** for distributed tracing.  
- **Minikube** and **Kubernetes** for containerization and orchestration.  

The system follows a distributed microservices architecture with features like API Gateway routing, fault tolerance, and dynamic service discovery.  

---

## 🛠️ **Key Technologies Used**  

- **Java 17**  
- **Spring Boot (Microservices)**  
- **Spring Cloud (Eureka, Feign)**  
- **Docker & Kubernetes**  
- **PostgreSQL**  
- **RabbitMQ**  
- **Zipkin** for tracing.  
- **JMeter** for performance testing.  
- **Spring Security (JWT)**  

---

## 📑 **Journey and Learnings**  

### **1️⃣ Day 1–5: Setting the Foundations**  
- Built microservices for `Company`, `Job`, and `Review`.  
- Established inter-service communication using **Eureka** and **Feign**.  
- Containerized services using **Docker** for seamless portability.  

### **2️⃣ Day 6–8: Enhancing Observability and Performance**  
- Integrated **Zipkin** for distributed tracing across services.  
- Conducted load testing with **JMeter** to identify bottlenecks.  
- Optimized service communication with `@LoadBalanced` RestTemplate and reactive WebClient.  

### **3️⃣ Day 9–11: Deployment and Resilience**  
- Deployed the services on **Kubernetes** using **Minikube**.  
- Ensured fault tolerance using **Resilience4j**.  
- Configured dynamic routing with **Spring Cloud Gateway**.  

---

## 🌟 **Major Challenges and Solutions**  

1. **Bean Creation Errors**:  
   - Fixed improper interface annotations and implemented services correctly.  

2. **NullPointerExceptions**:  
   - Added null checks and used `Optional` for safe handling.  

3. **Inefficient Database Calls**:  
   - Replaced redundant `existsById()` with single fetch operations.  

4. **Hardcoded URLs**:  
   - Adopted service discovery and externalized configurations for flexibility.  

5. **Missing Resilience Features**:  
   - Integrated retries, fallbacks, and circuit breakers with **Resilience4j**.  

6. **Deployment Issues**:  
   - Followed Kubernetes best practices to ensure scalability and proper resource allocation.  

---

## 🏆 **Key Achievements**  

- Mastered **Spring Boot** and **Spring Cloud** to build production-ready microservices.  
- Gained proficiency in containerization using **Docker**.  
- Successfully deployed and managed services in **Kubernetes**.  
- Implemented end-to-end tracing with **Zipkin**, enhancing system observability.  
- Designed secure and scalable RESTful APIs using **JWT Authentication**.  

---

## 🔍 **What I Learned**  

1. **Repository Pattern** for efficient database access.  
2. **Entity Relationships** in JPA and avoiding circular references with annotations.  
3. Advanced **PostgreSQL** features for high-performance database operations.  
4. Building resilient, asynchronous systems with **RabbitMQ**.  
5. **Spring Actuator** for monitoring application health and lifecycle.  
6. Practical Kubernetes concepts like **Deployments**, **ReplicaSets**, and **Service Types**.  

---

## 🚀 **Next Steps**  

- Deep dive into **Reactive Microservices** with Spring WebFlux.  
- Explore **CI/CD pipelines** using Jenkins and GitHub Actions.  
- Enhance system monitoring with **Prometheus** and **Grafana**.  
- Scale services on a cloud platform like AWS or GCP.  

---

## 📂 **How to Run the Project**  

### Prerequisites  
1. Install **Docker**, **Java 17**, and **Maven**.  
2. Set up **Minikube** or a Kubernetes cluster.  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/AadiDev005/microservices-project  
