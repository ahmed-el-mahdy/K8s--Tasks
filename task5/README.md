# Task 5: Kubernetes YAML Files Overview 🚀

Welcome to **Task 5**! This folder contains vital Kubernetes configuration files focusing on StatefulSets, Persistent Volumes, and ConfigMaps. Below is a detailed overview of the key files and their functionalities.

---

## 📂 Key Files

### 1. **`statefulset.yaml`**  
> **Purpose**: Configures a StatefulSet for managing stateful applications.

- **Key Features**:
  - 📦 **Stable Identity**: Each pod in the StatefulSet gets a unique, stable identity.
  - 💾 **Persistent Storage**: Automatically provisions persistent storage for each pod.

---

### 2. **`persistentvolume.yaml`**  
> **Purpose**: Defines a Persistent Volume (PV) to provide storage resources.

- **Key Features**:
  - 🗄️ **Storage Abstraction**: Decouples storage from the pod lifecycle.
  - 📈 **Dynamic Provisioning**: Supports automatic volume provisioning based on storage class.

---

### 3. **`persistentvolumeclaim.yaml`**  
> **Purpose**: Configures a Persistent Volume Claim (PVC) for requesting storage.

- **Key Features**:
  - 📄 **Resource Request**: Specifies the desired amount and type of storage.
  - 🔄 **Binding**: Automatically binds to an available Persistent Volume.

---

### 4. **`configmap.yaml`**  
> **Purpose**: Manages application configuration data through a ConfigMap.

- **Key Features**:
  - 🛠️ **Decoupling Configuration**: Keeps configuration separate from application code.
  - 🔗 **Environment Variables**: Easily injects configuration data into pods.

---

## ⚙️ How to Use

To apply the configurations defined in these YAML files, use the following command in your terminal:

```bash
kubectl apply -f <filename>.yaml
