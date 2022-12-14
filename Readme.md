# AVOLENS Helm Repository

## Add Repo
```
helm repo add avolens 'https://helm.avolens.com/releases/'
helm repo update
helm repo list
```

## Install ETH Node
```
helm show values avolens/eth-node > values.yaml
```

EDIT values.yaml as you need it!
```
helm install -f values.yaml eth-node avolens/eth-node

```
