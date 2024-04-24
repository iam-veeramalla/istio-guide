# Istio

### Admission Controllers

Admission controllers in Kubernetes enforce policies on objects during their creation or modification. They intercept requests to the Kubernetes API server before objects are persisted and can modify or deny requests based on predefined rules.

### Sidecar Containers

In Kubernetes, sidecar containers are auxiliary containers that run alongside the main application container within the same pod. They enhance or extend the functionality of the main container, such as handling networking, logging, or monitoring tasks.

### What is a Service Mesh?

A service mesh is a dedicated infrastructure layer for handling service-to-service communication within a distributed application. It provides features like traffic management, observability, security, and resilience without requiring changes to the application code.

### Why do you need a Service Mesh?

Service meshes address challenges in managing microservices architectures by offering centralized control over communication, improving reliability through features like circuit breaking and retries, enhancing security with mutual TLS, and providing visibility into service interactions.

### Traffic Management

Traffic management in a service mesh involves controlling the flow of requests between services. This includes features such as load balancing, routing, traffic shaping, and fault tolerance mechanisms like retries and circuit breaking.

### Virtual Services

Virtual services in Istio define how incoming requests to a service should be routed to different versions or subsets of that service. They enable sophisticated traffic management strategies like A/B testing and canary deployments.

### Destination Rules

Destination rules in Istio configure the traffic policies applied to the traffic destined for a particular service version or subset. They define things like load balancing algorithms, circuit breaking settings, and TLS settings for communication between services.

### Circuit Breaking

Circuit breaking is a pattern used to prevent cascading failures in distributed systems. In Istio, it involves setting thresholds for error rates or latency, and if these thresholds are exceeded, requests to a service are automatically stopped, preventing further damage.

### mTLS (Mutual TLS)

Mutual TLS in Istio ensures secure communication between services by requiring both the client and the server to present a valid TLS certificate. It encrypts traffic and provides authentication, preventing unauthorized access or eavesdropping.

### Gateways

Gateways in Istio allow external traffic to enter the service mesh. They act as ingress and egress points for traffic, enabling communication between services inside the mesh and external clients or services outside the mesh.

### Observability

Observability in a service mesh refers to the ability to monitor, trace, and analyze the behavior and performance of services. It includes features like distributed tracing, metrics collection, and logging to provide insights into the health and operation of the system.

### Service Mesh vs Ingress

A service mesh operates at the layer of service-to-service communication within a cluster, providing features like traffic management, security, and observability. In contrast, an ingress controller manages external access to services within the cluster, typically handling tasks like load balancing, SSL termination, and routing based on HTTP/HTTPS requests.


