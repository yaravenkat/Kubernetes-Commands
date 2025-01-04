# Kubernetes-Commands

**Cluster Management:**
- kubectl cluster-info – Check cluster info
- kubectl get nodes – List all nodes
- kubectl describe node <node-name> – Describe a node
- kubectl get componentstatuses – Check cluster health

**Namespaces:**
- kubectl get namespaces – List namespaces
- kubectl create namespace <namespace-name> – Create namespace
- kubectl delete namespace <namespace-name> – Delete namespace

**Pods:**
- kubectl get pods – List pods (default namespace)
- kubectl get pods -n <namespace> – List pods (specific namespace)
- kubectl describe pod <pod-name> – Describe a pod
- kubectl delete pod <pod-name> – Delete a pod

**Deployments:**
- kubectl get deployments – List deployments
- kubectl create deployment <name> --image=<image> – Create deployment
- kubectl set image deployment/<name> <container>=<new-image> – Update deployment
- kubectl scale deployment <name> --replicas=<count> – Scale deployment
- kubectl delete deployment <name> – Delete deployment

**Services:**
- kubectl get services – List services
- kubectl expose deployment <name> --type=<type> --port=<port> – Create service
- kubectl describe service <name> – Describe service
- kubectl delete service <name> – Delete service

**ConfigMaps & Secrets:**
- kubectl get configmaps – List ConfigMaps
- kubectl create configmap <name> --from-literal=<key>=<value> – Create ConfigMap
- kubectl get secrets – List Secrets
- kubectl create secret generic <name> --from-literal=<key>=<value> – Create Secret

**Persistent Volumes & Claims:**
- kubectl get pv – List PVs


