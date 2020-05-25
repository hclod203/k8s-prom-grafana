
     kubectl apply --filename https://raw.githubusercontent.com/giantswarm/prometheus/master/manifests-all.yaml
     kubectl port-forward --namespace monitoring service/grafana 3000:3000
