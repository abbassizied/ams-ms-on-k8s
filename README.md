# ams-ms-on-k8s

## steps in killercoda:

```sh
$ git clone https://github.com/abbassizied/ams-ms-on-k8s.git
$ kubectl create namespace ams-database 
$ kubectl create namespace ams-backend

$ cd ams-ms-on-k8s

# you can see the IP address of each pod with:
$ kubectl get pods -o wide --all-namespaces

$ kubectl apply -f ./mysql 
$ kubectl apply -f ./pma
$ kubectl apply -f ./backend


$ kubectl get sts -n ams-database
$ kubectl get pods -n ams-database
$ kubectl get svc -n ams-database

$ kubectl get sts -n ams-backend
$ kubectl get pods -n ams-backend
$ kubectl get svc -n ams-backend 

```
