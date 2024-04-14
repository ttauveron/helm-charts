# Helm Charts

## Add this repository
```
helm repo add ttauveron https://ttauveron.github.io/helm-charts
helm repo update
```

## List charts versions

```
helm search repo ttauveron --versions
```

## Install a chart example

```
helm upgrade --install whoami ttauveron/whoami
```
