# Task 3: Kubernetes YAML Files Overview 🚀

Welcome to **Task 3**! This folder contains vital Kubernetes configuration files that demonstrate advanced service configurations, including deployments and scaling. Below is an overview of the key files and their functionalities.

---

## 📂 Key Files

### 1. **`deployment.yaml`**  
> **Purpose**: Defines a deployment for managing replicas of your application.

- **Key Features**:
  - ⚙️ **Replicas**: Specifies the number of pod replicas for high availability.
  - 🔄 **Rolling Updates**: Supports seamless updates to application versions.

---

### 2. **`service.yaml`**  
> **Purpose**: Exposes the deployment as a network service.

- **Key Features**:
  - 🌐 **Service Type**: Configures service types (ClusterIP, NodePort, LoadBalancer).
  - 🔗 **Port Mapping**: Maps service ports to the target pod ports.

---

### 3. **`hpa.yaml`**  
> **Purpose**: Configures Horizontal Pod Autoscaler for scaling pods based on CPU utilization.

- **Key Features**:
  - 📈 **Autoscaling**: Automatically adjusts the number of pod replicas based on CPU load.
  - ⚖️ **Metrics**: Sets the target metrics for scaling actions.

---

## ⚙️ How to Use

To apply the configurations defined in these YAML files, use the following command in your terminal:

```bash
kubectl apply -f <filename>.yaml
