# Task 1: Kubernetes YAML Files Overview 🚀

Welcome to **Task 1**! This folder contains essential Kubernetes configuration files designed to facilitate the deployment and management of applications within a Kubernetes cluster. Below is an overview of the key files and their functionalities.

---

## 📂 Key Files

### 1. **`deployment.yaml`**  
> **Purpose**: Defines the deployment of an application in Kubernetes.

- **Key Features**:
  - 📈 **Scaling**: Specifies the desired number of replicas for horizontal scaling.
  - 🐳 **Container Configuration**: Configures the container image and environment variables.
  - 💻 **Resource Management**: Sets resource requests and limits for CPU and memory.

---

### 2. **`service.yaml`**  
> **Purpose**: Exposes the application to the network.

- **Key Features**:
  - 🌐 **Service Type**: Defines the service type (e.g., ClusterIP, NodePort, LoadBalancer).
  - 🔄 **Port Mapping**: Configures port mappings to route traffic to the correct pods.

---

### 3. **`namespace.yaml`**  
> **Purpose**: Organizes resources within a specific namespace.

- **Key Features**:
  - 🏢 **Resource Isolation**: Enables isolation and management of resources.
  - 🌍 **Multi-tenancy Support**: Facilitates multi-tenancy within a Kubernetes cluster.

---

## ⚙️ How to Use

To apply the configurations defined in these YAML files, use the following command in your terminal:

```bash
kubectl apply -f <filename>.yaml
