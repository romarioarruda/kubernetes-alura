## Verificando instalação do kubectl

`$ kubectl version --client`


## Iniciando o cluster

`$ minikube start --vm-driver=virtualbox`


### Comandos Básicos

**Lista os Nós**

`$ kubectl get nodes`

**Cria um pod de forma declarativa**

`$ kubectl apply -f portal-noticias.yml`

**Cria um pod de forma imperativa**

`$ kubectl run nginx-pod --image=nginx:latest`

**Lista os pods**

`$ kubectl get pods`

**Assiste e lista a criação de pods**

`$ kubectl get pods --watch`

**Descreve informações do pod**

`$ kubectl describe pod nome-pod`

**Deleta um pod de forma declarativa**

`$ kubectl delete -f primeiro-pod.yml`

**Deleta um pod de forma imperativa**

`$ kubectl delete pod nginx-pod`



### Links úteis

https://kubernetes.io/docs/tasks/tools/

https://minikube.sigs.k8s.io/docs/start/

https://www.virtualbox.org/wiki/Downloads