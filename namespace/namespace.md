# Kubernetes Commands Explanation

This document explains the sequence of Kubernetes commands you provided.

---

## 1. List all Namespaces
```bash
kubectl get ns
```
This command lists all the namespaces in the Kubernetes cluster. Namespaces help in organizing and managing resources.

---

## 2. Create a New Namespace
```bash
kubectl create ns nginx
```
This creates a new namespace named **nginx**. Namespaces isolate resources within the cluster.

---

## 3. Run a Pod in the Namespace
```bash
kubectl run nginx --image=nginx -n nginx
```
This creates and runs a pod named **nginx** in the `nginx` namespace using the official **nginx** container image.

---

## 4. Get Pods in the Namespace
```bash
kubectl get pods -n nginx
```
This command lists all pods running inside the `nginx` namespace.

---

## 5. Delete the Pod
```bash
kubectl delete pod nginx -n nginx
```
This deletes the pod named **nginx** inside the `nginx` namespace.

---

## 6. Delete the Namespace
```bash
kubectl delete ns nginx
```
This deletes the entire namespace **nginx**, along with all the resources created inside it (including pods, services, etc.).

---

# Summary
1. Checked namespaces  
2. Created a new namespace `nginx`  
3. Ran an nginx pod inside it  
4. Verified pod creation  
5. Deleted the pod  
6. Deleted the namespace  
