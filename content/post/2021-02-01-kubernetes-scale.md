---
title: Scaling My Kubernetes Deployment
date: 2021-02-01
tags: ["kubernetes", "code"]
---

Scaling My Kubernetes deployment

<!--more-->

```sh
    $ kubectl scale deployments/kubernetes-bootcamp --replicas=4
```

Now, check whether it is scaled up:
```sh
    $ kubectl get deployments
 
    $ kubectl get pods -o wide
  
```

