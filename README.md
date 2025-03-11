````markdown
Deploy Dify on Kubernetes using YAML and Helm. Enjoy it!

If you like it, please give me a ⭐star⭐!
````

# Deploying Dify
## Using YAML
```shell
kubectl apply -f deployment/dify.yaml
```

## Using Helm
```shell
helm upgrade --install dify helm/dify -n dify --create-namespace
```
![dify.png](dify.png)