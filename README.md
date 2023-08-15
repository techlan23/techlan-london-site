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

```bash
cd techlan-london-site

docker build . -t techlan-london-site:v0

kubectl create -f techlan.yaml

kubectl create -f techlan-service.yaml
```
