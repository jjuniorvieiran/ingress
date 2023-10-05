# ingress

## overview 
+ enable trafik
+ traffic routing
+ traffic reliablility

## k8s network fundamentals
+ network topology/3 network tips: pod, node, cluster network 

## networking in kubernetes 
+ same pod different containers: containers communicate each other via localhost
+ different pods: different ip inside same network 

## abstracting pods as services
+ Services: Service entity act as a proxy to each pod
+ selecter.app: nginx ➡️ label used to selected target pods