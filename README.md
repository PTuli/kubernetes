# kubernetes
```
- kubectl apply -f pod.yaml
- kubectl describe pod nginx
- k get pods -o wide
k describe pods
k edit pod podname
k apply -f sample.yaml
k run pod redis --image=redis --dry-run -o yaml > redis.yaml
k create -f redis.yaml
k explain replicaset
k apply -f filename -- to save any edits
k scale rs new-replica-set --replicas=5
k create deployment httpd-frontend --replicas=3 --image=httpd:2.4-alpine --dry-run=client -o yaml>abc.yaml
k get deploy
k set image deploy depname containername=<newimge>


```
