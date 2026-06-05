# Day 1 - Kubernetes Pod and Jupyter Notebook Setup

## Objective

Learn how to access a remote GPU environment and launch Jupyter Notebook for AI/ML development.

## Topics Covered

* Introduction to Kubernetes
* Understanding Pods
* SSH access to remote server
* Basic Linux terminal commands
* Launching Jupyter Notebook inside a Kubernetes Pod
* Accessing Jupyter through a browser

## Commands Practiced

### Connect to Server

```bash
ssh username@server-ip
```

### Check Pods

```bash
kubectl get pods
```

### Access a Pod

```bash
kubectl exec -it my-pod -- bash
```

### Launch Jupyter Notebook

```bash
jupyter notebook --NotebookApp.token='1234'
```

## Key Concepts Learned

### Kubernetes

Kubernetes is a container orchestration platform used to manage and deploy applications.

### Pod

A Pod is the smallest deployable unit in Kubernetes and can contain one or more containers.

### Jupyter Notebook

Jupyter Notebook is an interactive environment used for writing and running Python code, especially for data science and machine learning.

## Outcome

Successfully connected to the GPU environment, accessed a Kubernetes Pod, and launched Jupyter Notebook for future AI and Machine Learning experiments.
