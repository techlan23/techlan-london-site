# Techlan London Site

Built using HUGO

# Installation

## Prerequisites

* Docker CLI
* Kubernetes configured

Clone the repo

```bash
git clone https://github.com/techlan23/techlan-london-site.git

cd techlan-london-site
```

Clone in the theme submodule

`git submodule update --init`


Build the image locally

```bash
docker build . -t techlan-london-site:v0
```

Deploy to k8s

```bash
kubectl create -f techlan.yaml

kubectl create -f techlan-service.yaml
```
