# ams-ms-on-k8s

## steps in killercoda:

```sh
$ git clone https://github.com/abbassizied/ams-ms-on-k8s.git
$ kubectl create namespace ams-database 
$ kubectl create namespace ams-backend
$ kubectl apply -f ./mysql 
$ kubectl apply -f ./pma
$ kubectl apply -f ./backend

$ kubectl get statefulset
$ kubectl get pods
$ kubectl get services 
```
