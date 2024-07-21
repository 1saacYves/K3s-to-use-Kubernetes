# K3s-to-use-Kubernetes

## Instalação K3s

```
https://docs.k3s.io/quick-start
```
1. Isso fará o download do binário e registrará um serviço do sistema para que o K3s seja iniciado automaticamente quando o host for reinicializado:

```
curl -sfL https://get.k3s.io | sh -s - --write-kubeconfig-mode 644
```

## Verifique o status do k3s

```
sudo systemctl status k3s
```

## Interaja com o Cluster

1. Use o comando para interagir com seu cluster com a versão empacotada do Kubectl:


```
 sudo k3s kubectl get nodes
```
