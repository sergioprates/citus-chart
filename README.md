# citus-chart
Execute:

> kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.5.4/cert-manager.yaml

Enter in the citus folder
> helm install citus .

For install with values.dev.yaml file
> helm install citus . -f values.dev.yaml