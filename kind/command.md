Comando para criar o cluster no kind

```kind create cluster --name <nome do cluster> --config 1.kind-cluster.yaml

kubectl config use-context <nome do cluster>


Criando INGRESS-NGINX
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/kind/deploy.yaml

Deletando o cluster kind

```kind delete clusters $(kind get clusters)


