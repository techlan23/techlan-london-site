# Techlan London Site

Built using HUGO

# Installation

## Prerequisites

* Docker CLI
* Kubernetes configured

Clone the repo

`git clone https://github.com/techlan23/techlan-london-site.git`

Clone in the theme submodule

`git submodule update --init`


Build the image locally

```bash
cd techlan-london-site

docker build . -t techlan-london-site:v0
```

Deploy to k8s

```bash
kubectl create -f techlan.yaml

kubectl create -f techlan-service.yaml
```
