# spinnaker-simpledemo


```sh
kubectl port-forward $(kubectl get pod -lapp=spin-kub-demo -o jsonpath='{.items[0].metadata.name}') 5000:8000
```