# Task 4: Kubernetes YAML Files Overview 🌟

Welcome to **Task 4**! This folder showcases essential Kubernetes configuration files focused on advanced networking and ingress management. Below is a detailed overview of the key files and their functionalities.

---

## 📂 Key Files

### 1. **`ingress.yaml`**  
> **Purpose**: Configures an Ingress resource to manage external access to services.

- **Key Features**:
  - 🌍 **Path Routing**: Routes traffic based on URL paths to different services.
  - 🔒 **TLS Support**: Enables HTTPS connections for enhanced security.

---

### 2. **`networkpolicy.yaml`**  
> **Purpose**: Defines a Network Policy to control the communication between pods.

- **Key Features**:
  - 🛡️ **Traffic Control**: Specifies rules for ingress and egress traffic to enhance security.
  - 🔄 **Pod Selector**: Targets specific pods based on labels.

---

### 3. **`loadbalancer.yaml`**  
> **Purpose**: Configures a LoadBalancer service for distributing incoming traffic.

- **Key Features**:
  - 📊 **Traffic Distribution**: Balances loads across multiple pods.
  - ⚡ **External Access**: Exposes services to external clients.

---

## ⚙️ How to Use

To apply the configurations defined in these YAML files, use the following command in your terminal:

```bash
kubectl apply -f <filename>.yaml
