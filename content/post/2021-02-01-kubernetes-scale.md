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
    NAME                                   READY     STATUS    RESTARTS   AGE
    kubernetes-bootcamp                    1/1       Running   0          11s
```

We can check application logs:
```sh
$ kubectl logs kubernetes-bootcamp-5c69669756-wv2rp
Kubernetes Bootcamp App Started At: 2018-10-20T13:38:41.537Z | Running On:  kubernetes-bootcamp-5c69669756-wv2rp
```

