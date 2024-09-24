
# Task 2: Kubernetes YAML Files Overview 🚀

Welcome to **Task 2**! This folder contains essential Kubernetes configuration files that focus on advanced deployment strategies, including persistent storage and config management. Below is an overview of the key files and their functionalities.

---

## 📂 Key Files

### 1. **`persistent-volume.yaml`**  
> **Purpose**: Defines a persistent volume for storage.

- **Key Features**:
  - 📦 **Storage Type**: Specifies the type of storage (e.g., NFS, AWS EBS).
  - 📏 **Capacity**: Sets the storage capacity to meet application needs.

---

### 2. **`persistent-volume-claim.yaml`**  
> **Purpose**: Claims a persistent volume for use by a pod.

- **Key Features**:
  - 📝 **Access Modes**: Configures how the volume can be accessed (ReadWriteOnce, ReadOnlyMany).
  - 🔗 **Binding**: Automatically binds to a suitable persistent volume.

---

### 3. **`configmap.yaml`**  
> **Purpose**: Manages configuration data for applications.

- **Key Features**:
  - 📄 **Key-Value Pairs**: Stores application configuration as key-value pairs.
  - 🔄 **Dynamic Updates**: Enables dynamic updates to configuration without redeploying pods.

---

## ⚙️ How to Use

To apply the configurations defined in these YAML files, use the following command in your terminal:

```bash
kubectl apply -f <filename>.yaml
