# k8s-simple-app


A simple web app with MongoDB deployed on Kubernetes.

---

### Key Learnings and Achievements:

- **Persistent Storage Management:**
    - Created a **local persistent volume** on the node.
    - Developed persistent volume **claims** to manage storage.

- **Deployment and Service Creation:**
    - Set up deployments and services for both the web app and MongoDB.
    - Mounted the volume to the MongoDB container to ensure data persistence.

- **Service Communication:**
    - Utilized Kubernetes services to enable communication between the web app and MongoDB pods within the cluster.

- **Secure Configuration Management:**
    - Implemented Kubernetes secrets to securely store and manage credentials.
    - Used config maps to manage and store required configuration data.

- **Deployment Strategies and Optimization:**
    - Worked with deployment strategies, setting `maxSurge` to address MongoDB persistent data locking issues during pod restarts.


### Run 

```bash 
kubectl apply -f . 
```

