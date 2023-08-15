# Techlan London Site

Built using HUGO

# Installation

`git clone https://github.com/techlan23/techlan-london-site.git`

```bash
cd techlan-london-site

docker build . -t techlan-london-site:v0

kubectl create -f techlan.yaml

kubectl create -f techlan-service.yaml
```
