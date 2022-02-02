# Kubernetes Hard Way

in this repository consist of materials to provide kubernetes cluster with vagrant and kubeadm

## Vagrant Command
```bash
vagrant up
vagrant status
vagrant halt
vagrant destroy
```

## Kubernetes Administration
```bash
cd configs
export KUBECONFIG=$(pwd)/config
```

## Get Token
```bash
cd configs
cat token | xclip -selection c
kubectl proxy &
```