# citus-chart

this repo is deprecated, its moved to 
https://github.com/sergioprates/prates-charts

Execute:

helm repo add jetstack https://charts.jetstack.io
helm repo update
helm install cert-manager --create-namespace --namespace cert-manager --version v1.5.4 jetstack/cert-manager --set installCRDs=true --wait --debug

Enter in the citus folder
> helm install citus .

For install with values.dev.yaml file
> helm install citus . -f values.dev.yaml

This chart is in  https://github.com/sergioprates/prates-charts

helm repo add prates-charts https://sergioprates.github.io/prates-charts/

helm install citus prates-charts/citus --debug --wait